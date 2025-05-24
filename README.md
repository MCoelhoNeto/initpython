# initpython

# 1. Criar pasta do projeto e acessar
mkdir meu_projeto
cd meu_projeto

# 2. Criar ambiente virtual com .venv
python -m venv .venv

# 3. Ativar o ambiente virtual

# ▶ Para Windows (cmd ou PowerShell):
.venv\Scripts\activate

# ▶ Para Linux/macOS:
source .venv/bin/activate

# 4. Instalar bibliotecas desejadas
pip install flask requests

# 5. Criar arquivo principal do projeto (opcional)
touch main.py

# 6. Gerar arquivo requirements.txt com as dependências
pip freeze > requirements.txt

# 7. (Quando clonar ou copiar o projeto em outro lugar)
# Ativar o ambiente virtual novamente:
# Windows:
.venv\Scripts\activate
# Linux/macOS:
source .venv/bin/activate

# 8. Instalar dependências listadas no requirements.txt
pip install -r requirements.txt
