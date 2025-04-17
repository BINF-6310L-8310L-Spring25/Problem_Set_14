# Problem_Set_Week_14

The goal of this problem set is to give you some real world experience in finding published data. Published data can be a rich source of new scientific study. 

You are a researcher studying **macular degeneration** which is a degenerative condition affecting the central part of the retina (the macula) and resulting in distortion or loss of central vision.

You come across an article titled "The impact of non-additive genetic associations on age-related complex diseases" which conducts a GWAS on 22 age-related diseases. 

_Abstract_

_Genome-wide association studies (GWAS) are not fully comprehensive, as current strategies typically test only the additive model, exclude the X chromosome, and use only one reference panel for genotype imputation. We implement an extensive GWAS strategy, GUIDANCE, which improves genotype imputation by using multiple reference panels and includes the analysis of the X chromosome and non-additive models to test for association. We apply this methodology to 62,281 subjects across 22 age-related diseases and identify 94 genome-wide associated loci, including 26 previously unreported. Moreover, we observe that 27.7% of the 94 loci are missed if we use standard imputation strategies with a single reference panel, such as HRC, and only test the additive model. Among the new findings, we identify three novel low-frequency recessive variants with odds ratios larger than 4, which need at least a three-fold larger sample size to be detected under the additive model. This study highlights the benefits of applying innovative strategies to better uncover the genetic architecture of complex diseases._

You want to examine the **raw summary statistics for macular degeneration on the X-Chromosome** for this phenotype. 


Here is the article: https://www.nature.com/articles/s41467-021-21952-4 

## Step 1 
Find the raw summary statistics

## Step 2 
Answer the following questions 

### Question 1

What is the effect allele for the SNP with the most significant P-value for both males and females together?

### Question 2

What position on the X chromosome has the biggest difference in the effect size (beta) between males and females. 

### Question 3

Test this hypothesis with a t-test. 
Hypothesis: In females, SNPs with an effect allele frequency less than 0.05 have a smaller effect on macular degeneration than SNPs with an effect allele frequency greater than or equal to 0.05. 

### Question 4

You previously discovered that rs142658961 was implicated in macular degeneration. Use the SNPdb https://www.ncbi.nlm.nih.gov/snp/ to find information about this SNP. 

What is the effect allele and beta for this rs in males?
