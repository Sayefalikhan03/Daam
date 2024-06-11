# DAAM Project

This repository contains code for generating images with Stable Diffusion using the `diffusers` library, and tracing through the generation process with the `daam` library.

## Setup and Installation

### Google Colab

To run this project on Google Colab, follow these steps:

1. **Open Google Colab:**
   - Go to [Google Colab](https://colab.research.google.com).

2. **Create a New Notebook:**
   - Click on `File` -> `New Notebook`.

3. **Clone the Repository and Set Up the Environment:**

   In the first cell, run the following code to clone the repository and install the dependencies:

   ```python
   # Step 1: Clone the Repository
   !git clone https://github.com/your-username/daam-project.git
   %cd daam-project

   # Step 2: Install Required Packages
   !pip install torch torchvision ftfy matplotlib
   !pip install diffusers==0.16.1 transformers==4.27.4 accelerate==0.18.0 jax jaxlib huggingface_hub

colab notebook link: https://colab.research.google.com/drive/1aLt2EAWQZmyKUd3L3esHFRnXXLxYbHSz?usp=sharing
