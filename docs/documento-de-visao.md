# Documento de Visão — Livro+

## 1. Identificação do Projeto

**Nome do projeto:** Livro+
**Tema:** Biblioteca + Clube do Livro
**Tecnologias previstas:** Python e Django
**Tipo de aplicação:** Aplicação Web
**Etapa atual:** Fase 1 — Documentação e Arquitetura

---

## 2. Contexto e Problema

Bibliotecas necessitam de mecanismos eficientes para organizar seu acervo e controlar as movimentações dos livros. Em determinados contextos, a ausência de uma ferramenta centralizada pode dificultar a consulta da disponibilidade dos exemplares, o registro de empréstimos e devoluções e o acompanhamento das informações relacionadas às leituras.

Para os leitores, também pode existir dificuldade em localizar livros, consultar suas informações e acompanhar o próprio histórico de leitura. Além disso, a ausência de recursos de avaliação pode limitar a interação dos usuários com o acervo.

Nesse contexto, o **Livro+** propõe uma aplicação web voltada ao gerenciamento de uma biblioteca, combinando funcionalidades administrativas com recursos destinados aos leitores. A aplicação deverá centralizar informações sobre o acervo, empréstimos, devoluções, avaliações e acompanhamento das leituras.

---

## 3. Justificativa

O desenvolvimento do Livro+ justifica-se pela necessidade de proporcionar uma forma mais organizada e centralizada de gerenciamento de uma biblioteca, reduzindo dificuldades relacionadas ao controle do acervo e dos empréstimos.

A aplicação também busca melhorar a experiência dos leitores ao disponibilizar recursos para pesquisa e consulta de livros, solicitação de empréstimos, avaliação das obras e acompanhamento das leituras.

Do ponto de vista acadêmico, o projeto possibilita a aplicação prática dos conhecimentos da disciplina de **Desenvolvimento Web**, especialmente no desenvolvimento futuro de uma aplicação utilizando Python e Django, além de possibilitar a integração com uma API externa para complementar informações relacionadas aos livros.

---

## 4. Objetivo Geral

Desenvolver uma aplicação web denominada **Livro+**, destinada a centralizar o gerenciamento de uma biblioteca e oferecer recursos aos leitores, permitindo organizar o acervo, controlar empréstimos e devoluções, facilitar a busca por livros e acompanhar e avaliar leituras.

---

## 5. Objetivos Específicos

* Permitir o cadastro de livros no acervo da biblioteca.
* Permitir a edição e exclusão das informações dos livros.
* Disponibilizar a consulta do acervo.
* Permitir a pesquisa de livros pelos leitores.
* Exibir informações relacionadas aos livros.
* Registrar empréstimos e devoluções.
* Permitir a consulta da disponibilidade dos livros.
* Permitir que leitores realizem ou solicitem empréstimos.
* Permitir que leitores avaliem livros.
* Permitir que leitores acompanhem livros que estão lendo ou já leram.
* Disponibilizar informações e relatórios relacionados aos empréstimos.
* Permitir filtros de relatórios por período.
* Utilizar a **Google Books API** para buscar ou complementar informações dos livros.
* Centralizar as principais informações relacionadas ao acervo e às atividades de empréstimo.

---

## 6. Público-Alvo

O sistema terá dois públicos principais:

### 6.1 Administrador/Bibliotecário

Responsável pelo gerenciamento do acervo e pelo controle das operações da biblioteca. Entre suas principais atividades estão o cadastro, edição, exclusão e consulta de livros, além do registro e acompanhamento de empréstimos e devoluções.

### 6.2 Usuário/Leitor

Pessoa que utiliza a aplicação para consultar o catálogo, pesquisar livros, visualizar informações, realizar ou solicitar empréstimos, avaliar obras e acompanhar suas leituras.

---

## 7. Stakeholders

Os principais stakeholders identificados para o projeto são:

| Stakeholder                     | Interesse no projeto                                                                  |
| ------------------------------- | ------------------------------------------------------------------------------------- |
| **Administrador/Bibliotecário** | Gerenciar o acervo e controlar empréstimos e devoluções.                              |
| **Usuário/Leitor**              | Pesquisar livros, realizar ou solicitar empréstimos e acompanhar suas leituras.       |
| **Professor da disciplina**     | Avaliar o desenvolvimento do projeto conforme os requisitos acadêmicos estabelecidos. |
| **Equipe de desenvolvimento**   | Projetar, documentar e posteriormente desenvolver a aplicação.                        |
| **Google Books API**            | Fornecer informações externas que poderão complementar os dados dos livros.           |

