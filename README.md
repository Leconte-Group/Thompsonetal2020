# Error Rate Calculations
Starting sequence data in FASTQ files, this program creates excel documents with data involving insertion, deletion, and misincorporation rates.  Sequences are aligned with a template using Bipyhons pairwise comparison and the aggregate error rate, error rate at each position, and the aggregate error spectrum is calculated.  The output is seperated by barcode (if the samples have barcodes) to identify unique experiments.

Prerequesites:

    1) Pip:

    Installation for Mac-
        curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
        sudo python get-pip.py

    2) Biopython: 

    Installation for Mac-
        sudo pip install biopython


Running the program:

    1) Open up the location with your zipped FASTQ files.  The program works with files in your current directory.
    
    2) Type in relevant template, primer and experiment information in the *USER INPUT* section.

    2) Run error_rate_calculations.py in the command line.
