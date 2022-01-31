# OmegaT project package templates for OpenXML

These project templates can be used to create project package to translate Microsoft Word files.

The project settings use the Okapi OpenXML filter, which is better architected than the default OmegaT OpeXML filter, and does a better job at:

-   Avoiding tag noise (i.e. only meaningful tags are displayed)
-   Hiding leading/trailing tag pairs
-   Handling in-context exact translations (aka alternative translations in OmegaT), using a paragraph's ID
-   Handling layout for bidirectional languages

## Source langauges

There are two project templates for two different source languages: one for English and one for French. Certain settings depend on the source language, such as locked untranslatables and segmentation.

## Language tasks

This template can be used to create project packages both for translation or for editing/revision. For any language task that entails reviewing existing translations, they must come from the working TM or a reference TM (since source files must always be monolingual).