---

## 8. Escopo

O escopo do Livro+ compreende o desenvolvimento de uma aplicação web para gerenciamento de uma biblioteca e disponibilização de funcionalidades voltadas aos leitores.

### 8.1 Escopo para Administrador/Bibliotecário

A aplicação deverá permitir ao administrador/bibliotecário:

* cadastrar livros;
* editar livros;
* excluir livros;
* consultar o acervo;
* registrar empréstimos;
* registrar devoluções;
* consultar quais livros estão disponíveis;
* consultar quais livros estão emprestados;
* acessar informações relacionadas aos empréstimos;
* consultar relatórios de empréstimos;
* visualizar a quantidade de livros emprestados;
* visualizar a quantidade de livros disponíveis;
* consultar livros atualmente emprestados;
* consultar o período dos empréstimos;
* aplicar filtros por período nos relatórios.

### 8.2 Escopo para Usuário/Leitor

A aplicação deverá permitir ao usuário/leitor:

* pesquisar livros;
* consultar o catálogo;
* visualizar informações dos livros;
* realizar ou solicitar empréstimos;
* avaliar livros;
* acompanhar livros que está lendo;
* acompanhar livros que já leu.

### 8.3 Integração externa

O projeto também contempla a integração com a **Google Books API**, que será utilizada para buscar ou complementar informações dos livros, como:

* título;
* autor;
* capa;
* outras informações disponibilizadas pela API.

A integração deverá estar associada a uma funcionalidade real da aplicação, contribuindo para a consulta ou complementação das informações do acervo.

---

## 9. Itens Fora do Escopo

Nesta versão inicial do projeto, não fazem parte do escopo:

* desenvolvimento de aplicativo mobile nativo;
* integração com outras APIs externas além da Google Books API;
* sistema de pagamento;
* venda de livros;
* gerenciamento financeiro da biblioteca;
* controle de estoque de materiais que não sejam livros;
* funcionalidades de redes sociais;
* chat ou comunicação em tempo real entre usuários;
* sistema de notificações por SMS;
* integração com serviços de entrega;
* funcionalidades que não estejam relacionadas ao gerenciamento do acervo, empréstimos, avaliações ou acompanhamento das leituras.

Esses itens poderão ser considerados em versões futuras, caso haja necessidade e disponibilidade de tempo, mas não fazem parte dos objetivos definidos para a versão inicial.

---

## 10. Funcionalidades

As funcionalidades previstas para o Livro+ estão organizadas de acordo com o perfil de acesso.

### 10.1 Gerenciamento de livros

* Cadastro de livros.
* Edição de livros.
* Exclusão de livros.
* Consulta do acervo.
* Consulta das informações dos livros.
* Identificação da disponibilidade dos livros.

### 10.2 Empréstimos e devoluções

* Registro de empréstimos.
* Registro de devoluções.
* Realização ou solicitação de empréstimos pelo leitor.
* Consulta dos livros atualmente emprestados.
* Acompanhamento do período dos empréstimos.

### 10.3 Pesquisa e catálogo

* Pesquisa de livros.
* Visualização do catálogo.
* Visualização das informações de cada livro.
* Consulta da disponibilidade.

### 10.4 Avaliações e leituras

* Avaliação de livros pelos leitores.
* Acompanhamento dos livros que estão sendo lidos.
* Acompanhamento dos livros já lidos.

### 10.5 Relatórios

O sistema deverá disponibilizar informações relacionadas aos empréstimos, incluindo:

* quantidade de livros emprestados;
* quantidade de livros disponíveis;
* livros atualmente emprestados;
* período dos empréstimos;
* filtros por período.

### 10.6 Integração com a Google Books API

A aplicação deverá utilizar a Google Books API como fonte externa para buscar ou complementar informações dos livros. A integração deverá possibilitar o aproveitamento de informações disponíveis externamente, evitando a necessidade de cadastrar manualmente todas as informações de uma obra quando esses dados puderem ser obtidos pela API.

---

## 11. Restrições

O projeto possui as seguintes restrições iniciais:

* A aplicação será desenvolvida posteriormente utilizando **Python e Django**.
* O sistema deverá utilizar um banco de dados relacional.
* O projeto deverá possuir uma API REST própria relacionada aos recursos definidos para a aplicação.
* A aplicação deverá realizar integração com a **Google Books API**.
* A primeira fase do projeto é destinada à documentação e definição da solução, não contemplando a implementação do sistema.
* O desenvolvimento deverá respeitar os requisitos acadêmicos definidos para a disciplina de Desenvolvimento Web.
* A disponibilidade e o funcionamento da Google Books API poderão limitar a quantidade e o tipo de informações externas disponíveis para consulta.

