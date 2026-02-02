# HierSleepTransformer

**HierSleepTransformer: A Hierarchical Single-Channel Transformer with Rotary Position Embeddings for Interpretable and Generalizable Sleep Stage Classification**

**Authors:**  
Zubair Akbar · Ubaidullah Alias Kashif · Jingzhen Li · Yuhang Liu · Zedong Nie

---

## Overview

This repository contains the experimental code, evaluation pipelines, and analysis notebooks used in our study on **automatic sleep stage classification from single-channel EEG** using 30-second epochs.  
HierSleepTransformer is a hierarchical transformer architecture incorporating **rotary position embeddings (RoPE)**, designed to achieve strong performance, interpretability, and robust cross-dataset generalization.

---

## Repository Structure

- **v5.ipynb**  
  Main notebook for model development and training.

- **Paper_ready_ablation.ipynb**  
  Ablation studies reported in the paper.

- **Final_eval_all.ipynb**  
  Final evaluation and metric computation on test datasets.

- **Sub_Group_Analysis.ipynb**  
  Subgroup-based performance analysis.

- **paper_interpretability.ipynb**  
  Model interpretability and qualitative analysis.

- **data_states.ipynb**  
  Dataset statistics and sleep stage distribution analysis.

- **10_fold_FINAL.ipynb**  
  Ten-fold cross-validation analysis on the SHHS-1 dataset.

- **Full_night_matrics.ipynb**  
  Full-night, per-subject metrics computation and analysis.

- **README.md**  
  Project documentation.

---

## Datasets

The code is designed for use with:
- Public sleep datasets (SHHS, MESA)
- A private in-house PSG dataset used **only as an external test cohort**

Due to privacy and ethical constraints, raw PSG data are **not included** in this repository.

---

## Usage

1. Preprocess datasets following the pipeline described in the paper.
2. Train the model using `v5.ipynb`.
3. Run `Paper_ready_ablation.ipynb` to reproduce ablation experiments.
4. Use `Final_eval_all.ipynb` for test-set evaluation.
5. Perform subgroup, full-night, and interpretability analyses using the corresponding notebooks.

Each notebook is self-contained and includes inline documentation.

---

## Notes

- This repository is **under active development**.
- Experiments are ongoing, and results or implementation details may be updated in future commits.
- This repository is intended **solely for research and reproducibility purposes**.

---

## Citation

If you use this code in your research, please cite our paper.  
(Citation details will be added upon publication.)
