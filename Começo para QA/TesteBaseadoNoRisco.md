# Teste Baseado no Risco (Risk-Based Testing - RBT) - Resumo Completo

## O que é?
O **Teste Baseado no Risco (Risk-Based Testing)** é uma estratégia onde o planejamento e execução dos testes são **priorizados com base nos riscos identificados** no projeto.

O foco é testar primeiro as funcionalidades que representam maior **risco de falha**, **impacto no negócio** ou **probabilidade de ocorrer um problema**.

## Objetivo
- **Gerenciar riscos** e otimizar o esforço de teste.
- Focar nos **cenários mais críticos** e que geram mais impacto caso apresentem falhas.
- Tornar o processo de teste mais eficiente e direcionado.

## Como funciona?
1. Identificar e analisar riscos:
    - Impacto no negócio.
    - Probabilidade de falha.
    - Complexidade técnica.
    - Mudanças frequentes.
2. Priorizar os testes:
    - Alta prioridade para áreas de alto risco.
    - Menor esforço em áreas de baixo risco.
3. Planejar e executar os testes com base nessa priorização.
4. Monitorar riscos ao longo do projeto.

## Exemplos de risco
- Funcionalidade nova ou muito complexa.
- Áreas do sistema críticas para o negócio (ex: pagamento).
- Integrações com sistemas de terceiros.
- Funcionalidades com histórico de bugs.
- Falta de documentação.

## Vantagens
✅ Foco no que é mais importante para o cliente e para o negócio.  
✅ Melhor gestão do tempo e recursos de QA.  
✅ Redução de retrabalho e de bugs em produção.  
✅ Ajuda a tomada de decisão: quando há pouco tempo para testar, você sabe o que deve testar primeiro.

## Desvantagens
❌ Depende de uma boa análise de risco (se os riscos forem mal avaliados, pode haver falhas não testadas).  
❌ Requer colaboração e maturidade da equipe.

## Exemplos práticos
- Testar a funcionalidade de checkout de um e-commerce com mais profundidade do que o cadastro de perfil.
- Priorizar testes em um módulo que foi recentemente alterado.
- Dar foco a APIs externas críticas que podem afetar o funcionamento da aplicação.

---

## Relação com outros tipos de teste

O **Teste Baseado no Risco** não substitui testes funcionais, de caixa preta ou de regressão — ele ajuda a **priorizar** o que será testado **primeiro**.

| Tipo de abordagem             | Foco principal                  |
|-------------------------------|---------------------------------|
| Teste baseado no risco         | Priorização de testes            |
| Teste de caixa preta           | Comportamento externo            |
| Teste de caixa branca          | Lógica interna do código         |
| Teste de regressão             | Testar funcionalidades já existentes |

---

# Cenário Prático - Aplicando Teste Baseado no Risco (RBT)

## Contexto
Você é QA em um projeto de **e-commerce** que está para lançar uma nova versão do site com várias mudanças:

- Novo módulo de pagamento via PIX.
- Melhorias no carrinho de compras.
- Nova integração com fornecedor externo.
- Ajustes na página de perfil do usuário.

Como o prazo de entrega é curto, você precisa **priorizar os testes** com base nos riscos do projeto.

---

## Passo 1: Identificar Riscos

| Funcionalidade                       | Impacto no negócio  | Probabilidade de falha | Complexidade técnica | Nível de Risco |
|--------------------------------------|--------------------|-----------------------|----------------------|----------------|
| Checkout com novo pagamento PIX      | Muito alto         | Alta                  | Alta                  | **Crítico**    |
| Integração com fornecedor externo    | Alto               | Alta                  | Alta                  | **Crítico**    |
| Carrinho de compras (melhorias UI)   | Alto               | Média                 | Média                 | **Alto**       |
| Página de perfil do usuário          | Baixo              | Baixa                 | Baixa                 | **Baixo**      |

---

## Passo 2: Priorizar os testes

1️⃣ **Alta prioridade / primeiro a testar**:
- Checkout com pagamento PIX
- Integração com fornecedor externo

2️⃣ **Prioridade média**:
- Carrinho de compras

3️⃣ **Baixa prioridade / testar se houver tempo**:
- Página de perfil do usuário

---

## Passo 3: Planejar e executar

- **Testes exploratórios** e **funcionais completos** no checkout e integração.
- **Automação de testes de regressão** focada nas funcionalidades críticas.
- **Testes manuais** nas melhorias de UI (carrinho).
- **Smoke Test** básico no perfil de usuário.

---

## Conclusão

Aplicando **Risk-Based Testing**, você garante que as áreas **mais críticas para o negócio e mais propensas a falhas** sejam testadas com mais profundidade — mesmo em um cenário com pouco tempo ou poucos recursos.

---

## Dicas finais
✅ Faça reuniões com PO e Devs para entender o que tem mais risco.  
✅ Use uma planilha simples ou ferramenta de gestão de testes para mapear os riscos.  
✅ Sempre documente quais áreas foram priorizadas e testadas.

