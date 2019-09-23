# deduplicate_by_sequence
This script reads paired-end BAM files, and deduplicates alignments based purely on exact matches of the first 50bp of both reads. Its sole purpose is to work with paired-end, Bowtie2 mapped files used for the eccDNA project.
