🧠 Website Summarizer with Ollama & BeautifulSoup
This project demonstrates a Python-based tool for scraping and summarizing the content of any website using BeautifulSoup and Ollama's LLaMA3.2 model. It provides a practical alternative to OpenAI's API by running LLMs locally.

🔍 Features
Scrapes textual content from a given URL using requests + BeautifulSoup

Removes unnecessary tags (like scripts, styles, images, inputs)

Uses Ollama (LLaMA3.2) to summarize web content

Designed for local, offline LLM usage

Also includes a placeholder for comparison with OpenAI summarization (optional)

🛠️ Dependencies
beautifulsoup4

requests

ollama (Python binding for locally run models)

python-dotenv

openai (optional, for OpenAI summarization)

Install all dependencies with:
pip install -r requirements.txt

🚀 How to Use
Clone the repo:
git clone https://github.com/yourusername/website-summarizer.git
cd website-summarizer
Start Ollama and load a model:

Make sure ollama is installed and running. Pull a model like:

bash
Copy
Edit
ollama pull llama3
Run the notebook:

Open the Jupyter notebook main.ipynb and run all cells.

Provide a URL:

In the input cell, replace the sample URL with any website you want to summarize.


This project is great for experimenting with local LLMs like Ollama.

Make sure to have Ollama running before you start summarization.

OpenAI support is optional and requires an API key in .env.

