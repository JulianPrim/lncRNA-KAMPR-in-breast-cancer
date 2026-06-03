# KAMPR function in breast cancer cells


This repository contains the R code used to generate the figures for our paper:
**“The drug- and hormone-responsive lncRNA KAMPR inhibits antigen presentation and links endocrine resistance to immune-cold breast cancer.”**

The scripts analyze the role of **KAMPR/LINC00885** in breast cancer using public transcriptomic and single-cell datasets, together with TCGA-based analyses. The repository includes code for comparing KAMPR/LINC00885-positive and -negative cancer epithelial cells, assessing its association with steroid signaling, endocrine resistance, interferon and antigen-presentation pathways, and evaluating its relationship with immune infiltration and patient outcome.

The analyses include:

* Differential and visualization analyses of **KAMPR⁺ versus KAMPR⁻ epithelial cancer cells** from the Wu et al. breast tumor single-cell RNA-seq atlas: *A single-cell and spatially resolved atlas of human breast cancers*, Nature Genetics, 2021, DOI: 10.1038/s41588-021-00911-1.

* Generation of half-violin plots for genes associated with **steroid signaling, endocrine resistance, luminal differentiation, interferon signaling, TGFβ signaling, migration, and antigen presentation**, based on KAMPR/LINC00885 expression status in breast cancer epithelial cells.

* Analysis of treated ER+ breast cancer cell lines, including **T-47D and ZR-75-1**, from Ors et al.: *Estrogen regulates divergent transcriptional and epigenetic cell states in breast cancer*, Nucleic Acids Research, 2022, DOI: 10.1093/nar/gkac908. These analyses quantify changes in the fraction of KAMPR/LINC00885-positive cells over time and across hormone/drug treatments.

* UMAP visualization of treated breast cancer cells and time-course plots of KAMPR-positive cell fractions from the Ors et al. dataset, together with heatmap visualization of KAMPR expression changes among KAMPR-positive cells, normalized as log2 fold change relative to untreated controls.

* Analysis of endocrine therapy response using paired responsive and resistant ER+ breast cancer biopsies from Xia et al.: *Integrated DNA and RNA Sequencing Reveals Drivers of Endocrine Resistance in Estrogen Receptor-Positive Breast Cancer*, Clinical Cancer Research, 2022, DOI: 10.1158/1078-0432.CCR-21-3189. These analyses include KAMPR/LINC00885 expression changes, immune score comparisons, cytotoxicity score analyses, and patient-level responsive-to-resistant transitions.

* Analysis of FELINE trial snRNA-seq data from Griffiths et al.: *Cellular interactions within the immune microenvironment underpins resistance to cell cycle inhibition in breast cancers*, Nature Communications, 2025, DOI: 10.1038/s41467-025-56279-x. These scripts compare KAMPR/LINC00885 expression in letrozole-responsive versus non-responsive cancer cells across treatment time points.

* TCGA/AMOCATI-based analyses linking **KAMPR/LINC00885** expression with **HLA genes, CTL score, immune-cold tumor phenotypes, and patient survival**.

This repository provides the code used to reproduce the main transcriptomic, single-cell, immune-score, and survival analyses supporting the study.
