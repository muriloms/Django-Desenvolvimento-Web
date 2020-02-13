# Criar novo Projeto Django
- Depois de ativado o ambiente virtual, criar um novo projeto <br/>
`django-admin startproject nomeProjeto`<br/>
- Acessar o projeto e testar conexão<br/>
`python manage.py runserver`<br/>
- Acessar: http://localhost:8000/<br/>
O projeto deve estar funcionando, entretando se acessar http://localhost:8000/admin ocorrerá um erro, o banco de dados ainda não foi atualizado
- Executar migrate para atualizar bd<br/>
`python manage.py migrate` (agora endereço /admin está funcionando)<br/>
- Com o admin funcionando, são criados os super usuários para acessar as areas restritas<br/>
`python manage.py createsuperuser` 
