# FIAP 2026 – Redes Neurais Artificiais, Deep Learning e Algoritmos Genéticos

Este repositório reúne todos os **notebooks, dados e materiais** utilizados na disciplina:

**Redes Neurais Artificiais, Deep Learning e Algoritmos Genéticos**  
Curso Tecnólogo FIAP – Turmas 2026

Instrutor: **Samir Ramos**  

---

## 🔑 Como usar este repositório

### 1. Pré-requisitos

- Ter uma conta Google (Gmail) para usar o **Google Colab**.
- Ter acesso ao GitHub (não é obrigatório para rodar, mas é recomendado para visualizar o repositório).

### 2. Passo a passo para os alunos

1. Acesse este repositório no GitHub:  
   `https://github.com/samoliverramos/FIAP2026`

2. Escolha a aula que deseja abrir (veja a seção abaixo).

3. Clique no link **"Abrir no Colab"** correspondente à aula.

4. No Colab:
   - Verifique se está logado com sua conta Google.
   - Vá em `Runtime` / `Executar tudo` (ou `Ambiente de execução` / `Executar tudo`).
   - Siga as instruções comentadas em cada notebook.

---

## 📚 Aulas (Notebooks)

AULAS DE MACHINE LEARNING

### Aula 01 - Trocador de calor - Análise e Revisão do exercício do prof. Julles

### Aula 02 – App de Corridas & AWS (Regressão Linear + Planejamento de Capacidade)

Objetivos:
- Relembrar regressão linear (modelo, β₀, β₁).
- Entender métricas: **R², MAE, MSE, RMSE** em “corridas/dia”.
- Usar o modelo para estimar quando precisamos escalar servidores (AWS Auto Scaling).

Notebook:
[▶ Abrir Aula 02 – App de Corridas no Colab](https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/aulas/aula01_app_corridas.ipynb)

## Aula 03 – Classificação de Crédito com Regressão Logística

  **Objetivos da aula:**
  - Entender a diferença entre regressão e classificação.
  - Introduzir regressão logística como modelo de classificação binária.
  - Treinar um modelo para aprovar/recusar crédito com base em dados de clientes.
  - Avaliar o modelo com accuracy e matriz de confusão, discutindo impacto de erros no negócio.

  [▶ Abrir Aula 03 – Regressão Logística (Crédito) no Colab]([https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/Práticas_Machine_Learning/aulas/aula03_regressao_logistica_credito.ipynb])

 

AULAS DE RERDES NEURAIS


### Aula 03 – Perceptron (Primeiro neurônio artificial)

Objetivos:
- Implementar um **perceptron** do zero em Python.
- Entender:
  - inputs, pesos, bias,
  - soma ponderada (`w·x + b`),
  - função de ativação (degrau),
  - ajuste de pesos ao longo das épocas.
- Visualizar a **fronteira de decisão** para um problema simples de classificação (comprou / não comprou).

Notebook:

[▶ Abrir Aula 2 – Perceptron (Primeiro neurônio) no Colab](https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/aulas/aula02_perceptron.ipynb)

### (Adicionar conforme as aulas forem sendo criadas)



- Aula 3 – MLP e Backpropagation  
- Aula 4 – TensorFlow: primeira rede neural com Keras  
- Aula 5 – Redes recorrentes e LSTM (séries temporais)  
- …

---

## 📂 Estrutura do repositório

```text
FIAP2026/
  ├── aulas/
  │   ├── aula01_app_corridas.ipynb
  │   ├── aula02_perceptron.ipynb
  │   └── ...
  ├── data/
  │   ├── rides_app.csv
  │   └── ...
  ├── extras/
  │   ├── imagens/
  │   ├── pdfs/
  │   └── ...
  └── README.md
```

- **aulas/** → notebooks usados em sala e para estudo.  
- **data/** → arquivos de dados (.csv, .xlsx, etc.).  
- **extras/** → materiais de apoio (imagens, PDFs, etc.).

---

## 💡 Dicas para os alunos

- Sempre rode o notebook **de cima para baixo**, sem pular células.
- Leia os comentários em português; eles explicam o que cada linha faz.
- Traga dúvidas anotadas para a próxima aula.
- Alguns notebooks terão seções marcadas como **“DESAFIO”** – tente resolver, mesmo que não esteja valendo nota. Isso acelera muito seu aprendizado.

---

## 📌 Observação sobre o Kahoot

As atividades, explicações teóricas rápidas e quizzes serão conduzidos em sala via **Kahoot**.  
Os notebooks deste repositório são a parte **prática**, para você:

- Acompanhar a aula ao vivo no Colab.  
- Revisar em casa tudo o que foi feito em sala.  

Mantenha este repositório salvo nos seus favoritos.
