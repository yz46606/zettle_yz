 `K202304281321` Enrichment of differential express genes in SMAD4/9 RARA binding genes
 
 Key words: `DEG differential expression gene` `ChIP-seq` `RNA-seq` `enrichment` `SMAD9/4` `RARA` 
 
# Question

if differential expressed genes upon RA exposure is significantly overlaped with SMAD4/9 binding genes. if so,
how to measure this significance?  similar questions also see in [K202304281506_SLAMEnrich.md](./K202304281506_SLAMEnrich.md)

I plan to use fisher-exact test to measure the significancy of enrichment.

in further exploring, it would be interesting to exploring the under-represent or over-represent of DEG genes that involved in apoptoiss, cycle arest, differentiation and TGF-beta signaling super family.

# Results summary  

Related Work log ID: [W202304281332_OverlapEnrich.md](https://github.com/yz46606/Working_record/blob/main/W202304281332_OverlapEnrich.md)

1. DEG genes is significantly over-represent with SMADs/RARA binding peaks. suggesting the direct regulation of RARA/SMADs on gene expression.
2. differential related genes are tend to up-regulated in 1, 3 and 6 days. cell cycle genes are under-represent in up-regulated genes in first 3 days while signficantly down-regulated in 6 days. apoptosis genes represent a averaged proportion in DEG genes, while TGF-beta genes tend to down-regulated after 3 days.
