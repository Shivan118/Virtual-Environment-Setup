## Create a virtual environment
```
python -m venv .venv
```

## Activate virtual environment
```
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
```

## Install dependencies
```
pip install -r requirements.txt
```

## Bonus: Add .venv to .gitignore
To avoid uploading the virtual environment to GitHub:

Create a .gitignore file and add:
```
venv/
.venv/
```
