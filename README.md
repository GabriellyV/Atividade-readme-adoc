= 📚 Sistema de Gerenciamento deBiblioteca

 👩🏻 Autor: Bianca Isabela Vaz
 📅 Data: 14/02/2025

:icons: font
:toc: left
:toclevels: 2

== 🎯 Sobre o Projeto
O **Sistema de Gerenciamento de Biblioteca** foi desenvolvido para facilitar o
processo de empréstimo, devolução e gerenciamento de livros em uma
biblioteca. Através da aplicação, é possível gerenciar empréstimos de livros,
disponibilidade de exemplares, cadastro de usuários e gerar relatórios de
atividades. O sistema visa **melhorar a experiência** do usuário e **otimizar** a
administração da biblioteca, garantindo uma gestão eficiente e eficaz.

== 🚀 Recursos
📋 **Cadastro e gerenciamento** de livros com informações detalhadas
(título, autor, ISBN, etc.).
Criação e modificação de empréstimos de livros, com opções de data
de empréstimo e devolução.
Visualização da disponibilidade dos livros em tempo real.
Geração de relatórios de empréstimos, devoluções e multas.
Notificação de usuários sobre empréstimos e devoluções.
Sistema de login e autenticação para administradores e usuários.

== 💻 Tecnologias Utilizadas

1. Frontend
  o Angular: Framework utilizado para o desenvolvimento da
interface de usuário, permitindo uma aplicação interativa e
responsiva.

2. Backend
  o Spring Boot (Java): Framework utilizado para o desenvolvimento
da API, que gerencia os empréstimos, os livros e os usuários.

3. Banco de Dados
  o MySQL: Banco de dados relacional utilizado para armazenar
informações sobre empréstimos, usuários e livros.

4. Autenticação
  o JWT (JSON Web Tokens): Utilizado para garantir a segurança
no processo de autenticação e autorização de usuários.
== 🎮 Como Executar
Siga os seguintes passos:

-> **Clone o repositório**
Clone o repositório para o seu ambiente local com o comando:

[source, sh]

----
git clone https://github.com/usuario/sistema-biblioteca.git
----

-> **Instale as Dependências do Frontend**
Navegue até o diretório do frontend e instale as dependências com npm:

[source, sh]

----
cd sistema-biblioteca/frontend
npm install
----

-> **Instale as Dependências do Backend**
Navegue até o diretório do backend e instale as dependências com Maven:

[source, sh]

----
cd sistema-biblioteca/backend
mvn install
----

-> **Configuração do Banco de Dados**
Crie um banco de dados MySQL e configure as credenciais noarquivo application.properties do backend. Em seguida, execute as
migrações para criar as tabelas necessárias:

[source, sh]

----
spring.datasource.url=jdbc:mysql://localhost:3306/biblioteca
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
----

-> **Inicie o Servidor Backend**
Inicie o servidor do backend com o comando:

[source, sh]

----
mvn spring-boot:run
----

-> **Inicie o Servidor Frontend**
Inicie o servidor do frontend com o comando:

[source, sh]

----
ng serve
----

-> **Acesse a Aplicação**
Abra o navegador e acesse a aplicação na URL:

[source, sh]

----
http://localhost:4200.
----

o professor Vinicius por ministrar essa matéria.
== 📚 Documentação da API
A API do Sistema de Gerenciamento de Biblioteca foi documentada
utilizando **Swagger**, permitindo uma **visualização interativa e detalhada** de
todos os endpoints disponíveis. Abaixo estão alguns dos endpoints principais:

GET /api/books: Retorna todos os livros disponíveis.
POST /api/loans: Cria um novo empréstimo de livro.
GET /api/loans/{id}: Obtém os detalhes de um empréstimo específico.
PUT /api/loans/{id}: Atualiza informações de um empréstimo.
 DELETE /api/loans/{id}: Cancela um empréstimo.


Para **acessar a documentação** completa da API no Swagger, inicie o servidor
backend e acesse:

[source, sh]

----
http://localhost:8080/swagger-ui.html
----


== 🤝 Contribuindo

Faça um fork do repositório.
Crie uma nova branch (git checkout -b feature-nome-da-feature).
Faça as alterações e commit (git commit -am &#39;Adiciona nova feature&#39;).
Envie para o repositório original (git push origin feature-nome-da-feature).
Abra um pull request descrevendo as mudanças feitas.


== 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para
mais detalhes.
                                 
== ✉️ Contato
Se você tiver alguma dúvida ou sugestão, entre em contato com a equipe de
desenvolvimento:

[source, sh]

----                                
Email: contato@biblioteca.com
Telefone: +55 11 98765-4321
----  
                                 
== 🙏 Agradecimentos
Agradeço a
