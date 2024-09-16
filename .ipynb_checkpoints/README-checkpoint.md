Notebooks: 
- 0_preprocessing:
	- Creates a panda dataframe, neuroblast_GT_preprocessed.csv, that has all the samples and the appropriate labels if present
- 1_feature_extraction:
	- Extracts all features of the annotated samples' image files and join it to the respective sample ids
	- Remove all sample ids that has no MYCN label
	- Creates a panda dataframe, samples_post_extraction_and_labelled.csv, that has all available labelled samples with the respective features extracted.
- 2_models:
	- train and test models on the dataset produced by feature_extraction
