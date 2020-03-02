# MinION + MinIT generated long reads data analysis pipeline for detection and classification of genomic sample(s) {MINDS} #

## Developed by: CCDC CBC, U.S. Army, APG ; ##

## Installation ##

------------
Setup an conda environment using miniconda
1. conda create -n MINDS --file requirements.yml
2. source activate MINDS
3. mkdir projects
4. cd projects
5. mkdir MINDS
    create the following folders inside the MINDS  folder.

	a. centrifuge_db
	b. centrifuge_rslts
        c. code
        d. docs
        e. fastq
        f. logs
        g. reports

------------
6. Download the centrifuge specific database indexes  from https://ccb.jhu.edu/software/centrifuge/
7. Moves the database indexes into the centrifuge_db folder

## To activate environment ##

source activate MINDS

## To deactivate environment ##

source deactivate

------------

## Running the application ##
source activate MINDS
cd projects/MINDS
jupyter notebook

------------
