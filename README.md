# GPT-2 Text Generation Playground 🧠✍️

This project is a simple and interactive playground to experiment with GPT-2 using Hugging Face's 🤗 `transformers` library.

## 📂 Project Structure

- `transformers.ipynb`: Jupyter Notebook with different GPT-2 text generation experiments.
- `requirements.txt`: Contains the list of Python dependencies.
- `venv/`: Your virtual environment folder (excluded from Git using `.gitignore`).
- `Exploring GPT-2 for Text Generation using Transformers.pdf`: Project report explaining the concepts and results.

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/gpt2-playground.git
cd gpt2-playground
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the notebook**

Open `transformers.ipynb` in Jupyter Notebook or VSCode and try out the different prompt-based experiments!

## ✨ Features

- Generate creative completions from prompts using GPT-2.
- Explore multiple generation techniques:
  - News headlines
  - Storytelling
  - Dialogues
  - Open-ended questions
  - Multiple outputs per prompt

## 📌 Dependencies

- `transformers`
- `torch` or compatible backend
- `notebook` (if using Jupyter)

## 🛑 .gitignore

Your `.gitignore` file should include:

```
venv/
__pycache__/
.ipynb_checkpoints/
*.pyc
```

This prevents pushing virtual environments and cache files to GitHub.

## 🤖 Powered by

- Hugging Face Transformers
- GPT-2 Language Model

---

Feel free to fork and extend this notebook with more experiments!
