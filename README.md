# GlobusGenomics_Tools

#Build the images using respective Dockerfile for each tool

#Picard
docker build -t bd2kbdds/picard_test3 https://github.com/poojavade/GlobusGenomics_Tools.git#master:picard

#GATK3
docker build -t bd2kbdds/gatk3_test3 https://github.com/poojavade/GlobusGenomics_Tools.git#master:GATK3
