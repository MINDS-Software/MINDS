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

## To activate environment ##

source activate MINDS

## To deactivate environment ##

source deactivate

------------

## Running the application usage of syntax and explaination ##

python MINDS.py --fastq [file with full path] --c [centrifuge generated file names] --taxaid

    -fastq -argument to pass the file name with folder were the fastq files are after basecalling.

    -c -argument centrifuge generated results & report files

example:
python Centrifuge_Scorer.py -f msa_2002_lee2.fastq -t 210 -a p_compressed_MSA2002_lee2_BCN01_report-UnFiltered.txt -b p_compressed_MSA2002_lee2_BCN01_results-UnFiltered.txt
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
