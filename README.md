# TarMet
TarMet is a shiny application for targeted metabolic analyses based on mass spectrometry.

## Installation  

### R users:

	install.packages(c("devtools", "data.table", "enviPat", "Matrix", "shiny", "plotly"))
	source("https://bioconductor.org/biocLite.R")
    biocLite(c("MassSpecWavelet", "mzR"))
	library(devtools)
	install_github("zmzhang/baselineWavelet")

	install_github("hcji/TarMet")
	
### Not R users
Download TarMet at [url](https://www.researchgate.net/profile/Hongchao_Ji/publication/322061960_Setup_file_of_TarMet_software/data/5a41a79f0f7e9ba868a19a58/setup-TarMet.7z) and install like a normal windows application.

## Usage:
  A [user guide](https://github.com/hcji/TarMet/blob/master/inst/TarMet.pdf) is included in the package	

## Contact
  For any questions, please contact:  ji.hongchao@foxmail.com