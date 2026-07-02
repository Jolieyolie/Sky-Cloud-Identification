# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** Faster- R-CNN
- **Rationale:** Faster R-CNN was chosen as baseline because it provides reliable bounding-box detection without the added complexity of instance segmentation, allowing for a clean performance comparison against the Mask R-CNN approach on the same dataset.

### Model Performance
- **Evaluation Metric:** mean average precision (maP)
- **Performance Score:** maP=0.3344
- **Cross-Validation Score:** Cross-validation was not performed, a train/validation/test split was used instead (consistent with the literature)

### Evaluation Methodology
- **Data Split:** Train/Validation/Test split ratios: 70/15/15
- **Evaluation Metrics:** mAP at IoU thresholds 0.5:0.95 and at specific thresholds mAP@50 and mAP@75, and Mean IoU as a direct measure of spatial overlap between predicted and ground-truth boxes. mAP is standard for object detection. It captures localization and classification accuracy across confidence levels, while Mean IoU complements this by isolating pure localization quality independent of classification confidence.
Test results: mAP = 0.3344, mAP@50 = 0.5225, mAP@75 = 0.3195, Mean IoU = 0.3787

### Metric Practical Relevance
mAP = 0.3344: The moderate mAP indicates in a weather-estimating context, that the model can identify cloud types with reasonable consistency, but localization precision still leaves room for error — relevant if downstream applications (e.g. coverage estimation) depend on accurate boundary detection.
mAP@50 = 0.5225: At a relaxed IoU threshold (50% overlap), the model performs considerably better, meaning it reliably detects that a cloud of a given type is present and roughly where, even if exact boundaries are imprecise. This is practically relevant for use where general estimations of cloud-type identification is sufficient, to detect the present ones.
mAP@75 = 0.3195: At stricter overlap (75%), performance drops notably, thus the precise spatial localization is the model's main limitation. This value matters for accurate cloud boundary delineation, such as estimating cloud coverage percentage.
Mean IoU = 0.3787: A moderate Mean IoU suggests the baseline model captures the general location of clouds but with imprecise boundaries — acceptable for rough weather trend estimation, but a limiting factor if the goal is precise quantitative cloud coverage analysis (analog result as maP scores)

Taken together, these results suggest the Faster R-CNN baseline is suitable for coarse cloud type identification but imply the need for a more refined approach like Mask R-CNN when precise spatial delineation is required for accurate short-weather-trend estimation tasks
## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
