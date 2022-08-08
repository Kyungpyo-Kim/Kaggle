# Kaggle

## Cheatsheet

* Kaggle dataset download
    1. Kaggle -> Profile -> Account -> API -> Create New API Token -> `kaggle.jon` file downloaded
    2. Move `kaggle.json` file to
        * Windows: C:\Users\<Windows-username>\.kaggle\kaggle.json
        * Linux/Mac: ~/.kaggle/kaggle.json

    3. run kaggle module
        ```bash
        python -m pip install pip -U
        python -m pip install kaggle
        kaggle competitions download -c titanic -p ./data/
        ```