# Projeto de Análise de Dados Aplicativo para os amantes de livros

## Descriçaõ do Projeto
O coronavírus pegou o mundo todo de surpresa mudando a rotina das pessoas. Os moradores das cidades já não passavam mais seu tempo livre fora de casa, indo a cafés e shoppings; a maioria ficou em casa lendo livros. Isso chamou atenção de startups que se apressaram para desenvolver novos aplicativos para os amantes de livros.
Neste projeto recebemos um banco de dados de um dos serviços concorrentes nesse mercado. Ele contém dados sobre livros, editoras, autores e classificação de clientes e avaliação de livros. Essa informação será usada para gerar uma promoção válida para o novo produto

## A tarefas são:
- Encontrar o número de livros lançados depois de 1 de janeiro de 2000
- Encontrar o número de avaliações e a classificação média para cada livro
- Identificar a editora que lançou o maior número de livros com mais de 50 páginas
- Identificar o autor com a média mais alta de classificação de livros: olhe apenas para livros com pelo menos 50 classificações
- Encontrar o número médio de avaliações entre usuários que classificaram mais do que 50 livros

## Dicionário de dados
- books: contém dados sobre livros
  - 'book_id': identificador do livr
  - 'author_id': identificador do autor
  - 'title': título
  - 'num_pages': número de páginas
  - 'publication_date': data de publicação
  - 'publisher_id': identificador da editora
- authors: contém dados sobre os autores
  - 'author_id': identificador do autor
  - 'author': autor
- publishers: contém dados sobre editoras
  - 'publisher_id': identificador da editora
  - 'publisher': editora
- ratings: contém dados sobre classificação dos usuários
  - 'rating_id': identificador da classificação
  - 'book_id': identificador do libro
  - 'username': o nome do usuário que avaliou o livro
  - 'rating': classificação
- reviews: contém dados sobre revisão dos clientes
  - 'review_id': identificador da revisão
  - 'book_id': identificadoe do livro
  - 'username': o nome do usuário que revisou o livro
  - 'text': o texto da revisão

## Ferramentas e Bibliotecas utilizadas
- Python: Linguagem principal utilizada para análise
- Sqlalchemy: Biblioteca python para trabalhar com consultas SQL

## Resultados
- São 821 livros publicados depois de 2000
- São 635 autores publicados por 341 editoras
- Foram feitas 6456 avaliações pelos clientes e 2793 críticas
- A média de classificações por livros é 3,9
- A editora que mais publicou foi a Penguin Books
- A autora mais bem avaliada é a J. K. Rowling
- É um mercado que vale a pena investir

## Aprendizados
- Consultas SQL

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto nos eu IDE favorito
- Instale as dependências
- Execute o script principal
  
