# Change log

## v2.0.8
- Updated Merqury tool_state to include `output_add_headers` and `output_selector` parameters required by `merqury/1.3+galaxy4`
- Updated Convert characters1 to `v1.0.1`

## v2.0.7
- Updated merqury tool version string from `1.3` to `1.3+galaxy4` — the bare `1.3` wrapper is no longer available on the Galaxy toolshed, causing a validation error on import. The underlying merqury version is unchanged.

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
