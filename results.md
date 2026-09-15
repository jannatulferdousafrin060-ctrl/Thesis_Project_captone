
# STAC + YOLO12m Results

## Training Configuration
- **Backbone**: YOLO12m
- **Labeled Data**: 404 images
- **Unlabeled Data**:3644 images
- **Epochs**: 50 (Phase 1) + 50 (Phase 2)
- **Batch Size**: 16
- **Learning Rate**: 0.001
- **Pseudo-label Threshold**: 0.7

## Performance Metrics

| Model | mAP@0.5 | mAP@0.5:0.95 | Precision | Recall | FPS |
|-------|----------|---------------|-----------|--------|-----|
| Teacher | 0.7283 | 0.4513 | 0.7298 | 0.6718 | 2.04 |
| Student (STAC) | 0.7332 | 0.4940 | 0.8605 | 0.5772 | 2.07 |

## Improvement
- **mAP@0.5 Improvement**: 0.0048
- **mAP@0.5:0.95 Improvement**: 0.0427

*Results generated on: 2025-12-06 18:29:36*
