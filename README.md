# HierSleepTransformer

**HierSleepTransformer: A Hierarchical Single-Channel Transformer with Rotary Position Embeddings for Interpretable and Generalizable Sleep Stage Classification**

**Authors:**  
Zubair Akbar · Ubaidullah Alias Kashif · Jingzhen Li · Yuhang Liu · Zedong Nie

---

## Overview

This repository contains the experimental code, evaluation pipelines, and analysis notebooks used in our study on **automatic sleep stage classification from single-channel EEG** (30-second epochs).  
HierSleepTransformer is a hierarchical transformer architecture with **rotary position embeddings (RoPE)**, designed for strong performance, interpretability, and cross-dataset generalization.

---

## Repository Structure
## Repository Structure

- **v5.ipynb**  
  Main training and model development notebook.

- **Paper_ready_ablation.ipynb**  
  Ablation studies reported in the paper.

- **Final_eval_all.ipynb**  
  Final evaluation and metric computation on test sets.

- **Sub_Group_Analysis.ipynb**  
  Subgroup-based performance analysis.

- **paper_interpretability.ipynb**  
  Model interpretability and qualitative analyses.

- **data_states.ipynb**  
  Dataset statistics and sleep stage distribution analysis.

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
3. Run `Paper_ready_ablation.ipynb` for ablation experiments.
4. Use `Final_eval_all.ipynb` for test-set evaluation.
5. Perform subgroup and interpretability analyses using the corresponding notebooks.

Each notebook is self-contained and includes inline documentation.

---

## Notes

- This repository is **under active development**.
- Experiments are ongoing, and results or implementation details may be updated in future commits.
- This repository is intended for **research and reproducibility purposes only**.

---

## Citation

If you use this code in your research, please cite our paper.  
(Citation details will be added upon publication.)
