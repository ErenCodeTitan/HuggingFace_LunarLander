# HuggingFace_RL (Lunar Lander)

A reinforcement learning project built while working through Hugging Face's Deep RL Course, training an agent to solve the classic **Lunar Lander** environment from Gymnasium.

## Overview

This repo contains notebooks that train and evaluate an RL agent (via Stable-Baselines3 / Hugging Face's `huggingface_sb3` tooling) to safely land a lunar module in the `LunarLander-v2` environment, then push the trained model to the Hugging Face Hub.

## Contents

- `Copy of unit2.ipynb` — Main training notebook.
- `notebooks/` — Supporting notebooks.

## Getting Started

### Prerequisites

```bash
pip install stable-baselines3[extra] gymnasium huggingface_sb3 huggingface_hub
```

### Running

1. Clone the repository:
   ```bash
   git clone https://github.com/ErenCodeTitan/HuggingFace_RL.git
   cd HuggingFace_RL
   ```
2. Open `Copy of unit2.ipynb` in Jupyter or Google Colab.
3. Run the cells to train the agent on `LunarLander-v2` and evaluate its performance.

## Notes

- If pushing the trained model to the Hugging Face Hub, you'll need a Hugging Face account and an access token (`huggingface-cli login`).

## Author

**Hariharan M S** ([ErenCodeTitan](https://github.com/ErenCodeTitan))
