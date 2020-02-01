# Welcome to Tejaswi Iyyanki GitHub pages


## Download The cancer genome atlas (TCGA) RNASeq Data for Breast cancer cohort using R

[View the code walkthrough here](https://tejaswiiyyanki.github.io/Code-Examples/getTCGA_BRCA_data.html).
Output of these files are shared here in a [Dropbox Link](https://www.dropbox.com/s/zoolb28fsbderno/Archive.zip?dl=0)

## Process Breast Cancer RNASeq Data with R and visualize it quick as a Heatmap
[View the code here](https://tejaswiiyyanki.github.io/Code-Examples/Data-Processing-and-Matrix-with-R.html).
Output of processed and filtered BRCA log2(TPM) gene expression matrix is [here](https://www.dropbox.com/s/mqcx5rxqzl9ek1l/TCGA_BRCA_Tumor_RSEM_GeneExp_filtered_log2.tsv?dl=0).

## Unsupervised exploratory analysis of Breast cancer RNASeq data using R to identify clinically relevant subtypes, consensus clustering and clinical
*Lets take a look at why we often divide patient population into clusters for precision medicine and personalized healthcare*
This is similar in marketing where customers are divided into market segments. Often these market segments may have features that desire a customization in specific product features. For example Starbucks own seattle's best coffee, which has a brand loyalty and price sensitivity that is distinct from the startbucks coffee brands. Starbucks would design and market features that this market segment desires in the case of seattle's best coffee.

For a personalized healthcare, we often need to treat each patient's disease as a unique case. However, in a population of patients, there are often a patient segment/cluster who show similar etiology and pathology of disease. Increase in genomic sequencing technologies and large-scale molecular profiling has allowed us to increase the number of features to identify different patient populations. This ultimately has led to precise molecular therapies that target molecular aberrations that is the source of a patient's disease. Hence this process has added tremendous value in discovering new precision medicine drugs for patients who did not benifit from traditional drugs, and as well as limit unnecessary toxicities.

Therefore, we are going to divide these patients into cohorts/clusters/segments that will allow us to discover new features that may be clinically relevant in this excercise.
