# Desempenho de estudantes: probabilidade e estatística com Python

Análise do dataset **Students Performance** (1.000 estudantes, sem valores nulos) feita nos módulos de Estatística I e II da pós-graduação em Engenharia e Análise de Dados (CESAR School). O notebook cobre probabilidade simples e condicional, Teorema de Bayes, variáveis aleatórias, correlação e distribuições amostrais, sempre ligando a teoria a perguntas sobre os dados.

## Principais achados

Todos os números abaixo são calculados no final do notebook.

1. **O curso preparatório está associado a notas mais altas.** Quem concluiu o curso teve em média +5,6 pontos em matemática, +7,4 em leitura e +9,9 em escrita (todas as diferenças com p < 0,001). Os dados não permitem dizer que o curso causa a melhora: quem faz o curso pode diferir em outros aspectos.
2. **Mulheres e homens concluem o curso na mesma proporção.** 35,5% das mulheres e 36,1% dos homens (qui-quadrado, p = 0,90). Como 51,8% da amostra é feminina, pelo Teorema de Bayes P(mulher | completou) = 51,4%, praticamente o mesmo número.
3. **O desempenho por gênero depende da disciplina.** Mulheres vão melhor em leitura (+7,1 pontos) e escrita (+9,2); homens vão melhor em matemática (+5,1).
4. **O tipo de almoço é o fator socioeconômico com maior diferença.** Alunos com almoço padrão têm média geral de 70,8 contra 62,2 para almoço gratuito ou reduzido (8,6 pontos).
5. **A escolaridade dos pais acompanha as notas.** A média geral sobe de 63,1 (pais com ensino médio) para 73,6 (pais com mestrado).
6. **Leitura e escrita andam quase juntas** (correlação de 0,95). Matemática se correlaciona menos com elas (0,80 a 0,82).
7. **Comparação externa:** a média de leitura é 4,7% maior que a de matemática neste dataset e 8,2% maior no PISA 2022 do Brasil, o mesmo padrão com intensidade diferente.

## Dados

- Dataset Students Performance: 1.000 estudantes, com gênero, grupo, escolaridade dos pais, tipo de almoço, curso preparatório e notas de matemática, leitura e escrita (0 a 100).
- Arquivo em `data/StudentsPerformance.csv`.

## O que o notebook faz

- Probabilidade simples, união, interseção, complemento e diferença.
- Probabilidade condicional e Teorema de Bayes.
- Variável aleatória (média das notas), função de probabilidade e função de repartição.
- Histogramas, boxplots, pairplot, covariância e correlação de Pearson.
- Distribuições amostrais e o Teorema Central do Limite.
- Dummy encoding e comparação entre StandardScaler e MinMaxScaler.

## Estrutura

```
├── data/
│   └── StudentsPerformance.csv
├── notebook/
│   └── estatistica_students_performance.ipynb
├── requirements.txt
└── README.md
```

## Como executar

1. `pip install -r requirements.txt`
2. Abra o notebook a partir da pasta `notebook/` (ele lê o CSV em `../data/`):
   ```bash
   cd notebook
   jupyter notebook estatistica_students_performance.ipynb
   ```
3. Execute as células em ordem.

## Autora

Laura Silva Soares de Melo · [LinkedIn](https://www.linkedin.com/in/laura-soares-313067195) · [GitHub](https://github.com/lssmsilva)
