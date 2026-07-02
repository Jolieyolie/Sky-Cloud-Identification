# Sky-Cloud-Identification

## Repository Link

https://github.com/marthab-oss/Sky-Cloud-Identification

## Description

Mask R-CNN model for detecting and segmenting 4 cloud types from the Clouds-1000 dataset, with a Faster R-CNN baseline for comparison.

### Task Type

Image Classification

### Results Summary

#### Best Model Performance
- **Best Model:** Mask R-CNN
- **Evaluation Metric:** maP and IoU
- **Final Performance:** maP=0.3933, maP@50=0.5975, maP@75= 0.3903, Mean IoU= 0.4744

#### Model Comparison
- **Baseline Performance:** Faster R-CNN
- **Improvement Over Baseline:** [Quantitative improvement, e.g., "+12% accuracy", "25% reduction in MSE"]
- **Best Alternative Model:** [Second-best model and its performance]

#### Key Insights
- **Most Important Features:** [Top 3-5 features that drive model performance]
- **Model Strengths:** [What the model does well]
- **Model Limitations:** [Known limitations and failure cases]
- **Business Impact:** [Practical implications of the model performance]

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/Cloud_data_analysis.ipynb)**
3. **[Baseline Model](2_BaselineModel/cloud_baseline_model_colab.ipynb)**
4. **[Model Definition and Evaluation](3_Model/cloud_training_model.ipynb)**
5. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Project Cover Image](CoverImage/Cover_Image_Clouds.png)
