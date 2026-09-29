# my-rag-app

This is a minimal implementation of the RAG model for question answering.

## Requirements

Before setting up the project, make sure you have the following prerequisites installed:

* **Conda Package Manager** (Miniconda or Anaconda):
  * [Miniconda Official Installation](https://docs.anaconda.com/miniconda/) (Recommended)
  * [Anaconda Official Installation](https://www.anaconda.com/download)
* **Python**: Version 3.10 or later.

## Environment Setup

Follow these steps to create, activate your isolated Conda environment, and install dependencies:

### 1. Create a Conda Environment
Open your terminal and run the following command to create a new environment named `mini-rag-app` with Python 3.10:

```bash
conda create -n mini-rag-app python=3.10 -y
```

### 2. Activate the Environment
To activate the created environment, run:

```bash
conda activate mini-rag-app
```

### 3. Verify Python Version
Confirm that the correct version of Python is active:

```bash
python --version
```

### 4. Install Dependencies
Install all required packages specified in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Environment Variables Configuration

The application requires environment variables (e.g., API keys) to function properly.

1. **Create your `.env` file:**
   Copy the provided `.env.example` file to create a `.env` file:

   ```bash
   cp .env.example .env
   ```

2. **Set up API Keys:**
   Open the newly created `.env` file in your code editor and add your API keys (e.g., OpenAI, Anthropic, or Hugging Face keys):

   ```env
   OPENAI_API_KEY=your_actual_api_key_here
   ```

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/mostafaamohameddd/my-rag-app.git](https://github.com/mostafaamohameddd/my-rag-app.git)
   cd my-rag-app
   ```

2. **Activate environment & install packages:**
   ```bash
   conda activate mini-rag-app
   pip install -r requirements.txt
   ```

3. **Configure environment variables:**
   ```bash
   cp .env.example .env
   ```