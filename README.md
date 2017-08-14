This is the source code for the article:

PIPI: PTM-Invariant Peptide Identification Using Coding Method
http://pubs.acs.org/doi/abs/10.1021/acs.jproteome.6b00485

The project was open sourced with the publication. Luckily, I did fork it at this timepoint from <https://github.com/fcyu> because now it is not available there anymore.

# PIPI
PTM-Invariant Peptide Identification.

## How to use it?
Requirement: 
- Java 1.8 or later.
- With [Percolator](https://github.com/percolator/percolator/releases) installed.

Usage:
```
java -Xmx25g -jar PIPI.jar <parameter_file> <spectra_file>
```
- ```<parameter_file>```: Parameter file. Can be downloaded along with PIPI.
- ```<spectra_file>```: Spectra file (mzXML or mgf).

example: ```java -Xmx25g -jar PIPI.jar parameter.def data.mzXML```

## Cite
Yu, Fengchao, Ning Li, and Weichuan Yu. "PIPI: PTM-Invariant Peptide Identification Using Coding Method" (under review).
