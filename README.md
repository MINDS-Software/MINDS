# MinION + MinIT generated long reads data analysis pipeline for detection and classification of genomic sample(s) {MINDS} #

## Developed by: CCDC CBC, U.S. Army, APG ; ##
###  Authors: samir.v.deshpande.ctr@mail.mil ###

## Installation ##

------------
Setup an conda environment using miniconda
1. conda create -n MINDS --file requirements.yml
2. source activate MINDS
3. mkdir MINDS ;

    create the following folders inside the MINDS  folder.

        a. centrifuge_db
	b. centrifuge_rslts
        c. code
        d. docs
        e. fastq
        f. logs
        g. reports

------------
4. Downlaods the centrifuge specific database indexes  from https://ccb.jhu.edu/software/centrifuge/

## To activate environment ##

source activate MINDS

## To deactivate environment ##

source deactivate

------------

## Running the application usage ##
source activate MIBDS
cd projects/MINDS
jupyter notebook

------------
## Team ##

Dr. Samir V Deshpande

Dr. Timothy Reed

Dr. Raymond Sullivan

Dr. Mary M. Wade

------------

#### Last Update Date ####

10/30/2019
By SVD
