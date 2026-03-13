# Release Notes — v1.0.0 (Final Project Release)

## Summary

This is the first complete release of **DengAI — Predicting Disease Spread**. The project is now fully reproducible, documented, presentation-ready, and published to GitHub.

## Highlights

- Final tuned model: **XGBoost**
- Validation performance:
  - **MAE:** 12.16
  - **R²:** 0.745
- Cross-validation mean MAE: **10.71**
- Submission file generated in required format

## Included deliverables

- Final notebook with complete workflow and conclusions
- Exported professional plots in `Image/`
- GitHub-ready README and setup files
- Full presentation deck (`.pptx`) and generation script
- Licensing and citation metadata

## Reproducibility

1. Create/activate environment
2. Install dependencies from `requirements.txt`
3. Run the notebook top-to-bottom
4. (Optional) regenerate presentation using `Documents/generate_presentation.py`

## Recommended next version (v1.1)

- Add lag/rolling time features
- Train city-specific models
- Add time-series cross-validation strategy
- Add drift monitoring report
