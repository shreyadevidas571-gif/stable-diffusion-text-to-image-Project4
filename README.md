# Stable Diffusion Text-to-Image Generator

A simple AI-powered text-to-image generation project built with **Stable Diffusion**, **Hugging Face Diffusers**, and **PyTorch**. The application generates high-quality images from natural language prompts using the Stable Diffusion v1.5 model.

---

## 🚀 Features

- 🎨 Generate images from text prompts
- 🤖 Uses Stable Diffusion v1.5
- ⚡ GPU acceleration with CUDA
- 🖼️ Display generated images using Matplotlib
- 🧩 Built with Hugging Face Diffusers

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Diffusers
- Stable Diffusion v1.5
- Matplotlib

---

## 📂 Project Structure

```
stable-diffusion-text-to-image/
│── app.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/stable-diffusion-text-to-image.git
```

Navigate to the project directory:

```bash
cd stable-diffusion-text-to-image
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

The model will load and generate an image based on the prompt.

---

## 🧠 How It Works

1. Load the Stable Diffusion v1.5 model.
2. Move the model to the GPU using CUDA.
3. Accept a text prompt.
4. Generate an image using the diffusion model.
5. Display the generated image with Matplotlib.

---

## 🏗️ Workflow

```
          Text Prompt
               │
               ▼
     Stable Diffusion Pipeline
               │
               ▼
      Latent Image Generation
               │
               ▼
      Image Decoding (VAE)
               │
               ▼
       Generated AI Image
               │
               ▼
       Matplotlib Display
```

---

## 📦 Requirements

- Python 3.10+
- CUDA-enabled GPU (recommended)
- PyTorch
- Diffusers
- Transformers
- Accelerate
- Matplotlib

Install dependencies:

```bash
pip install torch diffusers transformers accelerate matplotlib
```

---

## 📚 Learning Outcomes

This project demonstrates:

- Text-to-Image Generation
- Diffusion Models
- Stable Diffusion
- Generative AI
- Hugging Face Diffusers
- PyTorch
- GPU Acceleration with CUDA
- Prompt Engineering
- AI Image Synthesis

---

## 🔮 Future Improvements

- Build a Gradio or Streamlit web interface
- Support negative prompts
- Adjustable image size
- Control inference steps
- Random seed selection
- Save generated images automatically
- Support SDXL and newer diffusion models

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

B.Shreya
