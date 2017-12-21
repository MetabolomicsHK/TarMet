# TarMet [![Build Status](https://www.travis-ci.org/hcji/TarMet.svg?branch=master)](https://www.travis-ci.org/hcji/TarMet)
TarMet is a shiny application for targeted metabolic analyses based on mass spectrometry.

## Installation  

### R users:

	install.packages(c("devtools", "data.table", "enviPat", "Matrix", "shiny", "plotly"))
	source("https://bioconductor.org/biocLite.R")
    biocLite(c("MassSpecWavelet", "mzR"))
	library(devtools)
	httr::set_config( httr::config( ssl_verifypeer = 0L ) )
	install_github("zmzhang/baselineWavelet")

	install_github("hcji/TarMet")
	
### Not R users
Download TarMet at [url](https://pan.baidu.com/s/1dEMfUF3) and install like a normal windows application.

## Usage:
  A [user guide](https://github.com/hcji/TarMet/blob/master/inst/TarMet.pdf) is included in the package	

## Contact
  For any questions, please contact:  ji.hongchao@foxmail.com