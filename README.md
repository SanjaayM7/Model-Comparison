# AI Image Generation Model Comparison

## Overview

This repository compares the performance of two different **Stable Diffusion** models:

- **Runway Stable Diffusion v1.5**
- **Dreamlike Photoreal 2.0**

The comparison evaluates image quality, realism, and computational efficiency using **FID (Frechet Inception Distance)** scores and visual analysis.

## Installation

Follow the steps to set up the environment and run model comparison.

### Prerequisites

- **Google Colab** or a local setup with GPU
- **Hugging Face Account** (if required for access to models)

### Setup in Google Colab

1. **Open Google Colab** and create a new notebook.
2. **Install dependencies**:

    ```bash
    !pip install diffusers transformers accelerate torch torchvision pillow torch_fidelity
    ```

3. **Clone the repository**:

    ```bash
    !git clone https://github.com/your-username/Stable-Diffusion-Model-Comparison.git
    ```

4. **Run the script to generate and compare models**:

    ```python
    !python model_comparison.py
    ```

## License

This repository is for educational purposes. Models used are hosted on **Hugging Face** and abide by their licenses.

