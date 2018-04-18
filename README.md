Baixar o projeto:

	
	git clone git@github.com:willemallan/python-lambda-samples.git


Criar um novo env:


	mkvirtualenv --python=python3 lambda-samples



Entrar na pasta:


	cd python-lambda-samples



Marcar pasta do projeto como default do env:


	setvirtualenvproject



Executando exemplo 1 - Hello World:


	python-lambda-local -l lib/ -f hello_world -t 5 sample1/index.py sample1/event.json