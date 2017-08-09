[![Build Status](https://travis-ci.org/broadinstitute/ichorCNA.svg?branch=master)](https://travis-ci.org/broadinstitute/ichorCNA)

# *ichorCNA*
ichorCNA is a tool for estimating the fraction of tumor in cell-free DNA from ultra-low-pass whole genome sequencing (ULP-WGS, 0.1x coverage). 

## ichorCNA Wiki Page
**For more details on usage/pipelines, outputs, and FAQs, please visit the [GitHub Wiki page for ichorCNA](https://github.com/broadinstitute/ichorCNA/wiki)**

## Description
ichorCNA uses a probabilistic model, implemented as a hidden Markov model (HMM), to simultaneously segment the genome, predict large-scale copy number alterations, and estimate the tumor fraction of a ultra-low-pass whole genome sequencing sample (ULP-WGS). 

The methodology and probabilistic model are described in:  
Adalsteinsson, Ha, Freeman, et al. Scalable whole-exome sequencing of cell-free DNA reveals high concordance with metastatic tumors. (2017) Nature Communications, in press.

The analysis workflow consists of 3 major tasks:  
1. Computing read coverage from ULP-WGS  
2. Data normalization  
3. CNA prediction and estimation of tumor fraction of cfDNA

## Contacts
Please contact [Gavin Ha](gavinha@broadinstitute.org) with any questions or feedback.

## Acknowledgements
ichorCNA is developed and maintained by Gavin Ha, Justin Rhoades, and Sam Freeman.  

This work was done in collaboration with  
- **Blood Biopsy Group**, Group Leader **Viktor Adalsteinsson**, Broad Institute of MIT and Harvard
- Laboratory of **Matthew Meyerson**, Medical Oncology, Dana-Farber Cancer Institute
- Laboratory of **J. Christopher Love**, Koch Institute for integrative cancer research at MIT
- Laboratory of **Gad Getz**, Cancer Program, Broad Institute

## Software License
ichorCNA
Copyright (C) 2017  Broad Institute

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
