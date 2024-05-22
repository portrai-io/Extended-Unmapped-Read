# Overview

Extended Unmapped Read is a method that builds on the conventional approach of handling sequences that do not map to any specific database or reference genome, commonly used in microbiome analysis. This technique utilizes the 16S rRNA reference of a specific microbial species to determine the genetic distance of this particular microbial species within the microbiome. Detailed information about this method can be found in this repository and is also discussed in our paper.

The Extended Unmapped Read method enhances microbiome analysis by utilizing the 16S rRNA reference of specific microbial species to measure their genetic distances within the microbiome. This technique enables quantitative analysis of genetic characteristics, facilitating the identification of genetic differences among microbiome species across different tissues. This method shows potential as a useful tool for understanding the composition, function, and dynamic changes of the microbiome. It can be applied to various research areas, including exploring relationships with diseases, assessing ecological impacts, or uncovering new biological pathways.

# Data

When specifying `tissue_dir`, ensure the directory includes five crucial files typically produced by the 10X Visium platform:

- `filtered_feature_bc_matrix.h5`
- `spatial/tissue_positions_list.csv`
- `spatial/tissue_lowres_image.png`
- `spatial/tissue_hires_image.png`

# Requirements

1. Install dependencies: `pip install -r requirements.txt`


# Public Data Download

|No   | Sample Name           |                                                                                   
|-----|-----------------------|
|1| Oral_Squamous_Cell_Carcinoma   |
|2| Colorectal_Cancer|

These datasets were used in our paper. You can access and download the datasets using the follw links:
https://github.com/FredHutch/Galeano-Nino-Bullman-Intratumoral-Microbiota_2022.


# Contact

We, as Portrai. Inc., innovate the process of developing new drugs beyond the limits of human cognition, and deliver safer and more effective new drugs to humanity. For any questions or inquiries, please contact us at [contact@portrai.io](mailto:contact@portrai.io).

