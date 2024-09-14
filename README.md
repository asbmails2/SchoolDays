<h1>School Days</h1>

Versão 2 do projeto de sistema básico em django para gestão de notas e alunos.

Será criado um modelo de projeto por engenharia de requisitos nos quais serão abordados os requisitos principais:
- Gestão de alunos / School
  - Presença
  - Notas
  - Histórico
  - Boletim
  - comunicaco com os pais
- Gestão de turmas
  - Turmas por diciplina por ano
  - professor responsável
  - alunos []
  - agenda de aulas
  - campo relatório de aula 
- Secretaria
  - Funções de gestão de professores, responsáveis e alunos
  - relatórios de aula
 
Será melhor explorado e criado conforme o andamento da criação do projeto.

Resumo do Modelo de Organização do Django
O Django oferece uma estrutura clara e eficiente para organizar seus projetos web. Essa organização padrão facilita a manutenção, colaboração e escalabilidade do seu aplicativo.

Estrutura Básica:

projeto: A pasta raiz do seu projeto Django. Contém configurações globais, arquivos de URL e o arquivo manage.py.
apps: Cada aplicativo dentro do seu projeto reside em uma pasta separada dentro de apps. Cada app representa uma funcionalidade específica (ex: blog, loja virtual, sistema de autenticação).
models.py: Define os modelos, que representam as tabelas do seu banco de dados e as estruturas dos seus dados.
views.py: Contém as views, que são as funções que recebem requisições HTTP, processam os dados e retornam respostas.
urls.py: Mapeia URLs para as views, definindo como as requisições são direcionadas para as funções corretas.
Diagrama Simplificado:

projeto/
├── manage.py
├── __init__.py
├── settings.py
├── urls.py
└── apps/
    ├── app1/
    │   ├── __init__.py
    │   ├── models.py
    │   ├── views.py
    │   └── urls.py
    └── app2/
        # ...
Benefícios da Organização:

Modularidade: Cada app pode ser desenvolvido e testado de forma independente.
Reusabilidade: Apps podem ser reutilizados em diferentes projetos.
Escalabilidade: Facilita a adição de novas funcionalidades.
Manutenibilidade: Código mais organizado e fácil de entender.
Conceitos-chave:

Models: Representam os dados que você deseja armazenar (ex: posts de um blog, produtos de uma loja).
Views: Processam as requisições HTTP e geram as respostas (ex: exibir uma lista de posts, salvar um novo produto).
URLs: Mapeiam as URLs para as views (ex: http://seusite.com/blog/post/1/).
Templates: Arquivos HTML que definem a aparência das páginas (ex: index.html, post_detail.html).
Dicas Adicionais:

Utilize apps para organizar seu código: Cada funcionalidade específica deve ter seu próprio app.
Separe a lógica de apresentação da lógica de negócio: Mantenha seus templates simples e focados na apresentação, enquanto as views cuidam da lógica.
Utilize o ORM do Django: O Object-Relational Mapper do Django facilita a interação com o banco de dados.
Siga as convenções de nomenclatura: Use nomes claros e concisos para seus modelos, views e URLs.
Teste seu código: Escreva testes unitários para garantir a qualidade do seu código.

