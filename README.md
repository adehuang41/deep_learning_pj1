# Deep Learning Project 1

This repository contains the source code and selected report assets for Project 1 of the Fudan University course *Neural Network and Deep Learning*.

## Contents

- `codes/`: NumPy implementation of the MLP, CNN, training pipeline, robustness analysis, and report-asset generation scripts.
- `project_outputs/part_b/`: selected figures and summary tables used in the report for the MLP-vs-CNN comparison.
- `project_outputs/part_c/`: selected figures and summary tables used in the report for robustness diagnosis and target-aware augmentation.
- `project_outputs/part_c_extended_drop_last/`: corrected extension summary tables for the subset-RGFT experiments.
- `report/`: LaTeX source of the final report.

## Notes

- The MNIST dataset is intentionally excluded from this repository.
- Trained checkpoints are intentionally excluded from this repository.
- Model weights are released separately on ModelScope and linked in the final report.

## Main Scripts

- `codes/test_train.py`: train individual experiments.
- `codes/test_model.py`: evaluate a saved model.
- `codes/run_project_pipeline.py`: generate the main project results and figures.
- `codes/build_hard_subset.py`: build the `random10` / `hard10` subsets for the extension.
- `codes/project_extended_analysis.py`: summarize the subset-RGFT extension results.

## Report Build

Compile the report with:

```bash
cd report
./build_report.sh
```
