# Teste de Caixa Preta (Black Box Testing)

## O que é?
O **Teste de Caixa Preta** é uma técnica de teste de software onde o testador **não tem conhecimento do código-fonte ou da estrutura interna** do sistema. O foco está em verificar se o sistema **funciona corretamente a partir da perspectiva do usuário final**, validando entradas e saídas.

## Objetivo
- Garantir que o sistema atenda aos **requisitos funcionais** e **não funcionais**.
- Detectar **falhas de funcionalidade**, como:
  - Comportamento incorreto em entradas válidas.
  - Respostas inadequadas a entradas inválidas.
  - Problemas de usabilidade, desempenho, ou segurança.

## Como funciona?
- O testador fornece **entradas específicas** e analisa as **saídas** produzidas, sem se preocupar com como o sistema processa internamente essas informações.
- Baseado em **casos de uso**, **histórias de usuário**, ou **requisitos do sistema**.

## Técnicas Comuns
- **Particionamento de Equivalência**
- **Análise do Valor Limite**
- **Tabela de Decisão**
- **Testes de Transição de Estado**
- **Testes Baseados em Casos de Uso**

## Vantagens
✅ Foca no comportamento do sistema como o usuário enxerga.  
✅ Ideal para validar se os requisitos estão sendo cumpridos.  
✅ Pode ser feito por QAs sem conhecimento técnico profundo.

## Desvantagens
❌ Não detecta erros na lógica interna do código.  
❌ Pode ter cobertura limitada sem uma boa análise de requisitos.  

## Exemplos de Teste de Caixa Preta
- Testar um campo de login: informar usuário/senha e verificar se o login é aceito ou rejeitado.  
- Testar um formulário: preencher os campos e ver se os dados são salvos corretamente.  
- Testar um botão: clicar e verificar se executa a ação esperada.

---

## Comparação com Caixa Branca

| Característica         | Caixa Preta                | Caixa Branca                  |
|------------------------|----------------------------|-------------------------------|
| Conhecimento interno   | Não necessário             | Necessário                    |
| Foco                   | Comportamento externo      | Lógica e estrutura do código  |
| Quem realiza           | QA, Testador, Cliente      | Dev, QA técnico               |
| Exemplos               | Teste funcional, UI, API   | Teste unitário, cobertura     |

---

Se quiser, posso te explicar o **Teste de Caixa Branca** também ou montar um fluxograma mostrando como as técnicas se complementam no ciclo de testes!
