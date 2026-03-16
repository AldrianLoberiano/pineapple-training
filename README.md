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
3. Install common notebook dependencies if needed:

```powershell
pip install jupyter numpy pandas matplotlib
```

4. Open the notebook and choose the correct kernel from your environment.

## Getting Started

1. Open the notebook in VS Code.
2. Select a Python kernel.
3. Run the cells in order.

## Recommended Workflow

1. Run all import and setup cells first.
2. Execute data loading and preprocessing cells.
3. Run training or analysis cells.
4. Save outputs and notes directly in the notebook.

## Troubleshooting

- Kernel not found: Ensure your environment is selected in VS Code.
- Import errors: Install missing packages in the active environment.
- Cells run out of order: Restart the kernel and run all cells from top to bottom.

## Notes

- Keep experiments reproducible by setting random seeds where applicable.
- If this project grows, consider adding a `requirements.txt` file for dependency tracking.
