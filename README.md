# 🧾 PDF CV Generator – Google Colab Notebook

Generate beautiful PDF resumes with Python using custom fonts and ReportLab – all from Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Andrea-Graziano-Gitto/Pdf-CV-Generator-GoogleColab/blob/main/CVCreator.ipynb)

---

## 📁 Setup Instructions

To use this notebook, follow these steps:

### 1. 📂 Prepare Fonts in Google Drive

Create a folder at the following path in your Google Drive:

```
/MyDrive/fonts/
```

Inside it, upload your preferred font files in `.ttf` format and **rename them exactly like this** (for example, with Montserrat):

```
/MyDrive/fonts/
├── Montserrat-Regular.ttf
├── Montserrat-Bold.ttf
├── Montserrat-Italic.ttf
└── Montserrat-BoldItalic.ttf
```

If you're using another font (e.g., Roboto), rename accordingly:

```
Roboto-Regular.ttf, Roboto-Bold.ttf, etc.
```

---

### 2. ✍️ Set Font Name in Notebook

In the notebook, find this line:

```python
font_name = "Montserrat"
```

Replace `"Montserrat"` with your font name if using a different one (e.g., `"Roboto"`).

---

### 3. ▶️ Run Cells to Mount Drive and Load Fonts

After mounting Google Drive, the notebook will load your font files and prepare them for ReportLab.

---

## 🖼️ Add Images (Optional)

You can upload PNG or JPG images that will be inserted into your CV (e.g., profile picture or logo). The notebook provides interactive prompts for this.

---

## 🧠 Using an LLM to Generate the CV Automatically

At the end of the notebook, there's a special **code cell** that expects **formatted instructions** describing your resume content (in structured text or natural language).

💡 **Pro tip:** You can copy and paste that last cell into any LLM (like ChatGPT or Gemini), and ask the LLM to:

> "Please follow these instructions and output Python code that creates my resume PDF using the notebook above."

This lets the LLM generate your full resume from simple instructions.

---

## 📌 Features

- ✅ Works entirely in Google Colab – no installation needed
- 🎨 Supports custom fonts via Google Drive
- 🖋️ Handles rich formatting: bold, italic, hyperlinks
- 🖼️ Add and position images in your CV
- 🧠 Compatible with LLMs for smart CV generation

---

## 📎 Repository Link

🔗 [CVCreator.ipynb](https://github.com/Andrea-Graziano-Gitto/Pdf-CV-Generator-GoogleColab/blob/main/CVCreator.ipynb)

---

## 📄 License

This project is licensed under the MIT License.

---

Made by [Andrea Graziano Gitto](https://github.com/Andrea-Graziano-Gitto)
