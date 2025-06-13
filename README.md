# 🎨 Guided Generation & Control in Pretrained Diffusion Models

This repository contains a project that demonstrates the use of **pretrained Stable Diffusion models** for **text-to-image generation**, **prompt control**, **inpainting**, and **style transfer** using the HuggingFace `diffusers` library.



## 🚀 Objectives

- Generate images from text using Stable Diffusion
- Explore **classifier-free guidance scale** effects
- Perform **inpainting** on masked images
- Use **ControlNet** and **Canny edges** to guide generation
- Apply **Style Transfer** using reference images

---

🖼️ Key Features & Sections
1. Text-to-Image Generation
Uses StableDiffusionPipeline to generate images based on simple text prompts.

2. Guidance Scale Experimentation
Varying the guidance_scale (5.0, 7.5, 10.0, etc.) to observe how it impacts image fidelity and prompt adherence.

3. Inpainting
Using StableDiffusionInpaintPipeline to modify specific regions in an image based on a text prompt and a mask.

4. ControlNet with Canny Edges
Guiding the generation with ControlNet + Canny edge detection for structure-aware synthesis.

5. Style Transfer
Conditioning generation using both a text prompt and a reference style image, leveraging multi-modal inputs.

📂 Output Samples
Each section in the notebook produces visual outputs. Example results include:

Text-guided generated images

Same prompt with varying guidance scales

Inpainted images using masks

ControlNet results conditioned on edge maps

Style transfer outputs blending text intent and image style

▶️ How to Use
Clone the repository or download the notebook:

bash
Copy
Edit
git clone https://github.com/yourusername/diffusion-guided-generation.git
Open the notebook in Jupyter or Colab:

Colab recommended (for GPU)

Run all cells sequentially to install dependencies, load models, and generate images.


## 📦 Libraries & Setup

The following libraries are used in this notebook:

- `diffusers`
- `transformers`
- `accelerate`
- `safetensors`
- `xformers`
- `controlnet_aux`

Install with:

```bash
pip install --upgrade diffusers transformers accelerate safetensors xformers controlnet_aux


