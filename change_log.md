# Change log

## v2.0.6
- Updated label for reads (assembly reads not raw reads)
- Added workflow report text into the workflow annotation, as it sometimes disappears

## v2.0.0

- Created new steps to calculate genome coverage
- Created a new table for assembly statistics, called metrics.tsv, which includes genome coverage and selected lines from Fasta Statistics
- New default settings for BUSCO: lineage = eukaryota; for Quast: lineage = eukaryotes, genome = large
- Created a new table to report BUSCO versions and dependencies
- Edited workflow report to display these two new tables - assembly metrics and BUSCO versions


## v1.1.0

- Updated meryl to the latest version in the workflow: `Galaxy Version 1.3+galaxy6`
- Fixed input data issue: added raw reads as input to meryl 
- Thanks to:
     - Katherine Farquharson & Lauren Alexander (University of Sydney) for reporting the workflow issue and testing workflow version 1.1.0.
     - Galaxy Australia team for troubleshooting the workflow

## v1.0.0

Initial workflow version
