# Models

Um modelo é a fonte única e definitiva de informações sobre seus dados. 
Ele contém os campos e comportamentos essenciais dos dados que você está armazenando. 
Geralmente, cada modelo é mapeado para uma única tabela de banco de dados.

- Cada modelo é uma classe Python que subclasses django.db.models.Model.
- Cada atributo do modelo representa um campo do banco de dados.
- Com tudo isso, o Django fornece uma API de acesso ao banco de dados gerada automaticamente; consulte Fazendo consultas.

Em resumo</br>
Aplicativos Django acessam e gerenciam dados através de objetos Python chamados de modelos (models). 
Modelos definem a estrutura dos dados armazenados, incluindo os tipos de campos e possivelmente também o seu tamanho máximo, 
valores desault, opções de listas de seleção, texto de ajuda para documentação, texto de labels para formulários, etc. 
A definição do modelo é independente do banco de dados - você pode escolher um tipo de banco como parte das configurações do seu projeto. 
Uma vez que você tenha escolhido qual banco será utilizado você precisa conversar diretamente com ele - 
você somente escreve a estrutura do seu modelo e outros códigos, e o Django faz todo o trabalho sujo de comunicação com o banco para você.
</br>

Material de consulta:</p>
- [Documentação](https://docs.djangoproject.com/en/3.0/topics/db/models/)
- https://developer.mozilla.org/pt-BR/docs/Learn/Server-side/Django/Models
- https://www.gilenofilho.com.br/como-funciona-o-orm-do-django/
