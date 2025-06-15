# 🔺 Pirâmide de Testes - Guia com base no Syllabus CTFL (ISTQB)

## 📘 O que é a Pirâmide de Testes?

A **Pirâmide de Testes** é uma representação visual que ilustra a **proporção ideal entre diferentes tipos e níveis de teste** dentro de uma estratégia de testes bem equilibrada.

Ela enfatiza a importância de **ter mais testes automatizados de baixo nível (como testes de unidade)**, pois são mais rápidos, baratos e fáceis de manter, e **menos testes de alto nível (como testes manuais de UI e testes exploratórios)**, que tendem a ser mais caros e demorados.

---

## 🎯 Objetivo da Pirâmide de Testes

- Reduzir o custo dos testes
- Aumentar a confiabilidade do software
- Encontrar defeitos o mais cedo possível (shift-left)
- Promover uma base de testes sólida e sustentável

---

## 🧱 Estrutura da Pirâmide

A pirâmide é geralmente dividida em **três camadas principais**:

### 1. 🧪 Testes de Unidade (Base da pirâmide)
- **Responsável:** Desenvolvedores
- **Automatizado:** Sim
- **Frequência:** Altíssima
- **Cobertura:** Alta (linhas e funções)
- **Objetivo:** Verificar se funções, métodos e classes estão funcionando corretamente.
- **Ferramentas:** JUnit, NUnit, PyTest, Mocha

### 2. 🔄 Testes de Integração (Meio da pirâmide)
- **Responsável:** Devs e QAs
- **Automatizado:** Sim
- **Frequência:** Média/Alta
- **Cobertura:** Componentes e interfaces entre módulos
- **Objetivo:** Verificar se os módulos se comunicam corretamente.
- **Ferramentas:** Postman, RestAssured, Spring Test, TestNG

### 3. 🌐 Testes de Interface Gráfica (Topo da pirâmide)
- **Responsável:** QAs/Testadores
- **Automatizado ou manual**
- **Frequência:** Baixa (deve ser menor)
- **Cobertura:** Fluxos principais do usuário (E2E)
- **Objetivo:** Validar a experiência do usuário, aparência e comportamento da aplicação.
- **Ferramentas:** Selenium, Cypress, Playwright, Appium

---

## 📉 O Que Evitar (Anti-pattern: Ice Cream Cone 🍦)

- Muitos testes manuais no topo.
- Poucos testes de unidade e automação.
- Alta dependência de testes caros e demorados.
- Difícil de escalar e manter a qualidade do software.

---

## 📌 Relação com o Syllabus CTFL

De acordo com o **Syllabus CTFL**, os testes devem ser organizados por níveis e tipos:

### Níveis de Teste (CTFL):
- **Teste de Unidade (Component Testing)**
- **Teste de Integração**
- **Teste de Sistema**
- **Teste de Aceitação**

A Pirâmide está diretamente relacionada a esses níveis, especialmente nos testes de unidade e integração, onde a automação é mais eficaz.

---

## ⚖️ Boas Práticas segundo ISTQB

- **Automatize testes em níveis baixos (unitários e integração).**
- **Evite dependência excessiva de testes manuais E2E.**
- **Garanta que os testes sejam rápidos, confiáveis e executados com frequência.**
- **Use ferramentas de CI/CD para execução contínua.**
- **Mantenha a pirâmide balanceada com base no contexto do projeto.**

---

## 🧠 Conclusão

A Pirâmide de Testes ajuda equipes de QA e desenvolvimento a construírem uma **estratégia de testes sustentável**, **eficiente** e **econômica**, alinhada com os princípios do ISTQB e boas práticas ágeis.

> "Quanto mais cedo o defeito é encontrado, menor o custo para corrigi-lo."

---
