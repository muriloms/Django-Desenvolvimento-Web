# Preparar ambiente de desenvolvimento
Instalar virtualenv <br/>
`pip install virtualenv`<br/>
Criar uma pasta para o projeto<br/>
Criar o ambiente virtual com python<br/>
`virtualenv nomeProjeto`<br/>
Ou <br/>
`python -m venv nomeProjeto`<br/>
Ative o ambiente
`cd nomeProjeto\Scripts`
`activate`

## Instalar Django e lib para banco de dados
`pip install Django`<br/>
`pip install psycopg2` - PostGres 

#### (no ubunto caso não instalar direto o psycopg, roda o códio abaixo)
` sudo apt-get install libpq-dev python-dev`
