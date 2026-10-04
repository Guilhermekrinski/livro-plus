# Cenários de Aceite — Livro+

## 1. Pesquisa de livros

### Cenário 1 — Pesquisa realizada com sucesso

**Dado que** o usuário está na página de catálogo  
**Quando** informar o título, autor ou ISBN de um livro  
**Então** o sistema deverá apresentar os livros encontrados.

### Cenário 2 — Nenhum livro encontrado

**Dado que** o usuário está realizando uma pesquisa  
**Quando** não houver resultados correspondentes  
**Então** o sistema deverá informar que nenhum livro foi encontrado.

---

## 2. Visualização de livro

### Cenário 3 — Visualizar detalhes

**Dado que** o usuário encontrou um livro  
**Quando** selecionar o livro  
**Então** o sistema deverá apresentar seus detalhes, como título, autor, descrição, ISBN e disponibilidade.

---

## 3. Empréstimo

### Cenário 4 — Solicitar empréstimo

**Dado que** o livro está disponível  
**Quando** o usuário solicitar o empréstimo  
**Então** o sistema deverá registrar o empréstimo e informar a data prevista para devolução.

### Cenário 5 — Livro indisponível

**Dado que** o livro não possui exemplares disponíveis  
**Quando** o usuário tentar solicitar o empréstimo  
**Então** o sistema deverá informar que o livro está indisponível.

---

## 4. Avaliação

### Cenário 6 — Registrar avaliação

**Dado que** o usuário está autenticado  
**Quando** registrar uma nota e um comentário para um livro  
**Então** o sistema deverá salvar a avaliação.

---

## 5. Google Books API

### Cenário 7 — Consulta à Google Books API

**Dado que** o usuário realizou uma pesquisa de livro  
**Quando** o sistema consultar a Google Books API  
**Então** as informações encontradas deverão ser utilizadas para complementar a apresentação dos dados do livro.

### Cenário 8 — Falha na API externa

**Dado que** a Google Books API esteja indisponível  
**Quando** o sistema realizar uma consulta  
**Então** o Livro+ deverá informar a indisponibilidade sem interromper o funcionamento principal da aplicação.

---

## 6. Administração

### Cenário 9 — Cadastro de livro

**Dado que** o usuário possui perfil de administrador/bibliotecário  
**Quando** cadastrar um livro  
**Então** o sistema deverá registrar o livro no acervo.

### Cenário 10 — Gerenciamento do acervo

**Dado que** o administrador está autenticado  
**Quando** acessar o gerenciamento do acervo  
**Então** deverá poder consultar, editar e excluir livros cadastrados.
