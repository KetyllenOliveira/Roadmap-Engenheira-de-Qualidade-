# TDD / BDD / ATDD

## TDD (Test-Driven Development) - Desenvolvimento Orientado a Testes

### O que é?
- Técnica de desenvolvimento onde os testes são escritos **antes** do código de produção.
- O ciclo é: 
  1. Escrever um teste que falha.
  2. Escrever o código necessário para passar o teste.
  3. Refatorar o código.
  4. Repetir.

### Objetivo
- Garantir que o código atenda aos requisitos desde o início.
- Produzir código mais limpo e fácil de manter.
- Aumentar a cobertura de testes unitários.

### Exemplo de ferramenta
- JUnit (Java), pytest (Python), Jest (JavaScript), NUnit (.NET)

---

## BDD (Behavior-Driven Development) - Desenvolvimento Orientado a Comportamento

### O que é?
- Evolução do TDD que foca nos comportamentos esperados pelo usuário.
- Utiliza uma linguagem natural (exemplo: Gherkin com *Given, When, Then*) que facilita a colaboração entre QA, Devs e POs.
- Testes são baseados em **exemplos de uso real do sistema**.

### Objetivo
- Alinhar o desenvolvimento com as necessidades de negócio.
- Tornar os testes compreensíveis para todas as partes interessadas.
- Melhorar a comunicação entre as equipes.

### Exemplo de ferramenta
- Cucumber, SpecFlow, Behave, Cypress + Cucumber Preprocessor

---

## ATDD (Acceptance Test-Driven Development) - Desenvolvimento Orientado a Testes de Aceitação

### O que é?
- Técnica onde os **testes de aceitação** (critérios de aceite) são definidos **antes** do desenvolvimento.
- QA, Devs e POs colaboram para escrever testes que validam que a funcionalidade atende às expectativas do cliente.

### Objetivo
- Garantir que o produto entregue realmente atenda aos requisitos do cliente.
- Focar nas funcionalidades que geram valor.
- Reduzir mal-entendidos sobre o que deve ser desenvolvido.

### Exemplo de ferramenta
- Cucumber, FitNesse, Robot Framework

---

## Resumindo

| Técnica | Foco principal | Quem participa |
|---------|----------------|----------------|
| TDD     | Qualidade do código (unitário) | Devs |
| BDD     | Comportamento e requisitos de negócio | Devs, QA, PO |
| ATDD    | Testes de aceitação do cliente | Devs, QA, PO, Cliente |
