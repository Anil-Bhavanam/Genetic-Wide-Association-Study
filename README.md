# Genetic-Wide-Association-Study
Genome-wide association studies (GWAS) are widely used in genetics to identify genetic variants associated
with complex traits or diseases. One common approach in GWAS is to compare the frequency of genetic variants
between cases and controls using statistical tests. Fisher's exact test is a popular choice for analyzing 
categorical data, making it suitable for examining the association between genetic variants and diseases.

#  Fisher's Exact Test:
For each genetic variant, create a 2x2 contingency table representing the allele count or genotype 
frequency in cases versus controls.

Apply Fisher's exact test to calculate the p-value for the association between each variant and 
the phenotype of interest.

Adjust the p-values using the BH procedure to account for multiple testing.

#  Significance Threshold:
Set a significance threshold (e.g., p-value < 0.05) to determine which associations are considered statistically significant.

#  Interpretation and Follow-up:

Identify genetic variants that surpass the significance threshold, indicating potential associations with the trait or disease.

Perform functional annotation to understand the biological relevance of the significant variants.

Conduct further analysis, such as pathway enrichment analysis or gene set enrichment analysis, to gain insights into the biological 
pathways or processes implicated by the identified variants.

# Conclusions:

This project aims to conduct a GWAS using Fisher's exact test and apply the BH procedure to detect significant
genetic variants associated with a specific trait or disease. The utilization of Fisher's exact test allows for 
the analysis of categorical data, while the BH procedure helps control the false discovery rate due to multiple testing.
By following these steps, researchers can uncover genetic variants that contribute to the understanding of the trait or
disease under investigation, potentially leading to improved diagnosis, treatment, or prevention strategies.
