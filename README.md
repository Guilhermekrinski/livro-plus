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

| a fazer na Fase 2

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
```

*# Decisões relevantes

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

### 6. Organização dos diretórios

A organização do repositório foi definida para separar a documentação, os artefatos de modelagem, os protótipos e os demais recursos do projeto.

```text
.
├── README.md
├── docs/
│   ├── api/
│   ├── design/
│   │   ├── prototipos/
│   │   └── identidade-visual.md
│   ├── modelagem/
│   ├── casos-de-uso.puml
│   └── documento-de-visao.md
└── images/
```

| Diretório / arquivo | Função |
|---|---|
| `README.md` | Documentação principal e apresentação do projeto |
| `docs/` | Organização dos documentos e artefatos técnicos |
| `docs/api/` | Documentação relacionada às APIs utilizadas no projeto |
| `docs/design/` | Documentação relacionada ao design e à identidade visual |
| `docs/design/prototipos/` | Armazenamento dos protótipos das principais telas |
| `docs/design/identidade-visual.md` | Documentação da identidade visual do Livro+ |
| `docs/modelagem/` | Artefatos relacionados à análise e modelagem do sistema |
| `docs/casos-de-uso.puml` | Diagrama de casos de uso desenvolvido em PlantUML |
| `docs/documento-de-visao.md` | Documento de visão e definição inicial do projeto |
| `images/` | Imagens e recursos visuais utilizados na documentação |

A estrutura poderá ser ampliada durante as próximas etapas de desenvolvimento, conforme novos componentes e documentos forem adicionados ao projeto.

---

## 7. Participantes

O projeto foi desenvolvido em equipe no contexto da disciplina de Desenvolvimento Web.

| Nome | Matrícula | Função no projeto |
|---|---:|---|
| Guilherme Eduardo Rodrigues Krinski | 22504358 | Responsável pela análise, documentação, modelagem, definição da arquitetura, identidade visual, prototipação, organização do repositório e desenvolvimento do projeto |
| Pedro Saldanha Santana | 22509813 | Apoio nas atividades do projeto e participação nas etapas definidas pela equipe |

**Professor responsável:** Felippe Pires Ferreira

---

## 8. Como executar

| A preencher na Fase 2

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

Nesta etapa do projeto, as configurações da aplicação estão sendo definidas para orientar a futura implementação do sistema.

As principais configurações previstas são:

| Configuração | Finalidade |
|---|---|
| Banco de dados | Armazenar os dados de usuários, livros, empréstimos, avaliações e demais informações do sistema |
| Google Books API | Consultar informações complementares sobre livros |
| Django | Estruturar o backend e as regras da aplicação |
| Variáveis de ambiente | Armazenar configurações e informações sensíveis de forma segura |

As credenciais da Google Books API, chaves de segurança e demais informações sensíveis não deverão ser armazenadas diretamente no repositório.

As instruções detalhadas de instalação e configuração serão adicionadas ao projeto durante a etapa de implementação.
---

## 10. Testes

| A preencher na Fase 2

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

- **Houve uso de IA neste projeto?** Sim 
- **Ferramentas utilizadas:** : ChatGPT, Gemini.
- **Finalidade:**: Apoio para consulta de documentação, esclarecimento de dúvidas pontuais de sintaxe e revisão gramatical/estrutural de texto.
- **O que NÃO foi delegado à IA:**: Toda a definição do projeto, arquitetura, lógica principal, implementação do código/regras de negócio e realização dos testes finais.

---

## 12. Contribuição e fluxo de trabalho

O projeto utiliza o GitHub para organização dos arquivos, controle de versões e acompanhamento da evolução do desenvolvimento.

### Branch principal

A branch `main` é utilizada como branch principal do projeto, concentrando a versão atual dos arquivos.

### Organização do trabalho

As atividades do projeto foram divididas entre os integrantes conforme as necessidades de cada etapa.

Guilherme Eduardo Rodrigues Krinski ficou responsável principalmente pela análise, documentação, modelagem, arquitetura, identidade visual, prototipação, organização do repositório e desenvolvimento do projeto.

Pedro Saldanha Santana participou como apoio nas atividades definidas pela equipe.

### Commits

Os commits são utilizados para registrar as alterações realizadas no projeto e acompanhar sua evolução.

Entre as principais alterações realizadas estão:

- Atualização da documentação;
- Criação do documento de visão;
- Adição dos diagramas de modelagem;
- Criação da identidade visual;
- Adição dos protótipos;
- Atualização do README;
- Organização dos diretórios do projeto.

### Fluxo de desenvolvimento

O desenvolvimento do Livro+ segue uma abordagem incremental, passando pelas seguintes etapas:

1. Definição do problema e contexto;
2. Documento de visão;
3. Modelagem do sistema;
4. Definição da arquitetura;
5. Identidade visual;
6. Prototipação;
7. Implementação;
8. Testes;
9. Ajustes e preparação para entrega.

---

## 13. Histórico de versões

O histórico de versões apresenta a evolução do projeto ao longo das etapas de desenvolvimento.

| Versão | Etapa | Descrição |
|---|---|---|
| `0.1.0` | Documentação e prototipação | Definição inicial do projeto, documento de visão, modelagem, arquitetura, identidade visual e protótipos |
| `0.0.1` | Estrutura inicial | Criação e organização inicial do repositório |

Novas versões serão adicionadas conforme o desenvolvimento e a implementação das funcionalidades do Livro+ avançarem.

---

## 14. Limitações e próximos passos

### Limitações atuais

O Livro+ encontra-se atualmente nas etapas de planejamento, documentação, modelagem e prototipação.

Nesta etapa, algumas funcionalidades ainda não foram implementadas, incluindo:

- Banco de dados da aplicação;
- Autenticação e controle de acesso;
- Gerenciamento completo do acervo;
- Sistema de empréstimos e devoluções;
- Registro de avaliações e acompanhamento de leituras;
- Integração com a Google Books API;
- Testes automatizados.

### Próximos passos

As próximas etapas previstas para o desenvolvimento do Livro+ são:

1. Configuração do ambiente de desenvolvimento;
2. Criação da estrutura inicial do projeto em Django;
3. Implementação do banco de dados;
4. Implementação da autenticação e dos perfis de usuário;
5. Desenvolvimento das funcionalidades do sistema;
6. Integração com a Google Books API;
7. Implementação das interfaces definidas nos protótipos;
8. Realização dos testes;
9. Correção de problemas e ajustes de usabilidade;
10. Preparação da versão final do sistema.

---

## 15. Licença, referências e contato

### Licença

Este projeto foi desenvolvido para fins acadêmicos na disciplina de Desenvolvimento Web do Centro Universitário de Brasília (CEUB).

### Documentação complementar

Os principais documentos e artefatos do projeto estão organizados na pasta `docs/`, incluindo:

- Documento de visão;
- Diagramas de modelagem;
- Identidade visual;
- Protótipos das telas;
- Documentos relacionados à arquitetura e ao planejamento do sistema.

### Referências

- Documentação oficial do Python;
- Documentação oficial do Django;
- Documentação da Google Books API;
- Documentação do GitHub;
- Materiais e orientações disponibilizados na disciplina de Desenvolvimento Web.

### Contato

**Guilherme Eduardo Rodrigues Krinski**  
**Matrícula:** 22504358  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Instituição:** CEUB  
**Disciplina:** Desenvolvimento Web  
**Professor:** Felippe Pires Ferreira
