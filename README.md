# Remote Model Experiments for UAV and Satellite Data

This folder contains the cleaned and GitHub-ready notebooks for model optimization, ablation studies, and interpretation on UAV and satellite remote sensing data.

## Contents

- `1.1.UAV model optimization.ipynb`
- `1.2.U2L8 model optimization.ipynb`
- `1.3.U2S2 model optimization.ipynb`
- `1.4.L8 model optimization.ipynb`
- `1.5.S2 model optimization.ipynb`
- `2.1.UAV ablation.ipynb`
- `2.2.UAVtol8 ablation.ipynb`
- `2.3.UAVtoS2 ablation.ipynb`
- `3.1.Model interpretation.ipynb`
- `3.2.SHAP for RF(baseline).ipynb`
- `4.attempt.ipynb`

## Data

- `data/` contains CSV datasets and supporting input files.
- `data/input/` contains the main CSV inputs used by the notebooks.
- `SRF/` contains spectral response function resources.

## Dependencies

Install the required Python packages before running the notebooks:

```bash
pip install -r requirements.txt
```

The current `requirements.txt` includes:

- `numpy`
- `pandas`
- `scikit-learn`
- `torch`
- `xgboost`
- `tabpfn`
- `joblib`

## Usage

1. Open a notebook in `to_github/`.
2. Confirm that the `ROOT_DIR` or data paths point to this repository root.
3. Run the notebook cells in order.

## Notes

- The notebooks are organized by task: model selection (`1.*`), ablation studies (`2.*`), and explanation/interpretation (`3.*`).
- The `4.attempt.ipynb` file contains additional experimental code.
- The notebooks are intended for demonstration and reproducibility on the provided dataset.
