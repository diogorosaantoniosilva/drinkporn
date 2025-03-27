# drinkporn
## Summary:
# Este .gitignore é configurado para um projeto de Inteligência Artificial (IA) que cria cocktails.
# Ele cobre as seguintes áreas:
# 1. Ignora arquivos temporários e de cache gerados pelo Python.
# 2. Ignora arquivos e pastas de configuração de IDEs populares como VSCode, PyCharm, etc.
# 3. Ignora diretórios de ambientes virtuais Python (venv, env).
# 4. Ignora arquivos relacionados a Jupyter Notebooks.
# 5. Ignora arquivos de log, dependências de pacotes, e outros arquivos temporários gerados durante o desenvolvimento.

# Python
__pycache__/
*.py[cod]
*.pyo
*.pyd
.Python
env/
venv/
ENV/
*.env
*.venv
*.ipynb_checkpoints

# Jupyter Notebooks
.ipynb_checkpoints/

# IDEs and Text Editors
.vscode/
.idea/
*.sublime-project
*.sublime-workspace
*.vscode/

# Dependency directories
node_modules/
bower_components/

# PyCharm
.idea/

# macOS
.DS_Store

# Windows
Thumbs.db
ehthumbs.db

# Logs
*.log
*.out
*.err

# Environment variables
.env

# Package distribution files
dist/
build/
*.egg-info/

# Testing
.coverage
nosetests.xml
test_*.xml
coverage.xml
*.cover
*.hypothesis/

# Virtualenv
venv/
ENV/

# Python Wheel
*.whl

# Sensitive files (e.g., API keys)
secret_config.json
secrets.py
