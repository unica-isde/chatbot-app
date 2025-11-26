# Web application to deploy an AI-based chatbot


## Download the repository

Use git to clone the repository:

```bash
git clone https://github.com/unica-isde/chatbot-app
```

Optional but recommended - create conda environment: https://docs.conda.io/projects/miniconda/en/latest/
```bash
conda create --name isde python=3.12
conda activate isde
```

And install the requirements with 

```bash
pip install -r requirements.txt
```

## Configuration

Configure the service by editing the file `app/config.py`.

## Usage

### Run locally

To run the application, it is sufficient to execute this command from a terminal:
```bash
fastapi dev
```
