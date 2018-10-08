### Safety

Recomenda-se utilizar um terminal bash para facilitar o desenvolvimeto e criação do ambiente local.

#### Preperando o Ambiente

	pip install virtualenv
	virtualenv env
	source env/bin/activate

#### Instalando Dependências

	pip install -r requirements.txt

#### Deploy no Heroku

	web: gunicorn --chdir flaskr flaskr:app	
	
#### Determinando Path do Diretório

	export FLASK_APP=flaskr/flaskr.py

#### Para Ambiente de Desenvolvimento

	export FLASK_DEBUG=true

#### Executando Projeto

	flask run
