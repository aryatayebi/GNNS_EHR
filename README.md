# GNNS_EHR

Use on BIGPURPLE Cluster

Preprocess: Creates preprocessed data used in BERT and Downstream models
- preprocessed_xall_with_outcome

Bert_WithMultipleGPU: Creates pretrained model used in Downstream models and the following files used for Downstream
- mapping_dict, study_indexes, final_list_modified pickle files

Downstream Notebooks: Takes in mapping_dict, study_indexes, final_list_modified, preprocessed_xall_with_outcome and evaluates model
