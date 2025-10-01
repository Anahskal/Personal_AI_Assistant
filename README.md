# 🧠 Personal AI Assistant

A simple terminal-based AI assistant powered by a lightweight open-source language model (`flan-t5-small`) using Hugging Face Transformers. This assistant can remember your recent conversation and respond accordingly.

---

## 🚀 Features

- Lightweight, fast setup (uses `google/flan-t5-small`)
- Maintains a short conversational history (last 5 turns)
- Runs on CPU — no GPU required
- Simple, readable Python code in a single Jupyter notebook

---

## 📂 File Structure

- `Personal_AI_Assistant.ipynb` — The main file, contains the full code for running the assistant.

---

## 🛠️ Installation

Before running the notebook, make sure you have Python installed (preferably 3.8+). Then install the required Python packages:

```bash
pip install transformers torch accelerate -q

---

##💬 How to Use
1.	Open the notebook: Personal_AI_Assistant.ipynb
2.	Run all cells in order
3.	Interact with the assistant in the terminal-like interface
Example interaction:
You: where is the white house located?
🤖 Assistant: New York City

You: bye
👋 Assistant: Goodbye!

---

##❓ Commands
You can end the conversation anytime using:
•	exit
•	quit
•	bye

---

##🧱 Built With
•	🤗 Transformers
•	PyTorch
•	flan-t5-small model by Google
