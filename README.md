# DSPy Learning Examples - Jupyter Notebook

This repository contains comprehensive Jupyter notebook examples from the [DSPy Learn](https://dspy.ai/learn/) documentation.

## 📚 Overview

DSPy is a framework for building AI systems with language models. This notebook covers all the core concepts you need to get started:

| Section | Description |
|---------|-------------|
| **Language Models** | Setting up and configuring LMs |
| **Signatures** | Defining input/output behavior |
| **Modules** | Using DSPy modules like Predict, ChainOfThought |
| **Adapters** | ChatAdapter and JSONAdapter |
| **Tools** | Using tools with ReAct and manual handling |
| **MCP** | Model Context Protocol integration |
| **Data Handling** | Working with Example objects |
| **Metrics** | Defining evaluation metrics |
| **Optimizers** | Optimizing prompts and weights |

## 🚀 Quick Start

### Run Locally

1. Clone this repository (if applicable)
2. Install DSPy:
   ```bash
   pip install -U dspy
   ```
3. Set your API key:
   ```python
   import os
   os.environ['OPENAI_API_KEY'] = 'your-api-key-here'
   ```
4. Open the notebook:
   ```bash
   jupyter notebook dspy_learn_examples.ipynb
   ```

### Run in Google Colab

Click the button below to open this notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/duksaramio/dspy-jupyter-notes/blob/main/dspy_learn_examples.ipynb)

**Or manually:**
1. Go to [Google Colab](https://colab.research.google.com)
2. Click "GitHub" tab
3. Enter: `https://github.com/duksaramio/dspy-jupyter-notes`
4. Select `dspy_learn_examples.ipynb`

## 📋 Table of Contents

1. [Setup](#setup)
2. [Language Models](#language-models)
3. [Signatures](#signatures)
4. [Modules](#modules)
5. [Adapters](#adapters)
6. [Tools](#tools)
7. [MCP](#mcp)
8. [Data Handling](#data-handling)
9. [Metrics](#metrics)
10. [Optimizers](#optimizers)

## 🔧 Requirements

- Python 3.8+
- DSPy
- OpenAI API key (or other LLM provider)

## 📦 Installation

```bash
# Install DSPy
pip install -U dspy

# Optional: Install with MCP support
pip install -U "dspy[mcp]"
```

## 📖 Learning Resources

- [DSPy Documentation](https://dspy.ai)
- [DSPy Learn](https://dspy.ai/learn/)
- [DSPy Tutorials](https://dspy.ai/tutorials/)
- [DSPy API Reference](https://dspy.ai/api/)

## 🤝 Contributing

Feel free to extend this notebook with more examples!

## 📄 License

This project is for educational purposes. See the [DSPy license](https://github.com/stanfordnlp/dspy) for details.

---

Made with ❤️ using [DSPy](https://dspy.ai)
