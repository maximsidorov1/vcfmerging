# vcfprocessing
Versions 1-5 of VCF merging scripts written to concatenate single sample VCF files into a multisample file. In order to implement the scripts require several conditions:

  -A local installation of snpEff with hg19 annotation database. Please refer to http://snpeff.sourceforge.net/SnpEff_manual.html#cmdline
   for further information
   
  -A directory within snpEff termed "input" as follows ~/snpEff/snpEff/input/*
  
  -The "input" directory can contain subfolders for each sample or tissue type which will contain the target VCFs
  
  -It is critical the the versions of the VCFs are the same. Merging 4.0 with 4.1 and above will produce unintelligible files
  
Required Dependencies:

-htslib1.6

-bcftools

-snpEff: A program for annotating and predicting the effects of single nucleotide polymorphisms, SnpEff: SNPs in the genome of Drosophila melanogaster strain w1118; iso-2; iso-3.", Cingolani P, Platts A, Wang le L, Coon M, Nguyen T, Wang L, Land SJ, Lu X, Ruden DM. Fly (Austin). 2012 Apr-Jun;6(2):80-92. PMID: 22728672

-SnpSift: "Using Drosophila melanogaster as a model for genotoxic chemical mutational studies with a new program, SnpSift", Cingolani, P., et. al., Frontiers in Genetics, 3, 2012.




  
  


