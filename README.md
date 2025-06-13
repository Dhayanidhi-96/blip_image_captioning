
# 🖼️ BLIP Image Captioning Web App

A simple image captioning project using the **Salesforce BLIP model** and a web interface built with **Gradio**. Upload any image and get an AI-generated caption in seconds.

---

## 🚀 Features

- 📌 Image Captioning using BLIP model  
- 🌐 Web interface using Gradio  
- 🧠 Pretrained transformer model from HuggingFace  
- ⚡ Fast and easy to run locally  

---

## 📂 Folder Structure

```
image_caption/
│
├── blip.py             # CLI test version of image captioning
├── app.py              # Gradio web interface
├── requirements.txt    # All dependencies
├── README.md           # Project documentation
└── venv/               # Python virtual environment (not uploaded to GitHub)
```

---

## ▶️ Run Locally

> ✅ Make sure you have **Python 3.9+** and `venv` activated

```bash
# 1. Clone the repo
git clone https://github.com/Dhayanidhi-96/blip_image_captioning.git
cd blip_image_captioning

# 2. Create virtual environment and activate
python -m venv venv

# For Windows:
venv\Scripts\activate

# For Mac/Linux:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py
```

---

## 🛠️ Tech Stack

- Python 🐍  
- Transformers 🤗  
- BLIP Model by Salesforce 📷  
- Gradio UI 🌐  
- Pillow 🖼️  

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Salesforce BLIP model](https://huggingface.co/Salesforce/blip-image-captioning-base)  
- [Gradio](https://www.gradio.app/)  
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/index)
