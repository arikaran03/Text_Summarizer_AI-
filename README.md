# 🤖 AI Text Summarizer 📝

[![GitHub repo size](https://img.shields.io/github/repo-size/arikaran03/Text_Summarizer_AI-?style=for-the-badge)](https://github.com/arikaran03/Text_Summarizer_AI-)
[![Languages](https://img.shields.io/github/languages/count/arikaran03/Text_Summarizer_AI-?style=for-the-badge)](https://github.com/arikaran03/Text_Summarizer_AI-)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](LICENSE) Transform long texts into clear and concise summaries with the power of AI! This web application leverages the Google Gemini API to provide summaries of three different lengths: short, medium, and detailed.

## ✨ Features

* **🤖 AI-Powered Summarization:** Utilizes the Google Gemini API for intelligent text summarization.
* **🔑 API Key Management:** Securely save your Gemini API key in local storage for convenient use.
* **📏 Multiple Summary Lengths:**
    * ⚡ **Short Summary:** Get the key points in just a few sentences.
    * 📄 **Medium Summary:** A balanced overview of the text.
    * 🗂️ **Detailed Summary:** An in-depth analysis of the content.
* **📋 Easy Text Input:** Paste your text directly into the application.
* **💅 Sleek User Interface:** A clean, modern, and responsive design.
* **🔄 Loading Indicator:** Visual feedback while the summary is being generated.
* **🚀 Smooth Scrolling:** Enhanced user experience with smooth transitions.

## 🛠️ Technologies Used

* **Frontend:**
    * HTML5
    * CSS3
    * JavaScript (ES6 Modules)
* **AI Model:**
    * Google Generative AI SDK (`@google/generative-ai`)
    * Gemini 2.0 Flash Model
* **Styling:**
    * Custom CSS with Flexbox for layout.
    * Gradient backgrounds and modern design elements.

## 🚀 How to Use

1.  **Clone the Repository (Optional - if running locally):**
    ```bash
    git clone [https://github.com/arikaran03/Text_Summarizer_AI-.git](https://github.com/arikaran03/Text_Summarizer_AI-.git)
    cd Text_Summarizer_AI-
    ```
2.  **Open `index.html`:**
    * If you've cloned the repository, open the `index.html` file in your web browser.
    * Alternatively, you can directly access it if deployed (e.g., via GitHub Pages - link to your deployed version if available).

3.  **Enter Your Gemini API Key:**
    * Scroll down to the "Enter Your Gemini API Key" section.
    * Input your valid Google Gemini API key into the text field.
    * Click the "Save API Key" button. The key will be stored in your browser's local storage for future sessions.
    * *You can obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).*

4.  **Summarize Your Text:**
    * Scroll or click the "Try Now" button to navigate to the "Text Summarizer" section.
    * Paste the text you want to summarize into the text area.
    * Choose your desired summary length by clicking one of the buttons:
        * "⚡ Short Summary"
        * "📄 Medium Summary"
        * "🗂️ Detailed Summary"

5.  **View Your Summary:**
    * A loading indicator will appear while the AI generates the summary.
    * Once complete, the summarized text will be displayed in the "🔍 Summary:" section below.
