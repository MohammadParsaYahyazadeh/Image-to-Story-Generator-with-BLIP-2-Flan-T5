# 🖼️→✍️ Image-to-Story Generator with BLIP-2 + Flan-T5

Generate creative, styled stories from one or more images using [BLIP-2](https://huggingface.co/Salesforce/blip2-flan-t5-xl) and Flan-T5 XL. This project supports batch processing, customizable story prompts, and a Streamlit web app!

🔗 [Try on Colab](https://colab.research.google.com/github/MohammadParsaYahyazadeh/Image-to-Story-Generator-with-BLIP-2-Flan-T5/blob/main/Image_to_Story_BLIP2_Advanced.ipynb)

---

## ✨ Features

- 📜 Story generation from images using zero-shot vision-language models
- 🎭 Custom prompt styles: `fantasy`, `horror`, `romance`, `sci-fi`, `default`
- 🖼️ Batch mode for multiple images
- 🌐 Streamlit app interface
- 💻 Google Colab notebook version

---

## 🧠 Model Used

- **BLIP-2 (BLIP-2-FlanT5-XL)** by Salesforce
- Combines image understanding with language generation
- No fine-tuning required for basic functionality

---

## 🔧 Installation

### 💡 Option 1: Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammadParsaYahyazadeh/Image-to-Story-Generator-with-BLIP-2-Flan-T5/blob/main/Image_to_Story_BLIP2_Advanced.ipynb)

### 💡 Option 2: Local + Streamlit

```bash
git clone https://github.com/MohammadParsaYahyazadeh/Image-to-Story-Generator-with-BLIP-2-Flan-T5.git
cd Image-to-Story-Generator-with-BLIP-2-Flan-T5

# Create virtual env (optional)
python -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run image_to_story_app.py


📦 Image-to-Story-Generator/
├── Image_to_Story_BLIP2_Advanced.ipynb  # Colab notebook
├── image_to_story_app.py                # Streamlit web app
├── README.md
├── requirements.txt


| Style   | Image                                                                   | Output                                                                                                 |
| ------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Fantasy | ![](https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d?w=300) | *The castle shimmered under a moonlit spell, as the enchanted knight returned to claim his destiny...* |


🛠 Prompt Styles
style_prompts = {
    "fantasy": "Write a magical fantasy story about this image.",
    "horror": "Write a short horror story based on this image.",
    "romance": "Write a romantic story based on this image.",
    "sci-fi": "Write a science fiction story about this image.",
    "default": "Write an imaginative story about this image."
}

✅ To Do
 Add Hugging Face Spaces deployment

 Upload webcam/photo capture support

 Optional story length and tone settings

 Persian language support 🇮🇷

👤 Author
Mohammad Parsa Yahyazadeh
🔗 GitHub: @MohammadParsaYahyazadeh

📜 License
MIT License — free to use and modify.
