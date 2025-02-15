# Projeto de Análise de Dados Aplicativo para os amantes de livros

## Descrição do Projeto
A pandemia de COVID-19 teve um impacto global significativo, alterando profundamente os hábitos e rotinas das pessoas em várias partes do mundo. As restrições impostas para conter o avanço do vírus levaram muitas pessoas a deixarem de frequentar estabelecimentos comerciais, como cafés, shoppings e restaurantes. Em vez disso, um grande número de indivíduos passou a se adaptar ao novo cenário, aproveitando seu tempo em casa para realizar atividades como leitura de livros. Esse novo comportamento foi particularmente marcante, pois não só mudou a dinâmica do consumo, mas também abriu novas oportunidades para diversos setores, especialmente para a indústria editorial e de entretenimento.
Este cenário de isolamento e mudança de comportamento atraiu a atenção de diversas startups, que rapidamente identificaram a crescente demanda por soluções digitais voltadas para os amantes de livros. As empresas começaram a se adaptar ao novo normal, desenvolvendo aplicativos de leitura, plataformas para aquisição de livros e até ferramentas de recomendação de leitura personalizadas. A rapidez com que essas startups se mobilizaram demonstra o interesse do mercado em atender a uma nova necessidade do público, impulsionada pela pandemia.
No âmbito deste projeto, recebemos um banco de dados proveniente de um dos concorrentes já estabelecidos neste mercado de aplicativos para leitores. O banco de dados em questão contém informações detalhadas sobre uma série de aspectos importantes, como livros, editoras, autores, e também as classificações e avaliações feitas pelos clientes dos livros. Além disso, há dados sobre a popularidade dos livros, os tipos de preferências dos leitores e os padrões de avaliação dos produtos. Esses dados serão fundamentais para realizar uma análise aprofundada do comportamento dos consumidores, visando entender suas preferências de leitura e as características dos livros que mais atraem esse público.
O objetivo principal deste projeto é utilizar essas informações para desenvolver uma promoção válida para um novo produto que a empresa está lançando no mercado. A análise detalhada desses dados ajudará a identificar quais livros têm maior potencial de atrair e engajar leitores, quais características são mais valorizadas pelos usuários e como a promoção pode ser estruturada para alcançar um público mais amplo e qualificado. Além disso, ao analisar os perfis dos usuários e suas preferências, será possível criar uma oferta personalizada que maximiza a atração de novos clientes e fideliza os já existentes.
Esse trabalho de análise será fundamental para compreender as tendências atuais no mercado de livros digitais e ajudar a empresa a posicionar seu produto de maneira estratégica, aproveitando as oportunidades geradas pelas mudanças no comportamento do consumidor durante a pandemia.

## A tarefas são:
- Encontrar o número de livros lançados após 1º de janeiro de 2000:
  - Contar quantos livros foram lançados depois dessa data.
- Encontrar o número de avaliações e a média das classificações para cada livro:
  - Contar o número de avaliações de cada livro e calcular a média das classificações recebidas.
- Identificar a editora que lançou o maior número de livros com mais de 50 páginas:
  - Encontrar qual editora lançou mais livros com mais de 50 páginas.
- Identificar o autor com a maior média de classificações para livros com pelo menos 50 avaliações:
  - Encontrar qual autor tem a maior média de classificações, considerando apenas livros com mais de 50 avaliações.
- Encontrar a média de avaliações feitas por usuários que classificaram mais de 50 livros:
  - Calcular a média de avaliações feitas por usuários que classificaram mais de 50 livros.

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
<img src="https://github.com/user-attachments/assets/b3b6531a-046b-4fec-8774-c966043a4fc8" alt="Projeto SQL"/>

### Tabela classificação média dos livros
<img src="https://github.com/user-attachments/assets/a26b55aa-8ae4-4c6b-a53e-3d43bbf3affc" alt="Projeto SQL"/>

### Tabela 5 editoras com mais publicações de livros com mais de 50 páginas
<img src="https://github.com/user-attachments/assets/c5c6140a-58c3-450e-9131-322c3b546459" alt="Projeto SQL"/>

### Escritora com maior classificação média com mais de 50 avaliações
<img src="https://github.com/user-attachments/assets/988b22b1-10a8-4597-98f9-3b4b86ca5769" alt="Projeto SQL"/>

### Média das avaliações entre os usuários que classificaram mais do que 50 livros
<img src="https://github.com/user-attachments/assets/f78d09d9-62f1-4eda-a471-6c029c77479e" alt="Projeto SQL"/>

