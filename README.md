<h1> Projeto Biblioteca - Sistema de Gerenciamento de Livros </h1>

Descrição:
Este é um projeto de exemplo de um sistema de gerenciamento de uma biblioteca de livros, desenvolvido em Flask com integração ao MySQL. Permite adicionar livros, pesquisar por título ou autor, editar a quantidade de livros e excluir livros da biblioteca.

Funcionalidades:
- Adicionar Livros: Permite inserir novos livros no sistema, especificando título, autor, gênero, editora, ano de publicação e quantidade.
- Pesquisar Livros: Realiza buscas por título ou autor, retornando os livros que correspondem ao critério de pesquisa.
- Editar Quantidade: Permite atualizar a quantidade disponível de um livro na biblioteca.
- Excluir Livros: Remove um livro da biblioteca, ajustando automaticamente os IDs dos livros restantes.

Tecnologias Utilizadas:
- Flask: Framework web em Python para desenvolvimento do backend.
- MySQL: Banco de dados relacional utilizado para armazenar informações sobre os livros.
- Flask-MySQLdb: Extensão Flask para facilitar a integração com o MySQL.

Instruções para Inicialização:
1. Clone o Repositório:
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   
2. Instale as Dependências:
   pip install -r requirements.txt
   
3. Configuração do MySQL:
   - Crie um banco de dados chamado 'biblioteca'.
   - Execute o script SQL para criar a tabela de livros dentro do banco de dados.
   
4. Execute o Projeto:
   python app.py
   
5. Acesse a Aplicação:
   Abra seu navegador e vá para http://localhost:5000/ para acessar a aplicação.

Nota: Certifique-se de ter o Python e o MySQL instalados em seu ambiente de desenvolvimento antes de prosseguir com a instalação e execução do projeto.

Para mais detalhes sobre a estrutura do projeto e o código-fonte, consulte os arquivos no diretório do projeto.

---
Este arquivo README fornece uma visão geral do projeto, suas funcionalidades principais, as tecnologias utilizadas e instruções básicas para começar a trabalhar com o sistema de gerenciamento de biblioteca.
