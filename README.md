# generative-ai-image-generator
Generative AI Image Generation Project using Python and AI models.
# Generative Image Application Using Stable Diffusion

## Project Overview

This project is a Generative AI application that creates images from text prompts using the Stable Diffusion 1.5 model.

The application allows users to enter a text description and generate AI-powered images through an interactive Streamlit web interface.

## Features

- Text-to-image generation using Stable Diffusion
- User-friendly Streamlit interface
- Adjustable inference steps
- Adjustable guidance scale
- Custom image width and height
- Seed selection for reproducible image generation
- GPU-based image generation using PyTorch

## Technologies Used

- Python
- PyTorch
- Stable Diffusion 1.5
- Hugging Face Diffusers
- Transformers
- Accelerate
- Safetensors
- Streamlit

## Project Structure

Generative-Image-App/

- app.py
- README.md
- requirements.txt

## Installation

Clone the repository and navigate to the project folder.

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment.

For Windows:

```bash
.venv\Scripts\activate
```

Install the required libraries:

```bash
pip install torch diffusers transformers accelerate safetensors streamlit
```

Make sure PyTorch is installed with CUDA support if you want to use GPU acceleration.

## How to Run

Run the following command in the project directory:

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal, usually:

http://localhost:8501

## How to Use

1. Enter a text prompt describing the image you want to generate.
2. Select the number of inference steps.
3. Adjust the guidance scale.
4. Choose the image width and height.
5. Set a seed for reproducible results.
6. Click the Generate Image button.
7. View the generated image.

## Model Information

Model: Stable Diffusion 1.5

Model ID: runwayml/stable-diffusion-v1-5

The application uses the StableDiffusionPipeline from Hugging Face Diffusers to generate images from text prompts.

## Future Improvements

- Add negative prompt support.
- Add image download functionality.
- Add image generation history.
- Improve error handling.
- Add image-to-image generation.
- Support automatic CPU and GPU selection.

## Author

Kavya Kannan

AI/ML | Generative AI | Data Analytics