---

## 12. Premissas

Para o desenvolvimento do projeto, são consideradas as seguintes premissas:

* Os usuários terão acesso à aplicação por meio de um navegador web.
* Existirão dois perfis principais de utilização: administrador/bibliotecário e usuário/leitor.
* O administrador/bibliotecário será responsável pelo gerenciamento das informações do acervo e pelo controle dos empréstimos e devoluções.
* Os leitores utilizarão o sistema principalmente para consultar livros, realizar ou solicitar empréstimos, avaliar obras e acompanhar suas leituras.
* As informações dos livros poderão ser obtidas ou complementadas por meio da Google Books API.
* O banco de dados relacional será utilizado para armazenar as informações necessárias ao funcionamento da aplicação.
* O sistema dependerá de acesso à internet para utilizar os recursos disponibilizados pela API externa.
* As funcionalidades poderão ser refinadas durante as etapas posteriores do projeto, desde que permaneçam coerentes com o objetivo geral e com o escopo definido.

---

## 13. Riscos Iniciais

Durante o desenvolvimento do projeto, alguns riscos iniciais foram identificados:

### 13.1 Dependência da API externa

A disponibilidade, estabilidade ou alterações na Google Books API podem afetar a obtenção de informações externas utilizadas pela aplicação.

**Impacto:** dificuldade ou indisponibilidade temporária para buscar ou complementar informações dos livros.

### 13.2 Complexidade do desenvolvimento

A implementação posterior da aplicação poderá apresentar desafios relacionados à integração entre as diferentes funcionalidades do sistema.

**Impacto:** aumento do tempo necessário para desenvolvimento e testes.

### 13.3 Consistência das informações

As informações obtidas por meio da API externa podem apresentar diferenças em relação aos dados cadastrados no sistema.

**Impacto:** necessidade de definir posteriormente como os dados externos serão utilizados ou complementados.

### 13.4 Limitação de tempo acadêmico

O projeto está condicionado ao período disponível para realização das atividades da disciplina.

**Impacto:** necessidade de priorização das funcionalidades essenciais caso o tempo disponível seja reduzido.

### 13.5 Alterações no escopo

A inclusão de novas funcionalidades durante o desenvolvimento pode aumentar a complexidade do projeto.

**Impacto:** atraso nas entregas e dificuldade para manter o foco nos requisitos inicialmente definidos.

---

## 14. Critérios de Sucesso

O projeto será considerado bem-sucedido quando atender aos principais objetivos definidos para a aplicação e aos requisitos estabelecidos para a disciplina.

São considerados critérios de sucesso:

* O sistema possuir uma proposta clara de gerenciamento de biblioteca e clube do livro.
* O administrador/bibliotecário conseguir gerenciar o acervo de livros.
* Ser possível registrar e consultar empréstimos e devoluções.
* Ser possível identificar livros disponíveis e emprestados.
* O leitor conseguir pesquisar e visualizar informações dos livros.
* O leitor conseguir realizar ou solicitar empréstimos.
* O leitor conseguir avaliar livros.
* O leitor conseguir acompanhar livros que está lendo ou já leu.
* Os relatórios apresentarem informações relacionadas aos empréstimos e permitirem filtros por período.
* A aplicação utilizar a Google Books API para buscar ou complementar informações dos livros em uma funcionalidade real.
* A solução permanecer coerente com o objetivo de centralizar o gerenciamento da biblioteca e melhorar a experiência dos leitores.
* A documentação produzida na Fase 1 apresentar de forma clara a visão e os objetivos do projeto.
* As funcionalidades implementadas posteriormente estiverem alinhadas ao escopo definido neste Documento de Visão.

---

## 15. Considerações Finais

O **Livro+** tem como proposta centralizar o gerenciamento de uma biblioteca e, simultaneamente, oferecer aos leitores recursos que facilitem a pesquisa, o empréstimo, a avaliação e o acompanhamento de suas leituras.

A primeira fase do projeto estabelece a visão geral da aplicação, seus objetivos, público-alvo, stakeholders, escopo, restrições, premissas, riscos e critérios de sucesso. Essa definição servirá como base para as etapas posteriores do projeto, mantendo o desenvolvimento alinhado às necessidades identificadas e aos requisitos acadêmicos da disciplina.
