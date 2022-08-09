<!-- README.md is generated from README.Rmd. Please edit that file -->

# XMAS2 Tutorial

## :book: Procedures

This tutorial was organized according to the **XMAS 2.0** functions.

-   In the beginning three chapters, we specially provided the basic
    requirements of bioinformatics and overview on microbiota, and the
    installation of XMAS.

-   In **Chapter 4**, we convert the results from in-house pipeline into
    phyloseq-class object for downstream data analysis.

-   In **Chapter 5** provided the functions to evaluate the data
    quality.

-   In **Chapter 6**, we introduced the preprocessing methods on
    microbiota data before differential analysis.

-   In **Chapter 7** provided the alpha diversity analysis.

-   In **Chapter 8** provided the beta diversity analysis.

-   In **Chapter 9** provided the microbiota composition analysis.

-   In **Chapter 10** provided the core microbiota analysis.

-   In **Chapter 11** provided the differential analysis.

-   In **Chapter 12** provided some functions for visualization.

-   In **Chapter 13** provided the association analysis.

-   In **Chapter 14** showed the principals of the differential analysis
    methods.

-   In **Chapter 15** provided the examples by using XMAS 2.0 on
    microbiota data.

## :writing_hand: Authors

1.  [Hua Zou](zouhua@xbiome.com)

## :wrench: Change log

### XMAS 2.1.7

-   add `preprocess_ps` including keep taxa in rows, filter taxa whose
    abundance is zero, fix duplicated tax, replace the taxa NA with the
    higher level taxa unclassified, filter samples whose library size is
    zero. (2022-07-20)
-   add `check_samples`. (2022-07-20)
-   add `phyloseq_qc`. (2022-07-20)
-   add `keep_taxa_in_rows`. (2022-07-20)
-   add `fix_duplicate_tax`. (2022-07-20)
-   add `fix_na_tax`. (2022-07-20)
-   add `convert_taxa_name`. (2022-07-20)
-   modify `run_cor`. (2022-07-20)
-   modify `run_partial_cor`. (2022-07-20)
-   modify `determine_tables`. (2022-07-20)
-   modify `run_maaslin2`. (2022-07-20)
-   modify `run_ANOSIM`. (2022-07-20)
-   modify `core_members`. (2022-07-20)
-   modify `run_alpha_diversity`. (2022-07-20)
-   modify `run_beta_diversity`. (2022-07-20)
-   modify `run_rank_abundance`. (2022-07-20)
-   modify `run_MantelTest`. (2022-07-20)
-   modify `run_MRPP`. (2022-07-20)
-   modify `run_ordination`. (2022-07-20)
-   modify `run_permanova`. (2022-07-20)
-   modify `run_RefCheck`. (2022-07-20)
-   modify `plot_core_taxa`. (2022-07-20)
-   modify `core_matrix`. (2022-07-20)
-   modify `plot_StackBarPlot`. (2022-07-20)
-   modify `aggregate_LOD_taxa`. (2022-07-20)
-   modify `summarize_taxa`. (2022-07-20)
-   modify `summarize_LowAbundance_taxa`. (2022-07-20)
-   modify `run_filter`. (2022-07-20)
-   modify `run_filter2`. (2022-07-20)
-   modify `run_filter2`. (2022-07-20)
-   fix bugs `run_alpha_diversity`. (2022-07-21)
-   fix bugs `run_beta_diversity`. (2022-07-21)
-   fix bugs `plot_RankAbundance`. (2022-07-21)
-   add parameters `run_permanova`. (2022-07-21)
-   add parameters `run_ANOSIM`. (2022-07-21)
-   add parameters `run_MRPP`. (2022-07-21)
-   add parameters `run_alpha_diversity`. (2022-07-21)
-   add parameters `run_beta_diversity`. (2022-07-21)
-   add parameters `run_MantelTest`. (2022-07-21)
-   add parameters `run_permanova`. (2022-07-21)
-   modify `import_metaphlan_taxa` for *metaphlan3*. (2022-07-22)
-   add `run_locom`. (2022-07-27)
-   add parameter `plot_StackBarPlot`. (2022-07-27)
-   modify usage of scripts. (2022-07-27)
-   add `ggord`. (2022-07-28)
-   modify `run_locom`. (2022-08-05)
-   modify `plot_StackBarPlot`. (2022-08-08)
-   add parameters `plot_StackBarPlot`. (2022-08-08)
-   modify `preprocess_ps`. (2022-08-08)

### XMAS 2.1.6

-   add *Gut microbiota Data from Zeybel et al. - 2022*. (2022-07-06)
-   add `run_cor`. (2022-07-06)
-   fix bugs `run_lefse`. (2022-07-07)
-   add `run_partial_cor`. (2022-07-08)
-   fix bugs `summarize_LowAbundance_taxa`. (2022-07-08)
-   fix bugs `summarize_taxa`. (2022-07-11)
-   add parameter *group_number* in `plot_barplot`, `plot_boxplot` and
    `plot_dotplot`. (2022-07-11)
