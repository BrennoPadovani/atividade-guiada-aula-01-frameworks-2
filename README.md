# Atividade Guiada – API CRUD de Tarefas (Spring Boot)

API CRUD para controle de tarefas, com dados armazenados em memória (lista interna).

## Tecnologias
- Java 17+
- Spring Boot 4.1.1 (Spring Web)
- Maven

## Como executar
```bash
mvn spring-boot:run
```
A API sobe em `http://localhost:8080`.

## Endpoints
| Método | URL | Descrição |
|--------|-----|-----------|
| GET | /tasks | Lista todas as tarefas |
| GET | /tasks/{id} | Busca uma tarefa pelo ID |
| POST | /tasks | Cria uma tarefa |
| PUT | /tasks/{id} | Atualiza uma tarefa |
| DELETE | /tasks/{id} | Exclui uma tarefa |

## Exemplo de corpo (POST/PUT)
```json
{
  "title": "Casa",
  "description": "Organizar as tarefas de casa",
  "dueDate": "2026-12-31T00:00:00"
}
```

## Integrantes
- Brenno Lucas Padovani Salgado
