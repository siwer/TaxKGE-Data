# TaxKGE-Data
Contains the raw data files (without the ontology). This was an attempt at reconstructing the data from (https://github.com/eXascaleInfolab/LBSN2Vec), both the New York City and Jakarta subsets.

Due to additional pre-processing steps, the number of check-ins varies from the numbers reported in the LBSN2Vec paper.

The current data consists of the test/train/valid splits in .txt format with 6 columns:

1. relation (always the same)
2. User ID
3. A letter indicating the hour of the day (with A indicating the time between 00:00 and 00:59, B = 01:00 - 01:59, an so on)
4. An abbreviation indicating the day of the week
5. The location Type
6. A unique location identifier 
