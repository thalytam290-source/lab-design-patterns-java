# Lab Padrões de Projeto com Spring Boot

Projeto prático desenvolvido para demonstração dos Padrões de Projeto (Design Patterns) com Spring Boot.

## 🧠 Padrões Aplicados
- **Singleton:** Beans gerenciados nativamente pelo Spring Container (`@Service`, `@RestController`).
- **Strategy:** Interface `ClienteService` permitindo flexibilidade de implementações de negócio.
- **Facade:** Abstração e integração da API ViaCEP com persistência JPA via `ClienteServiceImpl`.

## 🛠️ Tecnologias
- Java 17
- Spring Boot 3
- Spring Data JPA
- OpenFeign
- H2 Database
