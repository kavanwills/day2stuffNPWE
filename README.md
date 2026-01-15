# day2stuffNPWE
New project working environment
# Recipe: 
Install necessary extensions in VS Code (Python, Data Wrangler, Jupyter, etc.), create a file (if .py add ipykernel for interactive), activate virtual environment in terminal, then make a requirements.txt file with any packages/versions you need. Finally, commit and push changes
# Terminal commands used:

python -m venv .venv

source .venv/bin/activate

pip install -r requirements.txt

pip install plotly

pip show plotly

pip freeze > requirements.txt

git status

git add .

git commit -m "Day 2 setup"

git push
