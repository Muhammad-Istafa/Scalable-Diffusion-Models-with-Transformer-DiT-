# Scalable Diffusion Models with Transformer (DiT)

This repository demonstrates image generation using a Diffusion Transformer (DiT) workflow in `run_DiT.ipynb`.

## Repository Contents

- `run_DiT.ipynb`: Main notebook with model loading, sampling, and diffusion visualization.
- `outputs/`: Sample generated images and a diffusion output video.

## How to Run

1. Open `run_DiT.ipynb` in Jupyter Notebook or Google Colab.
2. Install dependencies used in the notebook (`torch`, `diffusers`, `transformers`, `matplotlib`, etc.).
3. Run cells in order to:
   - Load the DiT model
   - Generate image samples
   - Visualize denoising/diffusion steps
   - Produce video frames/animation inside the notebook

## Output Images

### Output 1
![Output 1](outputs/output_1.png)

### Output 2
![Output 2](outputs/output_2.jpg)

### Output 3
![Output 3](outputs/output_3.png)

## Output Video

- [Download / Open generated video](outputs/output_video_1.mp4)

<video src="outputs/output_video_1.mp4" controls width="720">
  Your browser does not support the video tag.
</video>

## Notebook Compatibility Fix

- The notebook metadata was cleaned by removing `metadata.widgets` to avoid rendering errors such as:
  - `the 'state' key is missing from 'metadata.widgets'`