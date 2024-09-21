<img width="912" alt="Captura de Tela 2024-09-20 às 21 21 12" src="https://github.com/user-attachments/assets/5e49f9e1-82e5-49f6-872e-818510fafda5">

# User Department CRUD

Um projeto de gerenciamento de usuários desenvolvido com Spring Boot e JPA. Este projeto permite operações CRUD (Criar, Ler, Atualizar e Deletar) para gerenciar informações de usuários.

## Tecnologias Utilizadas

- [Spring Boot](https://spring.io/projects/spring-boot) - Framework para desenvolvimento de aplicações Java.
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) - Para interação com o banco de dados.
- [H2 Database](https://www.h2database.com/) - Banco de dados em memória para desenvolvimento e testes.
- [Maven](https://maven.apache.org/) - Gerenciador de dependências e construção do projeto.

## Pré-requisitos

- JDK 17 ou superior
- Maven 3.6 ou superior

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/userdept.git
   cd userdept
   ```
2. Compile o projeto:
   ```bash
   mvn clean install
   ```
3. Execute a aplicação:
   ```bash
   mvn spring-boot:run
   ```

## Endpoints

A API possui os seguintes endpoints:

- <strong>GET /users:</strong> Retorna todos os usuários.

- <strong>GET /users/{id}:</strong> Retorna um usuário específico pelo ID.

- <strong>POST /users:</strong> Adiciona um novo usuário.

- <strong>PUT /users/{id}:</strong> Atualiza um usuário existente pelo ID.

- <strong>DELETE /users/{id}:</strong> Remove um usuário pelo ID.

## Exemplo de Uso

Você pode usar ferramentas como Postman ou curl para testar os endpoints.

### Exemplo de Requisição POST

   ```bash
     curl -X POST http://localhost:8080/users \
  -H "Content-Type: application/json" \
  -d '{
    "name": "John Doe",
    "email": "john.doe@example.com"
  }'
   ```

## Contribuições

Sinta-se à vontade para contribuir com o projeto. Para isso, siga os passos:

1. Fork este repositório.
2. Crie uma nova branch (git checkout -b feature/nome-da-sua-feature).
3. Faça suas alterações e commit (git commit -m 'Adiciona nova feature').
4. Faça o push para a branch (git push origin feature/nome-da-sua-feature).
5. Abra um Pull Request.


## Licença

Este projeto está licenciado sob a MIT License.

## Para mais informações, entre em contato pelo email: gustavolirasn@gmail.com
