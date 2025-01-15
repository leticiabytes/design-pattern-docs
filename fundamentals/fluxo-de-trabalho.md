# 🔀 Fluxo de Trabalho

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum posuere leo lorem, in auctor lacus interdum nec. Sed quis accumsan odio, sed accumsan libero. Etiam condimentum euismod orci quis pharetra.



**1. Git Flow**

* **Branches**:
  * `main`: Código pronto para produção.
  * `develop`: Código em desenvolvimento.
  * `feature/*`: Novas funcionalidades.
  * `fix/*`: Novas funcionalidades.
  *
* **Commits**: Use o padrão Conventional Commits:

```plaintext
feat (feature):

Usado para indicar a adição de uma nova funcionalidade.
Exemplo: feat: add user login functionality

fix:
Indica uma correção de bug.
Exemplo: fix: correct error handling in login service

chore:
Usado para mudanças que não afetam o código de produção, como atualizações de ferramentas, scripts de build ou configurações.
Exemplo: chore: update dependencies

style:
Para mudanças que afetam a formatação do código, como a correção de espaçamento, indentação, etc., sem alterar a lógica do código.
Exemplo: style: format code according to lint rules

refactor:
Para mudanças que alteram a estrutura do código sem alterar sua funcionalidade. Isso inclui melhorias na legibilidade ou otimizações.
Exemplo: refactor: simplify authentication logic

perf (performance):
Usado para melhorias de performance.
Exemplo: perf: improve query speed on user table

test:
Usado quando você adiciona ou modifica testes.
Exemplo: test: add tests for login service

docs (documentation):
Para mudanças na documentação, como README ou arquivos de guia.
Exemplo: docs: update API usage in README

build:
Usado para mudanças relacionadas ao sistema de build ou ferramentas externas, como Webpack, npm, etc.
Exemplo: build: configure webpack for production

ci:
Para mudanças no sistema de integração contínua (CI), como arquivos de configuração do GitHub Actions, Jenkins, etc.
Exemplo: ci: update CI config to run tests
```

**2. Pull Requests**

* Sempre crie uma descrição detalhada.
* Checklist de revisão:
  * O código está limpo e legível?
  * Foram realizados testes?

