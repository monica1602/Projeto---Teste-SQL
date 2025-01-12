![projeto SQL - tabela livros](https://github.com/user-attachments/assets/f2e7b4b1-3565-4b6c-994d-fb1322afa1ff)# Projeto de Análise de Dados Aplicativo para os amantes de livros

## Descrição do Projeto
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

## Imagens

### Tabela livros
<img src="https://github.com/user-attachments/assets/8744507d-2897-4137-98ba-850214ea9a6f" alt="Projeto SQL"/>

### Tabela autores
<img src="https://github.com/user-attachments/assets/f41e2aac-80cd-4620-82ca-c74c272edfb9" alt="Projeto SQL"/>

### Tabela editoras
<img src="https://github.com/user-attachments/assets/ab0cee81-d8bf-4c82-9937-8412c76fa040" alt="Projeto SQL"/>

### Tabela classificação
<img src="https://github.com/user-attachments/assets/b496ec3e-8764-4daa-8cd1-a3550c21895d" alt="Projeto SQL"/>

### Tabela avaliações
<img src="https://github.com/user-attachments/assets/a5d04053-98d0-49f3-bbdf-a6abb8c8d76b" alt="Projeto SQL"/>

### Quantidade de livros lançado depois de 01/01/2000
<img src="https://github.com/user-attachments/assets/89b41e34-61a2-42e9-a039-efe45935846c" alt="Projeto SQL"/>

### Quantidade de avaliações
<img src="https://github.com/user-attachments/assets/c8f386f1-1e29-4835-b027-10df78b0d38" alt="Projeto SQL"/>

### Tabela classificação média dos livros
<img src="https://github.com/user-attachments/assets/a26b55aa-8ae4-4c6b-a53e-3d43bbf3affc" alt="Projeto SQL"/>

### Tabela 5 editoras com mais publicações de livros com mais de 50 páginas
<img src="https://github.com/user-attachments/assets/c5c6140a-58c3-450e-9131-322c3b546459" alt="Projeto SQL"/>

### Escritora com maior classificação média com mais de 50 avaliações
<img src="https://github.com/user-attachments/assets/988b22b1-10a8-4597-98f9-3b4b86ca5769" alt="Projeto SQL"/>

### Média das avaliações entre os usuários que classificaram mais do que 50 livros
<img src="https://github.com/user-attachments/assets/f78d09d9-62f1-4eda-a471-6c029c77479e" alt="Projeto SQL"/>

## Resultados
- São 821 livros publicados depois de 2000
- São 635 autores publicados por 341 editoras
- Foram feitas 6456 avaliações pelos clientes e 2793 críticas
- A média de classificações por livros é 3,9
- A editora que mais publicou foi a Penguin Books
- A autora mais bem avaliada é a J. K. Rowling
- É um mercado que vale a pena investir
- Com os dados, é possível perceber que relamente é um mercado que vale a pena investir
- A quantidade de livros publicados foi bem grande
- Existe um grande número de usuários que avaliam continuar a ler e mostrar sua opinião para próximos livros e estilos de livros que mais gostam
- Concluindo, vale a pena investir em aplicativos para amantes de livros, seja ele apenas um lugar para os usuários mostrarem suas opniões, como também um lugar para mostrar livros com estilos parecidos com o que eles leram, opniões de outros usuários, onde comprar, entre outras coisas 

## Aprendizados
- Consultas SQL

## Contexto real
- Livrarias que desejam entender melhor seus clientes, para com isso oferecer uma melhor experiência
- Novas livrarias de bairro ou pequenas, que desejam saber quais livros oferecer para seus possíveis clientes
- Qualquer tipo de empresa que deseja entender melhor seus clientes/usuários e oferecer uma experiência diferenciada
- Empresas de pesquisa contratadas para melhorar o atendeimento ao clientes de alguma empresa
- Empresas de marketing contratadas para oferecer uma melhor experiência para os clientes de alguma empresa
- Analistas de dados que desejam entender melhor alguma situação de alguma empresa

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto nos eu IDE favorito
- Instale as dependências
- Execute o script principal
  
