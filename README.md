# ClassKit Studio (Local Edition)

A 100% offline, privacy-focused content creation tool for teachers.

## Features
* **Offline AI:** Uses `Qwen2.5-1.5B-Instruct-Q8` (GGUF) running locally.
* **No API Costs:** Runs on your CPU.
* **Privacy:** No data leaves your machine.
* **Features:** Generates Slides, Posters, and Quizzes locally.

## Setup
1.  **Install Python 3.11+** (Ensure you have a C++ compiler for llama-cpp, e.g., Visual Studio Build Tools on Windows).
2.  **Install requirements:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: installing `llama-cpp-python` might take a moment as it compiles).*

## Running the App
1.  Run the app:
    ```bash
    streamlit run app.py
    ```
2.  **First Run:** The app will automatically download the 1.6GB model file from HuggingFace. This only happens once.
3.  **Inference Speed:** Since it runs on CPU, generation might take 10-30 seconds depending on your computer speed.
