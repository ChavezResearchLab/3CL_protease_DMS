This is repository containing the code and  data for testing SARS-CoV-2 3CL single mutant fitness for all possible amino acid mutations. 

1. The [sample_spreadsheet](https://github.com/ChavezResearchLab/3CL_protease_DMS/blob/main/sample_spreadsheet_RSA.csv) file contains the information necessary for producing read counts.  
2. The read count is generated by running [this notebook](https://github.com/ChavezResearchLab/3CL_protease_DMS/blob/main/Master_notebook_alignment_free_read_count.ipynb). The outputs of the notebook are a series of unnormalized activity scores organized by set deposited [here](https://github.com/ChavezResearchLab/3CL_protease_DMS/tree/main/Data) with directory suffix _matrices_ for each set. Statistics for individual residues have directory prefix _amino_acid_. 
3. These raw data are then normalized and processed into heatmap form [here](https://github.com/ChavezResearchLab/3CL_protease_DMS/blob/main/Fig2-Generate_heatmaps_with_glu_stop-codon_norm.ipynb). 
4. Heatmap data in CSV form can be found [here](https://github.com/ChavezResearchLab/3CL_protease_DMS/blob/main/CSVs/glu_gal_WT_stop_normalize.csv). 
5. Notebooks for generating individual figures are prefixed in this repository by _Fig_ and point to the figure that they generate. All figures are generated from the jupyter notebooks referring to the figure number of interest.
6. An interactive version of the heatmap can be found on the [lab website](https://chavezlab.com/).
7. For raw sequencing reads please refer to NCBI BioProject PRJNA702507.
