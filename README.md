# Extended Unmapped Read Analysis for Cancer Spatial Microbiome

## 🌟 Overview

Extended Unmapped Read is a method that builds on the conventional approach of handling sequences that do not map to any specific database or reference genome, commonly used in microbiome analysis. This technique utilizes the 16S rRNA reference of a specific microbial species to determine the genetic distance of this particular microbial species within the microbiome. Detailed information about this method can be found in this repository and is also discussed in our paper.

The Extended Unmapped Read method enhances microbiome analysis by utilizing the 16S rRNA reference of specific microbial species to measure their genetic distances within the microbiome. This technique enables quantitative analysis of genetic characteristics, facilitating the identification of genetic differences among microbiome species across different tissues. This method shows potential as a useful tool for understanding the composition, function, and dynamic changes of the microbiome. It can be applied to various research areas, including exploring relationships with diseases, assessing ecological impacts, or uncovering new biological pathways.

## 📊 Key Components & Data Linkage

### **1. Mismatch Ratio Analysis**
* **Core Metric**: Measures the evolutionary distance between unmapped reads and species-specific 16S rRNA references.

### **2. Statistical Results (`output/`)**
* **Taxonomic Overlap & P-value Matrices**: These are the final results of our similarity analysis, which statistically prove the contradictions in standard PathSeq results (Supplementary Figure 6).
* **Supplementary Tables**: Detailed quantitative taxonomic profiles that provide the raw numerical data for the spatial distributions visualized in **Supplementary Figure 3**.

## 🔗 Data & Code Repositories
To ensure transparency and reproducibility, all resources are publicly available as follows:

### **1. Zenodo (Internal Data: HNSC-1, HNSC-2)**
* **DOI**: [10.5281/zenodo.18763899](https://doi.org/10.5281/zenodo.18763899)
* **Contents**:
    * `raw_data_subset/`: Original FASTQ files for HNSC-1 and HNSC-2.
    * `processed_data/outs/`: Space Ranger outputs, including `unmapped_reads.bam`.
    * `processed_data/h5ad/`: AnnData objects containing calculated Mismatch Ratios for 4 species (*E. coli, S. aureus, S. epidermidis, C. pneumoniae*).
    * `output/`: Statistical result matrices and Supplementary Tables.

### **2. Public Data (External: CRC, OSCC)**
|No   | Sample Name           |                                                                                   
|-----|-----------------------|
|1| Oral_Squamous_Cell_Carcinoma   |
|2| Colorectal_Cancer|

These datasets were used in our paper. You can access and download the datasets using the follw links:
https://github.com/FredHutch/Galeano-Nino-Bullman-Intratumoral-Microbiota_2022.

### **3. GitHub (Code Repository)**
* **URL**: [https://github.com/portrai-io/Extended-Unmapped-Read](https://github.com/portrai-io/Extended-Unmapped-Read)
* **Modules**:
    * `01_Mismatch_Calculation/`: Core algorithm for calculating the Mismatch Ratio.
    * `02_Spatial_visualization/`: Scripts for Figure 1, Figure 2, and host-microbiome integrated mapping.
    * `03_Supplement/`: Codes for Fisher's Exact Test and hierarchical clustering.

## Published
https://www.biorxiv.org/content/10.1101/2024.06.09.598160v1

## Contact

We, as Portrai. Inc., innovate the process of developing new drugs beyond the limits of human cognition, and deliver safer and more effective new drugs to humanity. For any questions or inquiries, please contact us at [contact@portrai.io](mailto:contact@portrai.io).

