# Sketch Generation with Diffusion and SketchRNN

This project implements generative sketch models to synthesize human-like drawings using both:
- ✏️ Conditional Diffusion Models
- ✍️ SketchRNN (LSTM-based)

## Dataset

Uses [Quick, Draw!](https://github.com/googlecreativelab/quickdraw-dataset) vector drawings in NDJSON format for:
- Bus
- Cat
- Rabbit

## Structure

- `notebooks/`: Jupyter notebooks for training and sampling
- `data/`: Raw `.ndjson` files
- `subset/`: Train/test splits
- `models/`: Saved `.pt` weights
- `outputs/`: Generated sketches and GIFs

## Setup

```bash
pip install -r requirements.txt
