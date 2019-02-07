## data/
* SAMPLES.csv has meta data for each sample.
* raw/ - holds lab or CHOP generated data that should never be deleted. , MANIFEST.csv holds paths to raw files and their types (bam, fastq, png, etc.). The goal of MANIFEST is to associate samples with raw files for data reuse. MANIFEST.csv includes checksums.
* interim/ - a free space to put intermediate files
* ref-data/ - external/public datasets that are not supplied by RIS or your lab. Folow [RIS reference_data structure](https://github.research.chop.edu/RIS/reference_data).
* endpoints/ - generated files to support papers or grants. MANIFEST.csv describes all important files in endpoints/ and tags them with a sample. The goal of MANIFEST is to associate samples with important files for later use. Try to organize file by type. MANIFEST.csv includes checksums.

