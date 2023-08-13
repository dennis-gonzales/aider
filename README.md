# About the project

AI pair programming in your terminal

## Getting Started

```bash
conda create --prefix ./env
```

```bash
pip install -r requirements.txt
```

### Activate

```bash
# use `conda info --envs` to list all your envs
conda activate /PATH_TO_PROJ/env
```

### Deactivate

```bash
conda deactivate
```

## Start Coding

```bash
aider --openai-api-key "<API_KEY>" file_name.file_ext
# example aider --openai-api-key "sk-..." src/hello.ts
```

## Troubleshooting

### Selecting The Correct Kernel

Make sure you've selected the **correct environment** to run on.

e.g. `python <python-version> (conda) .\env\python.exe`
