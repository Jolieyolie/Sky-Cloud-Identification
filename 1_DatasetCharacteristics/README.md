# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** https://data.mendeley.com/datasets/4pw8vfsnpx
- **Dataset Owner/Contact:** Universidade Federal de Santa Catarina

- **Second option:** https://zenodo.org/records/16647156?preview_file=test_set.zip (test and train set, 4 classes for altitude); not used in this project, but possible for an additional future training
- **Dataset Owner/Contact:** DLR Institute of Solar Research

### Dataset Characteristics
- **Number of Observations:** 996 annotated images, collected between March and October 2021, at 2592×1944 resolution
- **Number of Classes:** 5 (4 cloud types + 1 background/object class)

### Target Variable/Label
- **Label Name:** Cirriforms, Cumuliforms, Stratiforms, and Stratocumuliforms
- **Label Type:** Classification
- **Label Description:** identify clouds in images, predict weather trends
- **Label Values:** type of clouds, if low or high, if water saturated or not,..
- **Label Distribution:** [Brief description of class balance for classification or value distribution for regression]

### Feature Description
[Provide a brief description of each feature or group of features in your dataset. If you have many features, group them logically and describe each group. Include information about data types, ranges, and what each feature represents.]

<img width="467" height="230" alt="Bildschirmfoto 2026-05-10 um 13 44 20" src="https://github.com/user-attachments/assets/c9f94537-81e4-47b0-bf4f-7771ec38dde4" />

Data type: 

- **Feature 1 (Arvore):** representation of other objects (trees, buildings)
  
- **Feature 2 (Stratocumuliformes):** lower clouds (1-4km), very humid
  
- **Feature 3 (Stratiformes):** horizontal, appear in stratified atmosphere
  
- **Feature 4 (Cirriformes):** high clouds
  
- **Feature 5 (Cumuliformes	):** vertically developed clouds, less common in this dataset (mountainous Brazilian region favors drier conditions)

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
