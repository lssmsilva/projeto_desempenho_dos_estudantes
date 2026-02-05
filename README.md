# 📘 Projeto de Estatística — Students Performance

Este repositório contém as análises desenvolvidas durante os módulos de **Estatística I e II** da pós-graduação em Engenharia e Análise de Dados. O estudo utiliza o dataset **Students Performance**, composto por 1.000 estudantes com informações pessoais, socioeconômicas e desempenho acadêmico em Matemática, Leitura e Escrita. citeturn2search1

O notebook principal realiza cálculos de probabilidade, probabilidade condicional, **Teorema de Bayes**, variáveis aleatórias e visualizações estatísticas. citeturn2search1

---

## 📁 Estrutura do Repositório
```
data/
└── StudentsPerformance.csv       # Dataset (adição manual)

notebooks/
└── estatistica_students_performance.ipynb   # Notebook principal

README.md
requirements.txt
```

---

## 🎯 Objetivos do Projeto
- Explorar e compreender a estrutura do dataset Students Performance. citeturn2search1
- Aplicar conceitos fundamentais de:
  - Probabilidade simples
  - Probabilidade condicional
  - Teorema de Bayes
  - Variáveis aleatórias e estatística descritiva
- Criar visualizações comparativas entre grupos (ex.: taxa de conclusão por gênero). citeturn2search1

---

## 📊 Principais Insights do Projeto

### 1) Mulheres têm maior taxa de conclusão do curso preparatório
Ao calcular a probabilidade condicional \( P(	ext{Completou} \mid 	ext{Mulher}) \), observou‑se que as mulheres apresentam uma **proporção maior de conclusão** do curso preparatório em comparação aos homens. citeturn2search1

### 2) Entre os estudantes que completaram o curso, a maioria é mulher (Teorema de Bayes)
Aplicando o Teorema de Bayes, o valor de \( P(	ext{Mulher} \mid 	ext{Completou}) \) mostrou que **mais da metade dos alunos que concluíram o curso são mulheres**, reforçando a tendência do item anterior. citeturn2search1

### 3) Diferenças perceptíveis de preparo por gênero
Comparando as probabilidades e as distribuições por gênero, nota‑se uma **diferença mensurável na preparação** entre homens e mulheres — um gancho para futuras análises envolvendo fatores socioeconômicos e comportamentais. citeturn2search1

### 4) Dataset adequado para fundamentar conceitos de Estatística
A composição do dataset (variáveis categóricas e numéricas) permite aplicar de forma didática espaço amostral, eventos, probabilidade simples/condicional e variáveis aleatórias em um contexto realista. citeturn2search1

### 5) Visualizações evidenciam padrões entre grupos
Gráficos (como barras da taxa de conclusão por gênero) tornam as diferenças **claras e comunicáveis**, facilitando o entendimento por públicos técnicos e não técnicos. citeturn2search1

> **Observação**: todos os resultados e gráficos citados acima são reproduzíveis executando o notebook em `notebooks/estatistica_students_performance.ipynb`. citeturn2search1

---

## ▶️ Como Executar
1. Instale as dependências:
```bash
pip install -r requirements.txt
```
2. Certifique-se de que o dataset está em:
```
data/StudentsPerformance.csv
```
3. Abra o notebook:
```bash
jupyter notebook notebooks/estatistica_students_performance.ipynb
```

---

## 🛠️ Tecnologias Utilizadas
- Python · Pandas · NumPy · SciPy
- Matplotlib · Seaborn · Plotly
- Jupyter Notebook

---

## 👩‍💻 Autora
**Laura Silva Soares de Melo**  
Pós-graduação em Engenharia e Análise de Dados
