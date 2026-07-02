# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** Faster- R-CNN
- **Rationale:** Faster R-CNN was chosen as baseline because it provides reliable bounding-box detection without the added complexity of instance segmentation, allowing for a clean performance comparison against the Mask R-CNN approach on the same dataset.

### Model Performance
- **Evaluation Metric:** mean average precision (maP)
- **Performance Score:** maP=0.3417
- **Cross-Validation Score:** Cross-validation was not performed, a train/validation/test split was used instead (consistent with the literature)

### Evaluation Methodology
- **Data Split:** Train/Validation/Test split ratios: 70/15/15
- **Evaluation Metrics:** maP: to evaluate the selection; and iou: to evaluate the chosen boxes and segementations

### Metric Practical Relevance
[Explain the practical relevance and business impact of each chosen evaluation metric. How do these metrics translate to real-world performance and decision-making? What do the metric values mean in the context of your specific problem domain?]

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
