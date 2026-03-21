# 🚀 Streamlit PyTorch App

A Streamlit web application powered by PyTorch for deep learning inference with support for vision and audio tasks.

## 📋 Requirements

- Python 3.9+
- pip

## 📦 Dependencies

| Package | Version |
|---|---|
| streamlit | 1.51.0 |
| torch (CPU) | 2.10.0 |
| torchaudio (CPU) | 2.10.0 |
| torchvision (CPU) | 0.25.0 |
| pillow | 12.0.0 |

> **Note:** This app uses CPU-only builds of PyTorch. If you have a CUDA-compatible GPU, you can swap the `+cpu` variants for GPU-accelerated versions from [pytorch.org](https://pytorch.org/get-started/locally/).

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create and activate a virtual environment** *(recommended)*

   ```bash
   python -m venv venv

   # macOS / Linux
   source venv/bin/activate

   # Windows
   venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Running the App

```bash
streamlit run app.py
```

The app will open automatically in your browser at `http://localhost:8501`.

## 🗂️ Project Structure

```
your-repo-name/
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## 🛠️ Tech Stack

- **[Streamlit](https://streamlit.io/)** — Interactive web UI framework for ML apps
- **[PyTorch](https://pytorch.org/)** — Deep learning framework for model inference
- **[TorchVision](https://pytorch.org/vision/)** — Computer vision utilities and pretrained models
- **[TorchAudio](https://pytorch.org/audio/)** — Audio processing utilities and pretrained models
- **[Pillow](https://python-pillow.org/)** — Image loading and preprocessing

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
