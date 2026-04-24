# Scalable Diffusion Models with Transformer (DiT)

This repository demonstrates image generation using a Diffusion Transformer (DiT) workflow in `run_DiT.ipynb`.

## Repository Contents

- `run_DiT.ipynb`: Main notebook with model loading, sampling, and diffusion visualization.

## How to Run

1. Open `run_DiT.ipynb` in Jupyter Notebook or Google Colab.
2. Install dependencies used in the notebook (`torch`, `diffusers`, `transformers`, `matplotlib`, etc.).
3. Run cells in order to:
   - Load the DiT model
   - Generate image samples
   - Visualize denoising/diffusion steps
   - Produce video frames/animation inside the notebook

## Outputs

- Output images and videos are generated dynamically when you run the notebook.
- Media files are not stored in this repository by default.

## Notebook Compatibility Fix

- The notebook metadata was cleaned by removing `metadata.widgets` to avoid rendering errors such as:
  - `the 'state' key is missing from 'metadata.widgets'`