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
[▶ Abrir Aula 02 – App de Corridas no Colab](https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/aulas/Praticas_Machine_Learning/aula01_app_corridas.ipynb)




## Aula 03 – Classificação de Crédito com Regressão Logística

  **Objetivos da aula:**
  - Entender a diferença entre regressão e classificação.
  - Introduzir regressão logística como modelo de classificação binária.
  - Treinar um modelo para aprovar/recusar crédito com base em dados de clientes.
  - Avaliar o modelo com accuracy e matriz de confusão, discutindo impacto de erros no negócio.

  [▶ Abrir Aula 03 – Regressão Logística (Crédito) no Colab](https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/Praticas_Machine_Learning/aula03_regressao_logistica_credito.ipynb)

 ### Aula 04 - Algoritmo K-NN (

Objetivos da aula
- Introduzir o algoritmo K-Nearest Neighbors (K-NN) como técnica de classificação supervisionada.
- Trabalhar o fluxo completo de um mini-projeto de Machine Learning em contexto de varejo em São Paulo (cliente fiel vs. ocasional).

- Praticar:
Carregamento de dados a partir de um arquivo CSV.
Análise Exploratória de Dados (EDA) básica com pandas, matplotlib e seaborn.
Separação de features e variável alvo; divisão em treino e teste.
Normalização de dados numéricos com StandardScaler e discussão de por que isso é importante para K-NN.
Treinamento, predição e avaliação de um modelo KNeighborsClassifier usando acurácia, relatório de classificação e matriz de confusão.
Explorar o impacto dos hiperparâmetros de K-NN:
Variação do valor de K (número de vizinhos) e análise da curva acurácia x K.
Comparação entre weights="uniform" e weights="distance".
Visualizar e interpretar a fronteira de decisão em 2D (idade x gasto mensal) para entender melhor o comportamento do modelo.
Estimular o raciocínio crítico sobre:
Limitações do K-NN em bases grandes e com muitas features.
Possíveis extensões do modelo e próximos algoritmos a testar em um cenário real de varejo.

## Executar no Google Colab

Clique no botão abaixo para abrir o notebook diretamente no Google Colab:

[![Abrir Aula K-NN no Colab]()

https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/Pr%C3%A1ticas_Redes_Neurais/Aula04_KNN.ipynb

## ---------------------------------------------------------------

AULAS DE RERDES NEURAIS

### Aula 01 – Aula Teórica: Revisão da Aula 0 + O que é inteligência Artificial
### Aula 02 – Aula Teórica: Entendendo termos e conceitos sobre RN, DL e Algoritmos Genéticos

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

[▶ Abrir Aula 3 – Perceptron (Primeiro neurônio) no Colab](https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/aulas/aula02_perceptron.ipynb)



### Aula 04 – MLP em Keras para prever se o cliente compra

Objetivos de aprendizado no notebook:
- Implementar uma MLP simples com Keras (TensorFlow).
- Entender a relação: número de neurônios / camadas / epochs ↔ desempenho.
- Ver na prática feedforward, erro, backprop acontecendo “por trás” da API do Keras.

[▶ Abrir Aula 4 – MLP com Keras no Colab](https://colab.research.google.com/github.com/samoliverramos/FIAP2026/blob/main/Praticas_Redes_Neurais/Aula04_MLP_em_Keras.ipynb
)

https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/Praticas_Redes_Neurais/Aula04_MLP_em_Keras.ipynb

      ]
Aula 5 – MLP em Keras: Experimentos, LOSS, Baseline e Overfitting
Objetivos de aprendizado
Revisar a MLP construída na aula passada (Aula 4).
Entender, na prática, o que é LOSS (função de perda) e por que ela é importante.
Entender o conceito de modelo baseline.
Observar como neurônios, camadas e epochs afetam treino e validação.
Identificar sinais de underfitting e overfitting nos gráficos.

https://colab.research.google.com/github/samoliverramos/FIAP2026/blob/main/Praticas_Redes_Neurais/Aula05_MLP_Experimentos1.ipynb#scrollTo=b8b13461





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
