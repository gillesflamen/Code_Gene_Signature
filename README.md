# Code FMP 
This repository contains all the code used for the creation of the gene signature described in the paper:

"Machine Learning-Based Gene Expression Signature for  Classification of Endocrine Therapy Sensitivity in ER+ Breast Cancer Patients"

# Content

- Code_Preprocess_QC_DEA_Internal_RNAseq_data.Rmd

Contains all the preprocessing steps that the Internally generated bulk RNAseq data underwent. As well the QC, the DEA, and functional analysis.

- Code_Preprocess_QC_DEA_Combined_RNAseq_data.Rmd

Contains all the preprocessing steps and QC that, first, the Gou et al. bulk RNAseq data underwent, and subsequently, the merging resulting in the Combined Internal with Gou et al. data underwent. Next, the QC, the DEA, and functional analysis of the Combined data. 

- Code_Preprocess_QC_snRNAseq_data.Rmd

Contains all the preprocessing steps that the snRNAseq data underwent. Additionally, QC and filtering of the cells. Finally, generation of the two types of pseudobulk RNAseq sets: the summing up of the counts across cells, and the averaging of expression across cells. 

- Code_Model_Training_Validation_.Rmd

Contains the code to train the Hallmark-genes model, the LASSO feature selection scripts, the training and testing of the LASSO-selected genes model. The loading, preprocessing, and QC of the Xia et al. bulk RNAseq validation set. Validation of the neural network models with the Xia et al. data, the snRNAseq data cell-by-cell wise, and the two pseudobulks, averaged and summed. 


