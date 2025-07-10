# anthropic-course
working content from anthropic course

## Run Locally

### Create virtual python environment
```bash
python3 -m venv /path/to/new/virtual/environment
```

Best practice is not to create the venv in the repo but to group by projects. For example:

```bash
python3 -m venv .venv
```

This will create the venv in the above mentioned folder which can then be referred to for
several crime data projects. 

### activate the venv

```bash
source .venv/bin/activate
```

### Install pip packages

```bash
python3 -m pip install anthropic python-dotenv
```

### Install dependencies
```bash
pip install -r requirements.txt
```
