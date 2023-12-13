# Generate Blogs using LLama 2 stored in Local

This is a Streamlit app that generates blogs using the LLama 2 model. The user can input the topic, number of words, and the job profile for which the blog is being written. The app then generates a blog post based on the input.

## Installation

Use the package manager pip to install the required packages.

```bash
pip install streamlit
pip install langchain
pip install sentence-transformers
pip install uvicorn
pip install ctransformers
pip install langchain
pip install python-box
pip install streamlit

```

## Model Directory
Please note that the langchain package is not available on PyPI, so you will need to install it manually. Also, make sure that the llama-2-7b-chat.ggmlv3.q8_0.bin model file is present in the models directory.

https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin

## Run

Use the package manager pip to install the required packages.
To run the app, install the required packages and run the following command:

```bash
streamlit run app.py
```

