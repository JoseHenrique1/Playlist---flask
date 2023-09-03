# Criando venv e ativando
py -m venv venv
cd venv/Scripts
activate

# Voltando para a raiz do projeto 
cd ..
cd ..

# Iniciando o projeto
pip install -r requirements.txt
flask --app app.py run

# Observação!
Você deve ter sua chave de api do tmdb
