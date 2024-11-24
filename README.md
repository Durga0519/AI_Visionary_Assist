# 👓 Visionary AI: Navigating the World Through AI Vision
Visionary AI is a Streamlit-based application that leverages cutting-edge AI technologies to assist visually impaired users in interacting with and understanding the visual world. With features like scene description, text extraction, and text-to-speech conversion, this tool makes it easier to navigate and understand visual content.

# 🌟 Features
# 📜 Describe Image
Generate detailed descriptions of uploaded images to provide insight into their content. Perfect for visually impaired users to understand their surroundings.

# 📝 Extract Text
Extract textual information from images using OCR technology. Ideal for reading documents, signs, or other text-based content.

# 🔊 Play & Download Speech
Convert extracted text into speech using gTTS. Users can listen to or download audio files for convenient access.

# 🚀 How It Works
Upload an Image
Upload any image (e.g., .jpg, .jpeg, .png) to process across all features.

Select a Feature
Choose from one of the three core functionalities:

Scene Description: Get AI-generated descriptions of the image.
Text Extraction: Extract any visible text in the image.
Text-to-Speech: Convert the extracted text into an audio format.
Get Results
View the generated output or listen to/download the audio file.

# 🛠️ Technologies Used
Streamlit: For building the interactive user interface.
Google Generative AI (Gemini): For generating detailed scene descriptions.
Pytesseract: For optical character recognition (OCR).
gTTS: For text-to-speech conversion.
Python: The core programming language used for development.

# 🖥️ Setup and Installation
Prerequisites
Python 3.8 or higher installed on your system.
Tesseract OCR installed. Follow the Tesseract installation guide.
A valid Google Generative AI API Key. Add it to a .env file in the root directory of the project.

Ah, I see! You want **separate code blocks** for specific commands and only **highlight** relevant headings. Here's how you can format it in Markdown:

```markdown
# Installation Steps

### Clone the repository:
```bash
git clone https://github.com/your-username/visionary-ai.git
cd visionary-ai
```

---

### Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

---

### Install the required dependencies:
```bash
pip install -r requirements.txt
```

---

### Add your API key to a `.env` file:
```plaintext
GOOGLE_GENERATIVE_AI_API_KEY=your_api_key_here
```

---

### Run the application:
```bash
streamlit run app.py
```

Access the app in your browser at [http://localhost:8501](http://localhost:8501).

---

## 📸 Screenshots

---

## 🎥 Cinematic Intro
The app starts with a Netflix-style animated title for a sleek, professional look.

---

# 🖼️ Unified Image Upload
Upload an image once and use it across all features seamlessly.

---

# 🎯 Intuitive Feature Selection
Easily switch between scene description, text extraction, and text-to-speech conversion using feature-specific buttons.

---

# 📝 Usage Scenarios

- **Visually Impaired Users**: Get a detailed understanding of your surroundings through AI-generated image descriptions.
- **Text Extraction**: Extract critical information from images, documents, or signs.
- **Speech Playback**: Listen to extracted text for improved accessibility and convenience.

---

# 🤝 Contributions
Contributions, issues, and feature requests are welcome!

Feel free to open an issue or submit a pull request to improve the app.

---

# 🌟 Acknowledgements
Special thanks to:

- **Google Generative AI** for scene description capabilities.
- **Tesseract OCR** for text recognition.
- **gTTS** for enabling seamless text-to-speech conversion.

---
