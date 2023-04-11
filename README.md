# albacore_gtseq_panel_development

This repository documents development of the Oregon State University State Fisheries Genomics Lab Albacore Tuna GTseq Panel. It contains all information needed to understand how the albacore gtseq panel was designed including ascertainment data, feature selection, primer design, validation and optimization.

A short summary is available in the file titled "panel_executive_summary"

The "panel_development.docx" file provides a narrative description of the panel development process with a high level of detail.

Further details, including fully reproducible logs of the components of this work completed by Dayan can be found at https://github.com/david-dayan/Albacore_feature_selection

# Panel Design Overview

![flowchart](https://github.com/State-Fisheries-Genomics-Lab/albacore_gtseq_panel_development/blob/main/notes/flowchart.png)
Overview of panel development. Two ascertainment datasets were used to select three sets of genomic features for inclusion in the panel. Consensus sequences surrounding the target features were inferred using the ascertainment data and an assembly of the Bluefin Tuna genome. Primers were designed from these consensus sequences by GTseek LLC and the panel was optimized using two validation libraries. 
* There are 170 spatial outliers, but 59 overlap with the FST outliers.
* There are 384 individual DNA libraries in validation library 2, but only the best 100 were used. 


# Files and Directories

Each subdirectory has its own detailed readme.

## Files (Main Directory)

__panel_executive_summary.docx__: Short description of panel development  
__panel_development.docx__: This document collates all information about panel development into a single location. 
## Directories

__Final Panel__: information on the finalized, 289 marker panel  
__Supplemental Files__: directory of the most important result tables, logs and other outputs  
__Notes__: other files  

