# 📊 Conjunto Dominante em Grafos

Este repositório contém a implementação de algoritmos para resolver o problema do **Conjunto Dominante (Dominating Set)** em grafos, desenvolvida em **Java** para a disciplina de **Análise de Algoritmos**.

O projeto tem como objetivo estudar a complexidade computacional do problema, bem como aplicar técnicas algorítmicas para sua resolução.

---

## 📌 Descrição do Problema

Dado um grafo \( G = (V, E) \), um **conjunto dominante** é um subconjunto \( D \subseteq V \) tal que:

Todo vértice de \( V \) pertence a \( D \) ou é adjacente a pelo menos um vértice de \( D \).

Em outras palavras, todos os vértices do grafo devem ser **dominados** por algum vértice do conjunto.

### Exemplo

Considere o grafo:
``` text
A --- B --- C
|     |
D --- E
```
Um possível conjunto dominante é:

D = {B, D}

Pois todos os vértices são cobertos por eles.

---

## ⚠️ Importância do Problema

O problema do Conjunto Dominante é fundamental na teoria dos grafos e possui diversas aplicações, como:

- Otimização de redes de sensores
- Posicionamento de roteadores
- Monitoramento de sistemas
- Cobertura de redes
- Planejamento de recursos

Além disso, trata-se de um problema **NP-Difícil**, sendo relevante para estudos em Análise de Algoritmos.

---

## 🧠 Abordagem Utilizada

Neste projeto, foram implementadas as seguintes estratégias:

- Força Bruta (Backtracking)
- Heurísticas

---

## ⚙️ Funcionalidades

- Leitura de grafos por arquivo
- Representação por lista de adjacência
- Execução dos algoritmos
- Exibição do conjunto dominante
- Cálculo do tamanho da solução
- Análise de desempenho

---

## 🛠️ Tecnologias Utilizadas

- Linguagem: Java
- Estruturas de Dados: Listas, Conjuntos, Mapas
- IDE: Opcional

---

## 📈 Objetivos do Projeto
- Estudar problemas NP-Difíceis
- Analisar complexidade
- Comparar abordagens
- Aplicar teoria na prática
