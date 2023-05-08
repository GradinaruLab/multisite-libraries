# multisite-libraries
Code to analyze substitution libraries generated between VR IV, VR V, and VR VIII.


Within each subfolder, there are files for analysis of the respective sequencing runs and two folders for raw data and analysis output. The fastq files should be placed in the raw data with the following format: '
'SAMPLENAME_SAMPLENUMBER_L001_R1_001.fastq', where SAMPLENAME is changed to reflect the naming of the sample (which is referred to in the code), SAMPLENUMBER is changed based on the sample number in the sequencing run, and the read is R1 or R2, depending on which paired end is being sequenced. FASTQ files of sequenced libraries can be examined with files labeled `FASTQ_seq_counting.ipynb` or `FASTQ_barcode_counting.ipynb`. 
Data anlysis is done with the other notebook within each subfolder.

Within each file, the code has some changes to reflect the differences between the datasets. 

For installation, the following packages will be required:
pip install numpy, pandas, biopython, pepars, tqdm, bokeh, and iqplot.
