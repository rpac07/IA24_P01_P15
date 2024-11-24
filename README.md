
# Planeamento e Gestão de Tarefas com OR-Tools

Este projeto utiliza a biblioteca **OR-Tools** da Google para resolver problemas de programação e planeamento de tarefas. Ele é especialmente útil para planear projetos de forma eficiente, respeitando dependências entre tarefas, recursos limitados e otimizando o tempo total de execução (makespan).


Git Link - > https://github.com/rpac07/IA24_P01_P15

---

## 🚀 Funcionalidades

1. **Leitura de Dados**  
   O programa processa um ficheiro de texto contendo informações detalhadas sobre tarefas, dependências, durações e recursos disponíveis. Este ficheiro é dividido em seções como:
   - Relações de precedência.
   - Duração das tarefas e recursos necessários.
   - Disponibilidade de recursos.

2. **Estruturação dos Dados**  
   Os dados são organizados em dicionários para facilitar a manipulação e a criação do modelo matemático.

3. **Definição e Resolução do Modelo**  
   - As tarefas são modeladas como intervalos com tempos de início e fim.
   - As dependências são garantidas (uma tarefa só pode começar quando as predecessoras terminarem).
   - Restrições de recursos asseguram que os limites disponíveis não sejam excedidos.
   - O objetivo é minimizar o tempo total do projeto (makespan).

4. **Visualização dos Resultados**  
   - Os tempos de início e fim de cada tarefa são apresentados.
   - Um gráfico de Gantt é gerado para visualizar o planeamento das tarefas e os recursos utilizados.

---

## 🛠️ Tecnologias Utilizadas

- **Python**  
  Linguagem principal utilizada para o desenvolvimento do projeto.
  
- **OR-Tools (Google)**  
  Biblioteca de otimização e programação para resolver problemas de planeamento e scheduling.

- **Matplotlib**  
  Biblioteca para geração de gráficos, usada para criar o gráfico de Gantt.

---


## 📊 Gráfico de Gantt

O gráfico de Gantt gerado pelo programa mostra de forma visual:
- Quando cada tarefa começa e termina.
- Os recursos utilizados por cada tarefa.

---

## 🌐 Link de Acesso

https://colab.research.google.com/drive/1JtFSJ08Fs8ANtovkkPXe-lYL8n_FJm0p?usp=sharing#scrollTo=7otCk8TGlJQ-

---
