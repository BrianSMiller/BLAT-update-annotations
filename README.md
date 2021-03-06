# BLAT-update-annotations
As genomes are updated, custom genomic annotation files (e.g. GTF or GFF) need to revised to match the genomic changes. This set of scripts takes genomic annotations in the form of a GTF file and updates the annotations to work in a new version of the genome.

For a given annotation to update, these scripts extract the nucleotide sequence from the outdated genome and use BLAT (v. 36x2) to determine the location of the annotation in the new version of the genome. The output is an updated gtf file to be used with the new version of the genome. Furthermore, any annotation that had its nucleotide sequence altered due the genome update will be reported with additional information.

For usage and dependancy information see master_BLAT_and_generate_updated_annotations.sh
