# Backend DESK HELP API

Aplicação backend com Java Spring Boot para fornecer API RESTful.

## 📋 Tecnologias

- **Java 21**
- **Spring Boot 3.5**
- **PostgreSQL** (ynhhA)
- **Spring Data JPA** + Hibernate
- **Spring Security**
- **Swagger** (Documentação API)
- **Maven** (Gerenciamento de dependências)

## ⚙️ Configuração do Ambiente

### Pré-requisitos
- JDK 21
- PostgreSQL 15+
- Maven 3.9+

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/EmersonBranch/desk-help-api.git
   ```
2. Configure o banco de dados:
   - Crie um database `ynhhA` no PostgreSQL
   - Altere as credenciais no `application.properties` ou `application.yml`

3. Execute a aplicação:
   ```bash
   mvn spring-boot:run
   ```

## 📡 Endpoints da API
Acesse a documentação interativa:
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- OpenAPI: `http://localhost:8080/v3/api-docs`

## 🌱 Estrutura do Projeto
```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── [seuprojeto]/
│   │           ├── config/       # Configurações Spring
│   │           ├── controller/   # Camada de API
│   │           ├── model/        # Entidades JPA
│   │           ├── repository/   # Interfaces JPA
│   │           ├── service/      # Lógica de negócio
│   │           └── security/     # Configurações de segurança
│   └── resources/
│       ├── application.properties
│       └── ...
```

## 🛠️ Comandos Úteis
```bash
# Rodar testes
mvn test

# Buildar o projeto
mvn clean package

# Rodar com perfil de desenvolvimento
mvn spring-boot:run -Dspring-boot.run.profiles=dev
```

## 🤝 Contribuição
Siga o fluxo Git:
1. Crie uma branch a partir de `prod`
2. Envie alterações para `dev`
3. Abra um PR para `stage` após revisão
```
