# Changelog

All notable changes to this project are documented in this file.

## [1.0.0] - 2026-03-13

### Added

- Complete end-to-end notebook pipeline for DengAI forecasting:
  - Data loading, cleaning, feature engineering, EDA
  - Model training and comparison across 10 regressors
  - XGBoost hyperparameter tuning with grid search
  - Cross-validation and validation diagnostics
  - Test prediction and submission generation
- Professional visual exports to `Image/`:
  - Target analysis
  - Model comparison
  - Feature importance
  - Validation actual-vs-predicted
  - City-month heatmap
  - Residual diagnostics
  - Yearly trend by city
- Executive Summary and Presentation-Ready Conclusion sections in notebook.
- GitHub-ready documentation:
  - `README.md`
  - `LICENSE` (MIT)
  - `requirements.txt`
  - `.gitignore`
- PowerPoint deliverables:
  - `Documents/generate_presentation.py`
  - `Documents/DengAI_Project_Presentation.pptx`
- Citation metadata and release documentation.

### Changed

- Updated project author naming in README to:
  - **Assimagbe Albert Raphael**
- Added official header image usage in both README and notebook.

### Fixed

- Plot export logic now handles city-based plotting source correctly.
- Removed temporary Office lock file from version control workflow.
