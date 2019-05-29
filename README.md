# Toshiba MeP-c4 for Ghidra
 
## Description

This repository contains a toy implementation of the Toshiba MeP-c4 processor
for [Ghidra](https://github.com/NationalSecurityAgency/ghidra).

## Installation

```
git clone https://github.com/guedou/ghidra-processor-mep
ln -s /flashre/ghidra-processor-mep/ ${GHIDRA_HOME}/Processors/MEP_C4/
cd ${GHIDRA_HOME}/Processors/MEP_C4/
sleigh -ax
```

## Notes

XML schemas are available in `ghidra.git/Ghidra/Framework/SoftwareModeling/data/languages/`. They can be
used to verify the definitions using, for example:
```
xmllint --relaxng language_definitions.rxg --format mep_c4.ldefs
```
