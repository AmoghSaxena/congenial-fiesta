# WGAN vs VAE Image Generation Comparison

This project compares Wasserstein Generative Adversarial Networks (WGAN) and Variational Autoencoders (VAE) for image generation using the CIFAR-10 dataset.

## Project Overview

The main objectives of this project are:
1. Implement WGAN and VAE models for image generation
2. Train both models on the CIFAR-10 dataset
3. Compare the performance of WGAN and VAE using the MiFID metric
4. Visualize and analyze the generated images

## Requirements

To run this project, you need:

- Python 3.7+
- PyTorch
- torchvision
- numpy
- matplotlib
- pytorch-fid

You can install the required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Project Structure

- `wgan_vae_comparison.ipynb`: Jupyter notebook containing the main code for the project
- `README.md`: This file, providing an overview of the project
- `requirements.txt`: List of required Python packages
- `LICENSE`: MIT License file

## Usage

1. Clone this repository:

```bash
git clone https://github.com/AmoghSaxena/congenial-fiesta.git
```


2. Install the required packages:

```bash
pip install -r requirements.txt
```


3. Open and run the `wgan_vae_comparison.ipynb` notebook using Jupyter Lab or Jupyter Notebook.

## Results

The project compares WGAN and VAE models based on:
- Generated image quality
- MiFID scores
- Training stability and convergence

Detailed results and analysis can be found in the notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.