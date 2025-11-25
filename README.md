# Kidney-Stone Risk Prediction (Tabular ML)

**Goal.** Train and evaluate supervised models to predict `kidney stones` from urine-test features, then generate predictions for new samples.

## Results (held-out test set)
- Precision: 94%
- Recall: 93%
- F1: 93%
- ROC-AUC: 99%
- Confusion matrix: (see notebook)

## Repository Structure
- `notebooks/` – primary analysis (`Kidney_stones_prediction.ipynb`)
- `data/` – datasets used
- `outputs/` – generated files (e.g., `predictions.csv`)
- `requirements.txt` – minimal, pinned deps

## How to Reproduce
1. `python -m venv .venv && source .venv/bin/activate` (Windows: `.venv\Scripts\activate`)
2. `pip install -r requirements.txt`
3. Place the two CSVs in root folder as (or: edit the paths in part 2.1):
   - `urine_specimens.csv`
   - `new_urine_specimens.csv`
4. Open `notebooks/Kidney_stones_prediction.ipynb`
5. **Restart Kernel & Run All**.  
   Outputs (e.g., `predictions.csv`) will appear in root folder`.


**Intended use:** educational demonstration.

## License
Code released under the MIT License (see `LICENSE`).
