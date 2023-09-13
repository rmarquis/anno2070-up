# anno2070-up

Anno 2070 Unofficial Patch

## Notes

* The patch should work with both the base game and the Deep Ocean expansion.
* Not tested in MP so far.
* This is for Vanilla, English language game only.
* Mods are likely incompatible, but could be modified to integrate this patch.

## Installation

* make a backup copy of your `patch8.rda` and `patch9.rda` in `/maindata`
* replace both files with the provided `patch8.rda` and `patch9.rda` files
* delete the `guidata64` folder (to force UI cache to be recreated at restart)

## Changelog

* Adjusted colour and font of epilepsy warning
* Removed deprecated Facebook buttons
  * on achievements
  * on senate and world council votes panels
  * on screenshots panel
  * on Find Contact panel, replaced by Annoverse Discord link
* Removed deprecated Open Game Table button in Domination
* Changed date format from American (mm/dd/yy) to British English (dd/mm/yy)
* Changed Arsenal tooltip text and icon to "Heavy Weapons" instead of "Weapons" with Ammunition icon
* Added in-game production ratio in production building tooltips
* Added END shortcut to enable simple cam mode
* Fixed various typo

## Packaging

Because git diff works better with files encoded in UTF-8, the code in this repository is stored as
UTF-8. To prepare a `.rda` package that you can use:

* change the files encoding from `UTF-8` to `UTF-16 BE`
* use [RDA Explorer](https://github.com/lysannschlegel/RDAExplorer) to package the files
