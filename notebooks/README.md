# Companion Notebooks

Interactive Jupyter notebooks for hands-on practice with the concepts in each chapter.

## Quick Start

Click the "Open in Colab" badge in any notebook to run it immediately in Google Colab (no setup required).

## Available Notebooks

| Notebook | Topics |
|----------|--------|
| [first-analysis.ipynb](first-analysis.ipynb) | Your first interpretability analysis: sentiment attribution, attention patterns |
| [exercises.ipynb](exercises.ipynb) | Practice exercises for all techniques |
| [02-transformers.ipynb](02-transformers.ipynb) | Forward pass, attention visualization, residual stream |
| [09-sparse-autoencoders.ipynb](09-sparse-autoencoders.ipynb) | Feature extraction, exploration, steering |
| [13-induction-heads.ipynb](13-induction-heads.ipynb) | Finding induction heads, ablation, two-layer circuit |

## Running Locally

If you prefer to run locally:

```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows

# Install dependencies
pip install transformer-lens sae-lens circuitsvis einops jaxtyping

# Start Jupyter
jupyter notebook
```

## GPU Recommendation

These notebooks work on CPU but run much faster with GPU. In Colab:
1. Runtime -> Change runtime type -> GPU

## Library Versions

Notebooks are tested with:
- transformer-lens >= 1.0.0
- sae-lens >= 0.1.0
- torch >= 2.0.0

## Contributing

Found an issue? Please open a GitHub issue or PR!
