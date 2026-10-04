# Contrato Inicial da API REST — Livro+

## 1. Objetivo

A API REST do Livro+ será responsável por disponibilizar operações relacionadas aos livros, empréstimos e avaliações.

## 2. Recursos

A API terá inicialmente os seguintes recursos:

- Livros
- Empréstimos
- Avaliações

## 3. Endpoints

### Livros

| Método | Endpoint | Descrição |
|---|---|---|
| GET | `/api/livros/` | Lista os livros cadastrados |
| GET | `/api/livros/{id}/` | Consulta um livro específico |
| POST | `/api/livros/` | Cadastra um novo livro |
| PUT | `/api/livros/{id}/` | Atualiza um livro |
| DELETE | `/api/livros/{id}/` | Exclui um livro |

### Empréstimos

| Método | Endpoint | Descrição |
|---|---|---|
| GET | `/api/emprestimos/` | Lista os empréstimos |
| GET | `/api/emprestimos/{id}/` | Consulta um empréstimo |
| POST | `/api/emprestimos/` | Registra um empréstimo |
| PUT | `/api/emprestimos/{id}/` | Atualiza um empréstimo |
| DELETE | `/api/emprestimos/{id}/` | Remove um registro de empréstimo |

### Avaliações

| Método | Endpoint | Descrição |
|---|---|---|
| GET | `/api/avaliacoes/` | Lista as avaliações |
| GET | `/api/avaliacoes/{id}/` | Consulta uma avaliação |
| POST | `/api/avaliacoes/` | Registra uma avaliação |
| PUT | `/api/avaliacoes/{id}/` | Atualiza uma avaliação |
| DELETE | `/api/avaliacoes/{id}/` | Remove uma avaliação |

## 4. Formato das respostas

As respostas da API serão disponibilizadas no formato JSON.

## 5. Códigos HTTP previstos

- `200 OK` — operação realizada com sucesso.
- `201 Created` — recurso criado com sucesso.
- `400 Bad Request` — requisição inválida.
- `401 Unauthorized` — usuário não autenticado.
- `403 Forbidden` — usuário sem permissão.
- `404 Not Found` — recurso não encontrado.
- `500 Internal Server Error` — erro interno do servidor.

## 6. Autenticação e autorização

O acesso aos recursos será controlado de acordo com o perfil do usuário.

O Administrador/Bibliotecário terá acesso às operações de gerenciamento do acervo e dos empréstimos.

O Usuário/Leitor terá acesso às operações relacionadas às suas consultas, empréstimos, leituras e avaliações.
