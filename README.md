# AI_Engineering_Part_1

NLP and AI engineering coursework — notebooks, exercises, and experiments.

## Environment setup

This project uses a **Conda** environment with **Python 3.12** (required for pinned packages such as `spacy==3.8.3`).

### 1. Create the environment

```bash
conda create -n ai_engineering_part_1 python=3.12 -y
```

### 2. Activate the environment

```bash
conda activate ai_engineering_part_1
```

### 3. Install dependencies

From the project root:

```bash
pip install -r requirements.txt
```

### 4. Register the Jupyter kernel (optional)

Use this so notebooks can select this environment as their kernel:

```bash
python -m ipykernel install --user --name=ai_engineering_part_1 --display-name="Python (ai_engineering_part_1)"
```

In Jupyter or VS Code, choose **Python (ai_engineering_part_1)** as the notebook kernel.

### 5. Deactivate when done

```bash
conda deactivate
```

## Quick reference

| Action | Command |
|--------|---------|
| Activate env | `conda activate ai_engineering_part_1` |
| Install packages | `pip install -r requirements.txt` |
| Start JupyterLab | `jupyter lab` |
| Start Notebook | `jupyter notebook` |
