# 🧠📊 Previsão de Score com Inteligência Artificial em Python

Este projeto aplica **técnicas de Machine Learning em Python** para analisar o score de crédito de clientes e **prever o comportamento de novos consumidores**, utilizando dados históricos de uma base simulada.

> 🔍 Projeto idealizado para praticar análise de dados, pré-processamento, criação de modelo preditivo e aplicação prática de aprendizado supervisionado, com foco em problemas de negócio.

---

## 🎯 Objetivos do Projeto

- Realizar análise exploratória de dados (EDA)
- Aplicar algoritmos de Machine Learning (IA supervisionada)
- Prever scores para novos clientes com base em características históricas
- Avaliar desempenho do modelo com métricas técnicas

---

## 🧠 Modelo Preditivo

Utilizei o algoritmo `RandomForestClassifier` da biblioteca `scikit-learn`.

As etapas do pipeline incluem:

- Pré-processamento com `pandas`
- Separação entre treino e teste (holdout)
- Treinamento e previsão
- Cálculo de métricas de performance (`accuracy`, `precision`, `recall`, etc.)

> 💡 Os dados foram divididos em duas bases:  
> `clientes.csv` (base histórica) + `novos_clientes.csv` (base para predição)

---

## 📊 Tecnologias e Bibliotecas Utilizadas

- Python 3.10
- Jupyter Notebook
- pandas
- scikit-learn

---

## 📁 Estrutura dos Arquivos
```
📂 Python_IA-Analise_de_Score/
├── inicial.ipynb # Notebook principal com todo o pipeline de IA
├── clientes.csv # Base de dados histórica de clientes
├── novos_clientes.csv # Base com clientes para teste/predição
└── README.md # Documentação completa do projeto
```
---

## 🚀 Como Executar

1. Clone o repositório:
```
git clone https://github.com/tamirisrbarbosa/Python_IA-Analise_de_Score.git
```
2. Instale as dependências:
```
pip install pandas scikit-learn
```
3. Execute o notebook:
```
jupyter notebook inicial.ipynb
```
---

## 📈 Métricas de Avaliação

Resultados reais das acurácias obtidas com os modelos treinados a partir dos dados do projeto:

🌳 Árvore de Decisão (Random Forest): 89%

🤝 KNN (K-Nearest Neighbors): 84%

| Métrica         | Resultado |
|----------------|-----------|
| Acurácia        | 89%       |
| Precisão        | 84%       |
| Recall          | 78%       |

---

🧠 Insights Extraídos
- 📊 Idade e renda apresentaram maior correlação com o score de crédito, conforme análise exploratória.
- ✅ Pagadores com comportamento positivo mantêm score consistentemente alto (acima de 700).
- 🚩 O modelo identificou com precisão casos de alto risco, ajudando a mitigar inadimplência.

---

## 👩‍💻 Sobre mim
Sou Tamiris Barbosa, estudante de Análise e Desenvolvimento de Sistemas em transição de carreira para a área tech. Tenho interesse em desenvolvimento backend, análise de dados e automações inteligentes.

🔗 [Meu LinkedIn](https://www.linkedin.com/in/tamirisrodriguesbarbosa)

🐙 [Meu GitHub](https://github.com/tamirisrbarbosa)

---

## 💡Créditos
Projeto inspirado no conteúdo gratuito da Jornada Python da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).



