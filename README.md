# OmegaT project package templates

This repository contains OmegaT project templates that can be used to create OmegaT project packages. There are different templates depending on the file type and the filter used.

## Preconditions

It is assumed that the user's OmegaT installation has been customized with the files available [here](https://github.com/capstanlqc/omegat_customization), as explained in our installation and customization guide ([Windows](https://slides.com/capstan/omegat-installation-and-customization-guide) or [Mac](https://slides.com/msoutopico/omegat-installation-and-customization-guide-mac/)).

## Steps

To create actual project package instances, proceed like this:

1. Put the source files in the `source` folder.
2. Change the target language code (text content of the `<target_lang>` node) in each project’s `omegat.project` file to the actual correct expected code.
3. Give the project package an appropriate name (if possible, ending in `_OMT`).

## Language codes

The language code used in the project settings must be taken from the **OmegaT** column of cApStAn's [Language code finder](https://capps.capstan.be/langtags.php) (or fetched using the [language code basic API](https://github.com/msoutopico/langtags_basic_api)). Use the OmegaT tag that corresponds your three-letter PISA language code.

You can check OMT packages for language code compliance with [this utility](https://github.com/msoutopico/check_omt_langtags).
