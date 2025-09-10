# 📘Pensamento Computacional

## 🔹 Apresentação
- O pensamento computacional é uma **forma de raciocínio** usada para resolver problemas de maneira estruturada.  
- Ele não serve apenas para programadores: pode ser aplicado na vida real, em estudos e no trabalho.  

---

## 🔹 Introdução
- É a habilidade de **organizar ideias, criar estratégias e aplicar lógica** para chegar a soluções.  
- Pode ser utilizado para problemas simples (como organizar tarefas do dia) ou complexos (como desenvolver um software).  

---

## 🔹 Habilidades complementares
- **Criatividade**: pensar em soluções inovadoras.  
- **Colaboração**: trabalhar em equipe para resolver problemas.  
- **Comunicação**: explicar claramente ideias e soluções.  
- **Persistência**: aprender com erros, ajustar e tentar de novo.  

---

## 🔹 Pilares do Pensamento Computacional

### 1. Decomposição
- **Dividir problemas grandes em partes menores**.  
- Exemplo: Ao organizar uma festa, dividir em: lista de convidados, comida, música, decoração.

### 2. Padrões
- **Encontrar semelhanças e repetições**.  
- Exemplo: Muitos sites pedem os mesmos dados para cadastro (nome, e-mail, senha).

### 3. Abstração
- **Ignorar detalhes irrelevantes** e focar no essencial.  
- Exemplo: Um mapa de metrô mostra só as linhas e estações, não cada prédio da cidade.

### 4. Algoritmos
- **Passos lógicos e ordenados** para resolver um problema.  
- Exemplo: Receita de bolo → ingredientes + modo de preparo em ordem.

---

## 🔹 Estudos de Caso

### 1. Estudo de caso conceitual: **Perdido**
- Situação: Você está em uma cidade desconhecida e precisa achar o caminho de volta para casa.  
- Aplicação dos pilares:  
  - **Decomposição**: definir etapas (perguntar informações, olhar placas, usar GPS).  
  - **Padrões**: reconhecer pontos repetidos (praça, avenida principal).  
  - **Abstração**: focar apenas nos marcos importantes (sem se perder em ruas pequenas).  
  - **Algoritmo**: criar uma sequência de passos até o destino.  

---

### 2. Estudo de caso aplicado: **Soma de um intervalo**
- **Problema**: Dada uma faixa de números, calcular a soma total.  
- Exemplo: Somar todos os números de **1 até 10**.  
  - Método tradicional: 1 + 2 + 3 + ... + 10 = 55.  
  - Com algoritmo: usar a fórmula da soma de uma progressão aritmética →  
    \[
    \text{Soma} = \frac{n \cdot (a_1 + a_n)}{2}
    \]  
    Onde:  
    - \(n\) = quantidade de números  
    - \(a_1\) = primeiro número  
    - \(a_n\) = último número  

  - Para 1 até 10:  
    \[
    Soma = \frac{10 \cdot (1 + 10)}{2} = 55
    \]  

- **Lógica computacional**: ao invés de somar número por número, criamos um **algoritmo eficiente** que resolve qualquer intervalo.

---

### 3. Estudo de caso aplicado: **Adivinhe um número**
- **Problema**: O computador escolhe um número secreto, e o jogador tenta adivinhar.  
- Exemplo: Número secreto entre **1 e 100**.  
- Estratégias possíveis:  

  1. **Chutar aleatoriamente**  
     - Pouco eficiente, pode demorar muito.  

  2. **Tentar em ordem** (1, 2, 3...)  
     - Também ineficiente, pode exigir até 100 tentativas.  

  3. **Busca binária (algoritmo eficiente)**  
     - Sempre dividir o intervalo pela metade.  
     - Exemplo:  
       - Chute inicial: 50.  
       - Se for menor, reduzir para 1–49.  
       - Se for maior, aumentar para 51–100.  
       - Repetir até achar o número.  

- **Lógica computacional**: essa estratégia garante encontrar o número em **no máximo 7 tentativas** (pois a cada chute reduzimos o espaço de busca pela metade).

---

# ✅ Conclusão
O **pensamento computacional** é construído em 4 pilares:  
- **Decomposição**, **Padrões**, **Abstração** e **Algoritmos**.  

Os **estudos de caso** mostraram que:  
- **Soma de intervalo** → pensar em fórmulas e eficiência.  
- **Adivinhe um número** → usar estratégias inteligentes como a **busca binária**.  

Isso prova que o pensamento computacional não é só para programar, mas para **resolver problemas de qualquer tipo de forma mais lógica, rápida e eficiente**.  