-   change parameter `run_RefCheck`. (2022-07-11)
-   add `plot_correlation_heatmap`. (2022-07-12)
-   fix bugs `aggregate_LOD_taxa`. (2022-07-13)
-   add *CA* in `run_ordination`. (2022-07-13)
-   fix bugs `summarize_taxa`. (2022-07-13)
-   fix bugs `plot_Ordination`. (2022-07-13)
-   fix bugs `summarize_LowAbundance_taxa`. (2022-07-14)
-   fix bugs `summarize_LowAbundance_taxa2`. (2022-07-14)
-   fix bugs `plot_StackBarPlot`. (2022-07-14)
-   add `wes_palette`. (2022-07-15)
-   add parameters `plot_Ordination`. (2022-07-18)
-   add parameters `plot_barplot`. (2022-07-18)
-   add parameters `plot_boxplot`. (2022-07-18)
-   add parameters `plot_dotplot`. (2022-07-18)
-   add parameters `plot_Dada2Track`. (2022-07-18)
-   add parameters `plot_taxa_heatmap`. (2022-07-18)
-   add parameters `plot_lefse`. (2022-07-18)
-   add parameters `plot_RankAbundance`. (2022-07-18)
-   add parameters `plot_topN_boxplot`. (2022-07-18)
-   add parameters `plot_2DA_venn`. (2022-07-18)
-   add parameters `plot_volcano`. (2022-07-18)
-   add `run_lefse2`. (2022-07-18)
-   fix bugs `determine_tables`. (2022-07-19)
-   fix bugs `run_lefse`. (2022-07-19)
-   fix bugs `run_lefse2`. (2022-07-19)

### XMAS 2.1.5

-   add *paired* parameter in `run_ttest` and `run_wilcox`. (2022-06-27)
-   add *Data from Early Childhood Antibiotics and the Microbiome (ECAM)
    study*. (2022-06-27)
-   add `run_filter2`. (2022-06-29)
-   fix bugs in `determine_tables`. (2022-06-29)
-   fix bugs in `run_RefCheck`. (2022-06-30)
-   fix bugs in `run_RefCheck`. (2022-07-03)
-   modify the scripts’ annotations. (2022-07-05)
-   fix bugs in `run_multiple_da`. (2022-07-05)
-   fix bugs in `run_edger`. (2022-07-05)

### XMAS 2.1.4

-   fix bugs in `plot_Dada2Track` and `plot_RarefCurve`. (2022-06-06)
-   fix bugs in `determine_tables`. (2022-06-07)
-   format the codes in elegant style. (2022-06-08)
-   fix bugs in `import_dada2_taxa`. (2022-06-13)
-   fix bugs in `run_permanova`, `run_ANOSIM` and `run_MRPP`.
    (2022-06-14)
-   fix bugs in `get_GroupPhyloseq`. (2022-06-14)
-   fix bugs in `run_RefCheck`. (2022-06-15)
-   fix bugs in scripts, for instance, replacing “SampleID” by
    “TempRowNames”. (2022-06-15)
-   fix bugs in `run_lefse`. (2022-06-16)
-   fix bugs in `plot_RankAbundance`, `transform_abundances` and
    `run_trim`. (2022-06-17)
-   update **SchematicFigure** in vignettes and README. (2022-06-20)
-   add `plot_double_barplot`. (2022-06-20)
-   fix bugs in `aggregate_LOD_taxa`. (2022-06-22)
-   fix bugs in `import_metaphlan_taxa`. (2022-6-24)

### XMAS 2.1.3

-   add `aggregate_LOD_taxa` and rename scripts. (2022-05-31)

### XMAS 2.1.2

-   reassign the packages to *imports* or *suggests*. (2022-05-26)

### XMAS 2.1.1

-   fix bugs in `run_permanova`, `plot_multiple_DA`,
    `summarize_LowAbundance_taxa` and `plot_boxplot`. (2022-05-23)

### XMAS 2.1.0

-   add `run_mulitple_da` and `plot_multiple_DA` for multiple DA
    methods’ results. (2022-05-18)

### XMAS 2.0.13

-   fix bugs. (2022-05-17)

### XMAS 2.0.12

-   Add `run_MantelTest`. (2022-05-11)
-   Add `plot_2DA_venn`. (2022-05-11)
-   Modify `plot_taxa_heatmap` and `plot_dotplot`. (2022-05-12)
-   Add topN significant taxa boxplot `plot_topN_boxplot` (2022-05-12)
-   Add `run_MRPP`. (2022-05-13)
-   Add `run_rank_abundance` and `plot_RankAbundance`. (2022-05-13)
-   Add `run_impute` for imputation. (2022-05-13)

### XMAS 2.0.7 (2022-04-12)

-   Add global view modules and other parts.

### XMAS 2.0.2 (2022-03-17)

-   Recode the differential analysis scripts `run_aldex` etc.
-   Modify the import scripts.

### XMAS 2.0.1 (2022-03-14)

-   Rearrange the package’s structure.

### XMAS 1.0.0 (2021-12-13)

-   The final version 1.0.0.

### Initial repository 0.0.1 (2021-07-25)

-   Submitted to gitlab.
