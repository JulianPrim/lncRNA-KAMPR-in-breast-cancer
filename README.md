# KAMPR function in breast cancer cells

This repository contains the R code used to generate the figures for our paper:  
**“The drug- and hormone-responsive lncRNA KAMPR inhibits antigen presentation and links endocrine resistance to immune-cold breast cancer.”**

The scripts analyze the role of **KAMPR/LINC00885** in breast cancer using public transcriptomic and single-cell datasets, together with TCGA-based analyses. The repository includes code for comparing KAMPR/LINC00885-positive and -negative cancer epithelial cells, assessing its association with steroid signaling, endocrine resistance, interferon and antigen-presentation pathways, and evaluating its relationship with immune infiltration and patient outcome.

The analyses include:

- Differential and visualization analyses of **KAMPR⁺ versus KAMPR⁻ epithelial cancer cells** from the Wu et al. breast tumor single-cell RNA-seq atlas.
- Generation of half-violin plots for genes associated with **steroid signaling, endocrine resistance, luminal differentiation, interferon signaling, TGFβ signaling, migration, and antigen presentation**.
- Analysis of treated ER+ breast cancer cell lines, including **T-47D and ZR-75-1**, to quantify changes in the fraction of KAMPR/LINC00885-positive cells over time and across hormone/drug treatments.
- UMAP visualization of treated breast cancer cells and time-course plots of KAMPR-positive cell fractions.
- Heatmap visualization of KAMPR expression changes among KAMPR-positive cells, normalized as log2 fold change relative to untreated controls.
- Analysis of endocrine therapy response using paired responsive and resistant breast cancer biopsies, including immune score and cytotoxicity score comparisons.
- Analysis of FELINE trial snRNA-seq data to compare KAMPR/LINC00885 expression in letrozole-responsive versus non-responsive cancer cells.
- TCGA/AMOCATI-based analyses linking KAMPR/LINC00885 expression with **HLA genes, CTL score, immune-cold tumor phenotypes, and patient survival**.

Overall, this repository provides the code used to reproduce the main transcriptomic, single-cell, immune-score, and survival analyses supporting the study.
