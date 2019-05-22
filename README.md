# Toshiba MeP-c4 for Ghidra
 
## Description

This repository contains a toy implementation of the Toshiba MeP-c4 for [Ghidra](https://github.com/NationalSecurityAgency/ghidra).

## Notes

XML schemas are available in `ghidra.git/Ghidra/Framework/SoftwareModeling/data/languages/`. They can be
used to verify the definitions using, for example:
```
xmllint --relaxng language_definitions.rxg --format mep_c4.ldefs
```
