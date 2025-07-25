# ComfyUI on Google Colab (Free Tier)

This repository provides a Google Colab notebook to run [ComfyUI](https://github.com/comfyanonymous/ComfyUI) on the **free Google Colab tier** (under 15 GB VRAM).  
The primary focus is to run **Flux models** efficiently within the Colab free tier limits.

---

## **Key Features**
- Runs **ComfyUI** seamlessly on Colab's free tier (Tesla T4 GPU).
- Pre-configured for **Flux models** (recommended [FP8 version](https://comfyanonymous.github.io/ComfyUI_examples/flux/)).
- Supports **LoRAs** by using smaller, quantized models.
- Tested with **Q5** and **Q4 GGUF** quantized models from [ComfyUI-GGUF](https://github.com/city96/ComfyUI-GGUF).
- Works well with LoRAs and various pipelines.
- Access to additional quantized Flux models on [Hugging Face](https://huggingface.co/city96/FLUX.1-dev-gguf).

---

## **Models**
### **FP8 Model**
- The FP8 version of Flux works **without LoRA** on free Colab.
- It’s recommended as the default model due to its balance of quality and performance.

### **Quantized Models (for LoRA support)**
- Q5 and Q4 GGUF versions are tested and work well with LoRAs.
- More quantized models can be found at:  
  [https://huggingface.co/city96/FLUX.1-dev-gguf](https://huggingface.co/city96/FLUX.1-dev-gguf)

---

## **Requirements**
- **Google Colab (Free Tier)** with GPU runtime (Tesla T4 or similar).
- ~15 GB of VRAM (default free tier is sufficient).
- Internet access to download model files (automated in the notebook).

---

## **Usage**
1. Open the Colab notebook from this repository.
2. Run all cells to install dependencies and launch ComfyUI.
3. The notebook will start **ComfyUI** on a public URL using **LocalTunnel**.
4. Load your desired model (FP8, Q5, or Q4) and start generating images.

---

## **Links & References**
- **ComfyUI:** [https://github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)  
- **Flux Model Guide:** [https://comfyanonymous.github.io/ComfyUI_examples/flux/](https://comfyanonymous.github.io/ComfyUI_examples/flux/)  
- **ComfyUI-GGUF:** [https://github.com/city96/ComfyUI-GGUF](https://github.com/city96/ComfyUI-GGUF)  
- **Quantized Flux Models:** [https://huggingface.co/city96/FLUX.1-dev-gguf](https://huggingface.co/city96/FLUX.1-dev-gguf)  

---

## **License**
This project follows the license of [ComfyUI](https://github.com/comfyanonymous/ComfyUI) and related model repositories.

---
