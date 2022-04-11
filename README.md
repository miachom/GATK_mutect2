
This pipeline is for running Mutect2 from GATK4.2.5, annotating and then subsetting to CGC genes of interest. These are WGS data of tRCC pateints on 18 samples. The pipeline is variant calls using Mutect2 for a single sample run followed by filtering and annotation with SnpEff.

The run can be split into chromosomes or by specifying co-ordinates to run in parallel otherwise a single run can take ~60-90hrs! If scatter and gather method is used, additional steps of merging vcfs are required at the end. All the bam files are from Srinivas lab at DFCI. 
