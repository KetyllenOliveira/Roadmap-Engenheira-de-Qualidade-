# Teste de Caixa Branca

## O que é?
O **Teste de Caixa Branca** (também conhecido como Glass Box Testing, Structural Testing, Clear Box Testing) é uma técnica de teste de software onde o testador **tem conhecimento da estrutura interna do código** e dos algoritmos.

O foco está em validar a **lógica interna**, **fluxos de controle**, e **estruturas de dados** do sistema.

## Objetivo
- Verificar a **correção da lógica do código**.
- Assegurar que **todas as rotas** do código sejam testadas.
- Garantir que estruturas como **loops, condições, branches e exceções** estejam funcionando conforme esperado.

## Como funciona?
- O testador analisa o código-fonte para projetar casos de teste.
- Executa os testes visando cobrir:
  - **Caminhos do código**
  - **Decisões lógicas**
  - **Condições**
  - **Laços de repetição**
  - **Tratamento de erros**

## Tipos de cobertura
- **Cobertura de instruções**: cada linha do código deve ser executada.
- **Cobertura de decisões/branches**: cada decisão (if/else, switch, etc.) deve ser tomada em todas as possibilidades.
- **Cobertura de caminhos**: todos os caminhos possíveis devem ser percorridos.

## Ferramentas comuns
- JUnit (Java)
- pytest (Python)
- Jest (JavaScript)
- NUnit (.NET)
- Ferramentas de cobertura de código: JaCoCo, Istanbul, Clover.

## Vantagens
✅ Identifica bugs ocultos na lógica interna.  
✅ Garante maior **cobertura de código**.  
✅ Ajuda na otimização e refatoração do código.

## Desvantagens
❌ Exige conhecimento técnico e do código.  
❌ Não valida se o sistema atende aos requisitos do usuário (foco é no código, não no comportamento).  

## Exemplos de Teste de Caixa Branca
- Testar algoritmos de ordenação, verificando se funcionam corretamente para todos os casos.
- Garantir que loops executem corretamente para todos os valores de entrada.
- Validar fluxos condicionais com todos os tipos de entrada.

---

## Comparação: Caixa Preta vs Caixa Branca

| Característica         | Caixa Preta                  | Caixa Branca                |
|------------------------|------------------------------|-----------------------------|
| Conhecimento interno   | Não necessário               | Necessário                  |
| Foco                   | Requisitos e comportamento   | Lógica e estrutura do código |
| Quem realiza           | QA, Testador, Cliente        | Dev, QA técnico             |
| Tipo de teste comum    | Funcional, UI, API           | Unitário, integração        |

---
