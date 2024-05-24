# datafun-04-jupyter
## Create Project Virtual Environment and update pip and install requests

On mac, create a project virtual environment in the .venv folder. 

''' zsh
python3 -m venv .venv
cd documents/data_analytics/datafun-04-jupyter/.venv/bin
source activate
touch requirments.txt
python3 -m pip install -r requirements.txt
python3 -m pip install jupyterlab numpy pandas matpotlib seaborn scipy
python3 -m pip freeze > requirements.txt
mkdir .gitignore
'''
## add lines .venv/ and .vscode/ to .gitignore file

## Git add and commit

'''zsh
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
'''

## Specification
'''
This project was built to the following specification:

- [datafun-04-spec](https://github.com/denisecase/datafun-04-spec)
'''