# SIMPLES CRUD
Esta é uma aplicação de back-end desenvolvida usando Java com o framework Spring Boot. O principal objetivo desta API é fornecer operações básicas de CRUD (Create, Read, Update, Delete).

Instalação

Clone o repositório:

````
git clone https://github.com/WendelGustavo/Api-Java-Spring-Boot.git
````

Instale as dependências com Maven

Uso
Inicie a aplicação com Maven
A API estará acessível em http://localhost:8080
Pontos de Extremidade da API
A API oferece os seguintes pontos de extremidade:

POST (Criar): A API permite criar novos registros, como entidades ou recursos, armazenando informações relevantes em um banco de dados.

GET (Ler): Com operações de leitura, a API pode recuperar informações específicas, consultando o banco de dados com base em parâmetros fornecidos ou retornando todos os registros disponíveis.

UPDATE (Atualizar): Há a capacidade de modificar registros existentes, permitindo que os usuários atualizem informações conforme necessário, mantendo a consistência dos dados.

DELETE (Excluir): A API oferece funcionalidades para remover registros, garantindo que os dados sejam mantidos atualizados e reflitam as operações de exclusão apropriadas.

Banco de Dados
O projeto utiliza o PostgresSQL como banco de dados. As migrações necessárias do banco de dados são gerenciadas usando o Flyway.
