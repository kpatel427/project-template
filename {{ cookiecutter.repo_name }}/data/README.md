## data/

### Summary
The goal of `data/` is to maintain descriptions of samples and their associated files in raw and processed formats. Samples are described in `data/EXPERIMENT.csv`, and files for samples are described in `data/raw/MANIFEST.csv` and `data/endpoints/MANIFEST.csv`. Organization:

* `data/EXPERIMENT.csv` has metadata for each sample. This csv, yaml, or xlsx file should be organized according to the submission standards of the [NCBI BioSample database](https://submit.ncbi.nlm.nih.gov/biosample/template/), or the [samples section of the metadata for a GEO submission](https://www.ncbi.nlm.nih.gov/geo/info/submission.html). `data/EXPERIMENT.csv` is an example of human samples according to the BioSample submission guidelines, and `data/EXPERIMENT.xlsx` is a example of human samples according to the GEO guidelines.
* `data/raw/` - holds lab or CHOP center generated data that should never be deleted. 
* `data/raw/MANIFEST.csv` holds paths to data raw files (bam, fastq, png, bfile, etc.). The goal of `data/raw/MANIFEST.csv` is to associate samples with raw files for archival purposes. This csv, yaml, or xlsx file should be organized according the [GEO submission guidelines](https://www.ncbi.nlm.nih.gov/geo/info/submission.html), or [SRA guidelines](https://www.ncbi.nlm.nih.gov/sra/docs/submitbio/).
* `data/interim/` - an unregulated space to put intermediate and temporary files
* `data/ref-data/` - external/public datasets that are not supplied by RIS or your lab. Folow [RIS reference_data structure](https://github.research.chop.edu/RIS/reference_data).
* `data/endpoints/` - generated files to support papers or grants. `data/endpoints/MANIFEST.csv` describes all important files in `data/endpoints/` and tags them with a sample. The goal of this MANIFEST is to associate samples with important files for later use. TThis csv, yaml, or xlsx file should be organized according the [GEO submission guidelines](https://www.ncbi.nlm.nih.gov/geo/info/submission.html), or [SRA guidelines](https://www.ncbi.nlm.nih.gov/sra/docs/submitbio/). Try to organize file by type endpoint subdirectories by file type (bam, fastq, etc).
