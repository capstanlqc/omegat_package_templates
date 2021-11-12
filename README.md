# OmegaT project package templates

## Preconditions

It is assumed that the user's OmegaT installation has been customized with the files available [here](https://github.com/capstanlqc/omegat_customization).

## Contents

This repository contains two project templates that can be used to create project package. 

## Language tasks

You must use one template or the other, depending on the task:

* Use `OMT_untranslated.omt` for translation tasks.
* Use `OMT_pretranslated.omt` for editing tasks (verification, adaptation, etc.).

In the first case, the target-language text in the XLIFF files must be a copy of the source-language text. In the second case, the source and the target text can be different.

## Steps

To create actual project package instances, proceed like this:

1. Put the source XLIFF files in the `/source` folder.
2. Change the target language code in each project’s `omegat.project` file to the actual correct expected code.
3. Give the project package an appropriate name (ending in `_OMT`).

## Language codes

The language code used in the project settings must be taken from the **OmegaT** column of cApStAn's [Language code finder](https://capps.capstan.be/langtags.php) (or fetched using the [language code basic API](https://github.com/msoutopico/langtags_basic_api)). Use the OmegaT tag that corresponds your three-letter PISA language code.

You can check OMT packages for language code compliance with [this utility](https://github.com/msoutopico/check_omt_langtags).

