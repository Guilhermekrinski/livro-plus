# Livro+

> Sistema web para gerenciamento de biblioteca e interação com leitores.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/versão-0.1.0-blue)
![Licença](https://img.shields.io/badge/licença-acadêmica-lightgrey)

## Informações acadêmicas

**Instituição:** CEUB  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Disciplina:** Desenvolvimento Web  
**Turma / Semestre:** Turma A / 4º semestre  
**Professor:** Felippe Pires Ferreira  

---

## Sumário

- [1. Descrição do projeto](#1-descrição-do-projeto)
- [2. Funcionalidades](#2-funcionalidades)
- [3. Demonstração](#3-demonstração)
- [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
- [5. Arquitetura](#5-arquitetura)
- [6. Organização dos diretórios](#6-organização-dos-diretórios)
- [7. Participantes](#7-participantes)
- [8. Como executar](#8-como-executar)
- [9. Configuração](#9-configuração)
- [10. Testes](#10-testes)
- [11. Uso de inteligência artificial](#11-uso-de-inteligência-artificial)
- [12. Contribuição e fluxo de trabalho](#12-contribuição-e-fluxo-de-trabalho)
- [13. Histórico de versões](#13-histórico-de-versões)
- [14. Limitações e próximos passos](#14-limitações-e-próximos-passos)
- [15. Licença, referências e contato](#15-licença-referências-e-contato)

---

# 1. Descrição do projeto

O **Livro+** é uma aplicação web voltada ao gerenciamento de uma biblioteca, com o objetivo de organizar o acervo de livros e facilitar a interação dos leitores com os conteúdos disponíveis.

A proposta do sistema é centralizar informações sobre os livros, permitindo que os usuários pesquisem obras, visualizem seus detalhes, solicitem empréstimos e acompanhem suas atividades de leitura e empréstimos.

Para os responsáveis pela biblioteca, o sistema oferece recursos para gerenciamento do acervo e controle das movimentações, tornando o processo mais organizado e facilitando o acompanhamento dos empréstimos.

O projeto está sendo desenvolvido de forma incremental. Nesta primeira fase, foram definidos o contexto do sistema, os requisitos, os casos de uso, a arquitetura inicial, a identidade visual e os protótipos das principais telas.

## Objetivos

### Objetivo geral

Desenvolver uma aplicação web para gerenciamento de biblioteca, proporcionando uma experiência simples e organizada para leitores e administradores.

### Objetivos específicos

- Permitir a pesquisa e consulta de livros.
- Apresentar informações detalhadas sobre as obras.
- Permitir a solicitação e o acompanhamento de empréstimos.
- Permitir o registro e acompanhamento de leituras.
- Permitir avaliações dos livros.
- Possibilitar o gerenciamento do acervo por administradores.
- Registrar empréstimos e devoluções.
- Permitir a consulta do histórico de empréstimos.
- Integrar a aplicação com a Google Books API para consulta de informações sobre livros.
- Desenvolver uma interface simples, responsiva e consistente com a identidade visual definida para o projeto.

## Público-alvo

- Leitores e usuários da biblioteca.
- Administradores e bibliotecários responsáveis pelo acervo.
- Usuários interessados em pesquisar e acompanhar livros.

---


# 2. Funcionalidades

As funcionalidades abaixo fazem parte da proposta do sistema e serão implementadas ao longo do desenvolvimento.

| Funcionalidade | Descrição | Status |
|---|---|---|
| Pesquisar livros | Permitir a pesquisa de livros disponíveis no sistema | Planejada |
| Visualizar detalhes do livro | Exibir informações detalhadas sobre uma obra | Planejada |
| Solicitar empréstimo | Permitir que o leitor solicite um empréstimo | Planejada |
| Acompanhar empréstimos | Permitir o acompanhamento dos empréstimos realizados | Planejada |
| Registrar avaliação | Permitir que o leitor registre uma avaliação | Planejada |
| Acompanhar leituras | Permitir o acompanhamento do histórico de leituras | Planejada |
| Cadastrar livro | Permitir ao administrador cadastrar novos livros | Planejada |
| Editar livro | Permitir alterações nas informações de um livro | Planejada |
| Excluir livro | Permitir a remoção de livros do acervo | Planejada |
| Consultar acervo | Permitir ao administrador consultar o acervo completo | Planejada |
| Registrar empréstimo | Registrar os empréstimos realizados | Planejada |
| Registrar devolução | Registrar a devolução de livros | Planejada |
| Consultar empréstimos | Permitir a consulta dos empréstimos registrados | Planejada |
| Gerar relatório de empréstimos | Permitir a consulta organizada das movimentações | Planejada |
| Consultar Google Books API | Buscar informações de livros por meio da API | Planejada |

## Requisitos não funcionais

- **Usabilidade:** a interface deve ser simples e intuitiva.
- **Responsividade:** o sistema deverá se adaptar a diferentes tamanhos de tela.
- **Desempenho:** as consultas devem apresentar respostas adequadas ao uso normal da aplicação.
- **Segurança:** informações de usuários e demais dados sensíveis deverão ser protegidos.
- **Manutenibilidade:** o código deverá ser organizado de forma a facilitar futuras alterações.
- **Consistência visual:** as telas deverão seguir a identidade visual definida para o Livro+.

---

## 3. Demonstração

*Inclua capturas de tela, GIF ou link para vídeo. Coloque as imagens em `images/`.*

![Tela principal](images/[screenshot-principal].png)

| Tela | Descrição |
| --- | --- |
| [Login] | [Acesso ao sistema com e-mail e senha] |
| [Painel] | [Visão geral das reservas do dia] |

**Vídeo / protótipo:** [URL do YouTube, Loom ou Figma]

---

# 4. Tecnologias utilizadas

As tecnologias previstas para o desenvolvimento do projeto são:

| Camada | Tecnologia | Finalidade |
|---|---|---|
| Backend | Python | Desenvolvimento da lógica da aplicação |
| Framework | Django | Estruturação da aplicação web |
| API | Django REST Framework | Desenvolvimento da API REST |
| Frontend | HTML, CSS e JavaScript | Construção e estilização da interface |
| Banco de dados | SQLite | Persistência inicial dos dados |
| API externa | Google Books API | Consulta de informações sobre livros |
| Modelagem | PlantUML | Criação dos diagramas do sistema |
| Versionamento | Git / GitHub | Controle de versões e organização do projeto |
| Prototipação | Ferramenta de prototipação | Criação dos protótipos das telas |

As tecnologias serão utilizadas de acordo com as necessidades de cada etapa do desenvolvimento. A implementação dessas tecnologias será realizada nas próximas fases do projeto.

---

# 5. Arquitetura

O Livro+ será desenvolvido como uma aplicação web utilizando o Django como framework principal. A arquitetura foi planejada de forma a separar a interface, as regras de negócio, a persistência dos dados e as integrações externas.

O fluxo geral previsto para o sistema é:

```text
[Usuário / Leitor]
        |
        v
[Interface Web]
        |
        v
[Django / Backend]
        |
        +--------------------+
        |                    |
        v                    v
[Banco de Dados]     [Google Books API]

*# 5. Decisões relevantes

Durante a definição do projeto, foram tomadas algumas decisões relacionadas à tecnologia, arquitetura, funcionalidades e experiência do usuário.

| Decisão | Justificativa |
|---|---|
| Utilização do Django | Framework escolhido para estruturar o desenvolvimento da aplicação web e organizar a lógica do sistema. |
| Utilização de Python | Linguagem prevista para o desenvolvimento do backend da aplicação. |
| Integração com a Google Books API | Permitir a consulta de informações sobre livros e complementar os dados disponíveis no sistema. |
| Separação entre frontend e backend | Facilitar a organização, manutenção e evolução da aplicação. |
| Desenvolvimento de uma aplicação web | Permitir acesso ao sistema por diferentes dispositivos através de um navegador. |
| Definição de diferentes perfis de usuário | Separar as funcionalidades destinadas aos leitores das funcionalidades administrativas da biblioteca. |
| Criação de identidade visual própria | Garantir uma interface consistente e facilitar a identificação do projeto Livro+. |
| Desenvolvimento de protótipos antes da implementação | Permitir validar a estrutura e a organização das principais telas antes da etapa de desenvolvimento. |
| Utilização do GitHub | Facilitar o controle de versões, organização dos arquivos e acompanhamento da evolução do projeto. |
| Desenvolvimento incremental | Permitir que o sistema seja construído em etapas, começando pela documentação, modelagem e prototipação. |

---

## 6. Organização dos diretórios

*Mantenha a árvore alinhada à estrutura real do repositório. Ajuste pastas conforme o tipo de projeto.*

```text
.
├── README.md                 # Documentação principal do projeto
├── .env.example              # Modelo de variáveis de ambiente (sem segredos)
├── docs/                     # Modelagem e demais artefatos técnicos (PDF)
│   ├── README.pdf            # Índice da pasta docs/
│   └── modelagem/
│       ├── casos-de-uso/
│       │   └── especificacoes-casos-de-uso.pdf
│       ├── classes/
│       │   └── diagrama-de-classes.pdf
│       └── banco-de-dados/
│           ├── diagrama-er.pdf
│           └── modelo-logico.pdf
├── images/                   # Figuras da documentação geral (ex.: política de IA)
├── src/                      # Código-fonte da aplicação
│   ├── frontend/             # Interface com o usuário (quando houver)
│   └── backend/              # Regras de negócio, API e acesso a dados (quando houver)
├── tests/                    # Testes automatizados
└── scripts/                  # Scripts auxiliares de setup, build ou deploy
```

| Diretório / arquivo | Função |
| --- | --- |
| `README.md` | Apresentação do projeto, objetivos, tecnologias e instruções de uso |
| `.env.example` | Lista das variáveis necessárias, sem credenciais reais |
| `docs/` | Artefatos de análise e modelagem em PDF |
| `docs/modelagem/` | Casos de uso, classes e modelo de dados (diagramas embutidos nos PDFs) |
| `images/` | Figuras da documentação geral do repositório (não usar para diagramas de modelagem) |
| `src/` | Código-fonte organizado por camada ou módulo |
| `tests/` | Casos de teste e evidências de verificação |
| `scripts/` | Automação de ambiente e execução |

---

## 7. Participantes

*Informe nome completo, função no grupo e, se houver, o identificador acadêmico (matrícula).*

| Nome | Matrícula | Função no projeto |
| --- | --- | --- |
| [Nome completo] | [000000] | [Ex.: coordenação / backend / frontend / testes / documentação] |
| [Nome completo] | [000000] | [Ex.: backend] |
| [Nome completo] | [000000] | [Ex.: frontend] |
| [Nome completo] | [000000] | [Ex.: testes e documentação] |

**Professor(a) responsável:** [Nome completo]

---

## 8. Como executar

*Preencha com os comandos reais do projeto para que outra pessoa consiga reproduzir o ambiente.*

### Pré-requisitos

- [Ex.: Git]
- [Ex.: Python 3.12+]
- [Ex.: Node.js 20+]
- [Ex.: Docker]

### Instalação e execução

```bash
# 1. Clonar o repositório
git clone [URL_DO_REPOSITORIO]
cd [NOME_DA_PASTA]

# 2. Instalar dependências
[comando de instalação]

# 3. Configurar variáveis de ambiente
cp .env.example .env
# edite o arquivo .env com as credenciais locais

# 4. Executar a aplicação
[comando de execução]
```

**Acesso local:** [Ex.: http://localhost:3000]

### Implantação (quando houver)

- **Ambiente:** [Ex.: Render, Railway, Vercel, servidor da instituição]
- **URL de produção:** [https://...]
- **Observações:** [Ex.: é necessário configurar as variáveis de ambiente no painel do provedor]

---

## 9. Configuração

*Liste as variáveis de ambiente usadas pelo sistema. Nunca publique senhas, tokens ou chaves neste arquivo.*

| Variável | Obrigatória | Descrição | Exemplo |
| --- | --- | --- | --- |
| `PORT` | Sim | Porta da aplicação | `3000` |
| `DATABASE_URL` | Sim | Conexão com o banco | `postgresql://user:senha@localhost:5432/app` |
| `SECRET_KEY` | Sim | Chave de sessão / JWT | `[gerar localmente]` |

Credenciais reais devem ficar apenas no arquivo `.env` (não versionado).

---

## 10. Testes

*Descreva como executar os testes e o que eles cobrem.*

```bash
[comando para executar os testes]
```

| Tipo | Ferramenta | O que verifica |
| --- | --- | --- |
| Unitários | [Ex.: pytest / JUnit / Jest] | [Ex.: regras de negócio isoladas] |
| Integração | [Ex.: ...] | [Ex.: API e banco de dados] |
| Manuais | [Ex.: checklist em `docs/`] | [Ex.: fluxos principais da interface] |

**Cobertura atual:** [Ex.: 70% / não medida]

---

## 11. Uso de inteligência artificial

Este repositório segue a política de uso de IA da disciplina (semáforo pedagógico):

![Política de uso de IA — semáforo](images/semaforo.png)

| Situação | Significado |
| --- | --- |
| **Vermelho — uso proibido** | Atividades de autonomia intelectual (ex.: provas presenciais sem consulta). |
| **Amarelo — uso limitado** | IA pode ser ferramenta auxiliar, desde que haja declaração de uso. |
| **Verde — uso permitido** | Uso livre ao longo da atividade acadêmica. |

### Declaração de uso

*Preencha de forma honesta. Se não houve uso de IA, declare explicitamente.*

- **Houve uso de IA neste projeto?** [Sim / Não]
- **Ferramentas utilizadas:** [Ex.: ChatGPT, GitHub Copilot, Gemini — ou “nenhuma”]
- **Finalidade:** [Ex.: revisão de texto, geração de esboço de testes, esclarecimento de dúvidas de sintaxe]
- **O que NÃO foi delegado à IA:** [Ex.: definição do problema, modelagem, implementação das regras de negócio, testes finais]

---

## 12. Contribuição e fluxo de trabalho

*Padronize o trabalho em equipe. Ajuste as regras ao combinado da disciplina.*

### Branches

- `main` — versão estável para avaliação
- `develop` — integração do grupo *(opcional)*
- `feat/[nome]` — nova funcionalidade
- `fix/[nome]` — correção de defeito
- `docs/[nome]` — alterações só de documentação

### Commits

Use mensagens curtas e no imperativo, por exemplo:

- `feat: adiciona cadastro de reservas`
- `fix: corrige validação de data`
- `docs: atualiza instruções de execução`

### Passos sugeridos

1. Criar uma branch a partir de `main`.
2. Implementar e testar localmente.
3. Abrir um *pull request* / *merge request* para revisão do grupo.
4. Só então integrar à branch principal.

**Issues e quadro de tarefas:** [link do GitHub Projects, Trello ou similar]

---

## 13. Histórico de versões

*Registre entregas relevantes (sprints, checkpoints ou versões avaliadas).*

| Versão | Data | Descrição |
| --- | --- | --- |
| `0.1.0` | [AAAA-MM-DD] | [Ex.: primeira versão executável / MVP] |
| `0.0.1` | [AAAA-MM-DD] | [Ex.: estrutura inicial do repositório] |

---

## 14. Limitações e próximos passos

### Problemas conhecidos

- [Ex.: a recuperação de senha ainda não envia e-mail]
- [Ex.: o layout quebra em telas menores que 360 px]

### Roadmap

- [ ] [Ex.: autenticação com dois fatores]
- [ ] [Ex.: exportação de relatórios em CSV]
- [ ] [Ex.: implantação em ambiente de homologação]

---

## 15. Licença, referências e contato

**Licença:** [Ex.: uso exclusivamente acadêmico / MIT / outro]

Este material destina-se a fins educacionais. Verifique com a disciplina se o código pode ser reutilizado fora do curso.

### Documentação complementar

- Índice da pasta `docs/`: [`docs/README.pdf`](docs/README.pdf)
- Casos de uso (diagrama + especificações): [`docs/modelagem/casos-de-uso/especificacoes-casos-de-uso.pdf`](docs/modelagem/casos-de-uso/especificacoes-casos-de-uso.pdf)
- Diagrama de classes: [`docs/modelagem/classes/diagrama-de-classes.pdf`](docs/modelagem/classes/diagrama-de-classes.pdf)
- Modelo conceitual (ER): [`docs/modelagem/banco-de-dados/diagrama-er.pdf`](docs/modelagem/banco-de-dados/diagrama-er.pdf)
- Modelo lógico: [`docs/modelagem/banco-de-dados/modelo-logico.pdf`](docs/modelagem/banco-de-dados/modelo-logico.pdf)
- Apresentação: [`docs/apresentacao.pdf`](docs/)

### Referências

- [Autor. Título. Ano. URL ou dados bibliográficos.]
- [Documentação oficial da tecnologia X.]

### Contato

Dúvidas sobre o projeto: [e-mail institucional do grupo ou issue no repositório]

**Agradecimentos:** [Ex.: professor(a), monitoria, materiais da disciplina]
