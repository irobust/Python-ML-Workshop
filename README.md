# Machine Learning with Python
## How to run transformer model
1. Create folder "hugging-face"
2. cd hugging-face
3. uv init
4. uv venv
5. .venv\Scripts\activate
6. uv add "transformer[torch]"
7. Coding in "main.py"
    ```python
    from transformers import pipeline

    classifier = pipeline("sentiment-analysis")

    result = classifier("I hate hugging face")

    print(result)
    ```
8. uv run main.py
