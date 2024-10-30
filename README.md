# 🎨 ComfyUI Colab Notebook

A Google Colab notebook for running ComfyUI with pre-configured models, custom nodes, and easy setup.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xLegende/ComfyUI_Colab/blob/main/ComfyUI_Colab.ipynb)

## ✨ Features

- 🚀 Easy setup of ComfyUI environment
- 💾 Google Drive integration for persistent storage
- 🎮 Pre-configured with popular models:
  - SD XL Base & Refiner
  - Pony Diffusion XL
  - JuggernautXL
  - Anything XL
  - Flux Models
  - SD 3.5
- 🛠️ Essential custom nodes pre-installed:
  - ComfyUI Manager
  - Impact Pack
  - Efficiency Nodes
  - Ultimate SD Upscale
  - IPAdapter Plus
  - And many more!
- 🎯 ControlNet models for SDXL
- 🔌 IP-Adapter support
- 📦 Easy output management with zip functionality

## 🚀 Getting Started

1. Open the notebook in Google Colab
2. Create a copy: `File > Save a copy in Drive`
3. Ensure GPU runtime is selected: `Runtime > Change runtime type > GPU`
4. (Optional) Add your Civit AI API key for model downloads
5. Run the "ComfyUI Setup" cell
6. Run the "Start ComfyUI" cell
7. Click the provided `https://xxxxxxx.loca.lt` link to access ComfyUI

## ⚙️ Configuration Options

### Models
- SD 3.5 Large model
- Flux model
- SDXL 1.0
- JuggernautXL v8
- Pony Diffusion XL v6
- Anything XL
- SDXL Refiner
- Custom model support (via URL)

### Custom LoRA Support
- Add your own LoRA models via URL
- Supports both Civit AI and Hugging Face links

### ControlNet & IP-Adapter
- SDXL ControlNet models
- IP-Adapter models

### Storage Options
- Google Drive integration
- Local storage fallback

## 📦 Output Management

Use the "Zip Outputs" cell to:
- Automatically collect generated images via prefix
- Create timestamped ZIP archives
- Save directly to Google Drive

## 💾 Persistent Storage

The notebook supports two storage options:
1. **Google Drive**: Enable `use_google_drive` for persistent storage
2. **Local Storage**: Disable for temporary session storage

## 🔧 Advanced Options

- Custom ComfyUI arguments support
- Clear log options
- Custom model and LoRA URL support

## 📝 Notes

- Colab Pro is recommended for better performance
- Press F5 if ComfyUI Manager doesn't load properly in Localtunnel
- Keep your Civit AI API key handy for model downloads
- Some models require significant storage space

## 📅 Changelog

| Date | Changes |
|------|---------|
| 30/10/24 | Added output zipping |
| 28/10/24 | Added custom LoRA and Checkpoint download |
| 26/10/24 | Added Civitai API Key |
| 25/10/24 | Created Notebook |

## 📜 License

This project is distributed under the Apache License 2.0. See `LICENSE` file for more information.
