# Pineapple Training

Short, practical Jupyter notebook workspace for training, experimentation, and reproducible analysis.

This workspace contains the notebook `pineapple_training.ipynb`.

## Contents

- `pineapple_training.ipynb`: Main notebook for training and experimentation.

## Prerequisites

- VS Code with the Jupyter extension installed
- Python 3.10+ recommended
- A working Python environment (venv, conda, or system Python)

## Setup

1. Open this folder in VS Code.
2. Create and activate a Python environment.
3. Install notebook dependencies:

```powershell
pip install jupyter numpy pandas matplotlib roboflow
```

4. Open the notebook and choose the correct kernel from your environment.

## Getting Started

1. Open the notebook in VS Code.
2. Select a Python kernel.
3. Run the cells in order.

## Recommended Workflow

1. Run all import and setup cells first.
2. Download/load your dataset (Roboflow example is included in the notebook).
3. Run training or analysis cells.
4. Save outputs and notes directly in the notebook.

## Model Options

- Current example uses `version.download("yolov5")` in the notebook.
- You can adapt the workflow to other model ecosystems such as TensorFlow, Keras, or PyTorch.
- Keep preprocessing and label format consistent with your chosen model pipeline.

## Troubleshooting

- Kernel not found: Ensure your environment is selected in VS Code.
- Import errors: Install missing packages in the active environment.
- Cells run out of order: Restart the kernel and run all cells from top to bottom.

## Notes

- Keep experiments reproducible by setting random seeds where applicable.
- If this project grows, consider adding a `requirements.txt` file for dependency tracking.
- Replace placeholder values such as `YOUR_API_KEY` and project name before running the dataset download cell.