## Resultados
- Publicações e Participação de Autores e Editoras
  - Foram lançados 821 livros após o ano de 2000, demonstrando um considerável volume de novas publicações no mercado. Além disso, 635 autores contribuíram para esse mercado, distribuídos por 341 editoras, evidenciando a diversidade e a competitividade do setor editorial.
- Avaliações e Interação dos Leitores
  - O número total de 6456 avaliações realizadas pelos leitores reflete o nível de engajamento com os livros. Além disso, 2793 críticas também foram registradas, o que indica uma participação ativa e o desejo dos leitores de compartilhar suas opiniões sobre as obras.
- Classificação dos Livros
  - A média de classificações atribuídas aos livros foi de 3,9, sugerindo uma avaliação geral positiva, com uma recepção favorável por parte dos leitores. Essa média reforça o potencial de qualidade e interesse no catálogo de livros disponível.
- Editoras e Autores de Destaque
  - Penguin Books foi a editora que mais publicou livros no período analisado, destacando-se no mercado editorial. Além disso, a autora J. K. Rowling obteve as melhores avaliações, consolidando sua popularidade e o apelo de seus livros junto aos leitores.
- Potencial do Mercado de Livros Digitais
  - Com base nos dados, é evidente que o mercado editorial, especialmente no segmento de livros digitais, apresenta um grande potencial de crescimento e inovação. O volume significativo de publicações e a alta interação dos usuários demonstram que há uma base sólida de leitores dispostos a consumir e avaliar conteúdo literário.
- Oportunidades para Investimento em Aplicativos para Amantes de Livros
  - Considerando a quantidade de livros publicados e a elevada participação dos leitores em avaliações e críticas, fica claro que o mercado de aplicativos para amantes de livros é uma área promissora para investimento. Tais aplicativos não devem apenas servir como plataformas para que os usuários compartilhem suas opiniões, mas também como ferramentas para recomendação de livros semelhantes aos já lidos, oferecendo a possibilidade de visualização de resenhas de outros leitores, informações sobre onde comprar os livros, e outros recursos que agreguem valor à experiência do usuário.
Portanto, a análise dos dados mostra que o setor de livros digitais e plataformas de leitura tem grande potencial, representando uma excelente oportunidade para inovação e desenvolvimento de novos produtos e serviços direcionados aos amantes de livros.

## Aprendizados
- Consultas SQL

## Contexto real
- Livrarias que buscam aprimorar a experiência de seus clientes
Livrarias que desejam entender de maneira mais profunda as preferências e comportamentos de seus clientes, com o objetivo de otimizar a oferta de produtos e serviços, garantindo uma experiência mais personalizada e eficaz para seus consumidores.
- Novas livrarias locais ou de pequeno porte que buscam ajustar seu portfólio de livros
Livrarias recém-estabelecidas, especialmente aquelas de pequeno porte ou localizadas em bairros específicos, que desejam identificar quais livros são mais adequados para oferecer aos seus potenciais clientes, a fim de atrair e reter um público específico e maximizar suas vendas.
- Empresas de diferentes segmentos que desejam compreender melhor o comportamento de seus clientes/usuários
Qualquer organização que tenha interesse em entender as preferências, necessidades e comportamentos de seus clientes ou usuários, com o objetivo de oferecer uma experiência mais direcionada e diferenciada, aumentando assim a satisfação e a fidelização dos clientes.
- Empresas de pesquisa contratadas para aprimorar a qualidade do atendimento ao cliente
Organizações especializadas em pesquisa de mercado ou satisfação do cliente, contratadas para conduzir análises detalhadas sobre o atendimento e a experiência do cliente em uma empresa específica, com o objetivo de fornecer recomendações que resultem em melhorias nos processos e na interação com os consumidores.
- Empresas de marketing contratadas para otimizar a experiência do cliente de outras empresas
Agências de marketing contratadas por empresas para criar estratégias eficazes de engajamento e fidelização, personalizando campanhas e ofertas de maneira a proporcionar uma experiência aprimorada para os clientes dessas empresas, levando em consideração suas preferências e comportamentos.
- Analistas de dados que buscam compreender melhor situações ou contextos empresariais
Profissionais de análise de dados que atuam em diferentes contextos empresariais, com o intuito de interpretar informações e padrões, ajudando as empresas a tomar decisões informadas sobre diversos aspectos de seus negócios, como estratégia de marketing, atendimento ao cliente, e gestão de produtos ou serviços.

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto nos eu IDE favorito
- Instale as dependências
- Execute o script principal
  
