# vcfprocessing
Versions 1-5 of VCF merging scripts written to concatenate single sample VCF files into a multisample file. In order to implement the scripts require several conditions:
  -A local installation of snpEff with hg19 annotation database. Please refer to http://snpeff.sourceforge.net/SnpEff_manual.html#cmdline
   for further information
  -A directory within snpEff termed "input" as follows ~/snpEff/snpEff/input/*
  -The "input" directory can contain subfolders for each sample or tissue type which will contain the target VCFs
  -It is critical the the versions of the VCFs are the same. Merging 4.0 with 4.1 and above will produce unintelligible files
  
  


