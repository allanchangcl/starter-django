python -m django --version
python -m pip install -U flake8
python -m pip install -U black
python -m pip install -U pytest
python -m pip install -U django

### set correct vscode python interpreter

Python 3.9.5 64-bit ('.venv':venv)
pip freeze > requirements.txt
git branch -M main
git remote add origin git@github.com:allanchangcl/starter-django.git
git push -u origin main

python -m pip install -U -r requirements.txt
home/allanchangcl/webdev/playground/mydjango/.venv/bin/python -m pip install --upgrade pip
