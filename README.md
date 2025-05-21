<p align="center">
    <img src="https://img.shields.io/badge/python-3.8%2B-blue" alt="Python Version">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

<h1 align="center">Text Summarizer AI</h1>

<p align="center">
    <em>Effortlessly generate concise summaries from long texts using state-of-the-art AI models.</em>
</p>

---

## 🚀 Features

- **Automatic Text Summarization**: Generate short, meaningful summaries from any input text.
- **Easy to Use**: Simple interface for quick summarization.
- **Customizable**: Adjust summary length and style.
- **Modern NLP Models**: Powered by advanced transformer-based models.

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/Text_Summarizer_AI.git
cd Text_Summarizer_AI
pip install -r requirements.txt
```

## 💡 Usage

```python
from summarizer import summarize

text = "Your long article or document goes here..."
summary = summarize(text)
print(summary)
```

Or use the provided CLI:

```bash
python summarize.py --input input.txt --output summary.txt
```

## 📦 Requirements

- Python 3.8+
- Transformers
- Torch
- Other dependencies in `requirements.txt`

## 🤖 Model Details

This project uses pre-trained transformer models (e.g., BART, T5) for extractive and abstractive summarization.

## 📄 License

This project is licensed under the MIT License.

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

<p align="center">
    <b>Made with ❤️ for the AZ Hackathon</b>
</p>
