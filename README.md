# Trilha de Conhecimento de Estatística para Ciência de Dados na Área da Saúde

Esta trilha de conhecimento propõe um roteiro para profissionais da saúde que desejam aprender estatística aplicada à ciência de dados. O foco está em fundamentos estatísticos, técnicas de análise e aplicações práticas na área da saúde.

---

## 1. Fundamentos de Estatística e Conceitos Básicos

### 1.1 Por que estatística é importante na saúde?
- **Relevância**: entender como dados podem embasar decisões clínicas, epidemiológicas, pesquisas farmacológicas e políticas de saúde.  
- **Exemplos**: avaliação da eficácia de medicamentos, estudos de prevalência/incidência, ensaios clínicos etc.

### 1.2 Conceitos iniciais
- **População vs. Amostra**: extrair conclusões de um grupo maior a partir de dados de um grupo menor.  
- **Tipos de variáveis**: categóricas (nominal, ordinal) e numéricas (discretas, contínuas).  
- **Escalas de medição**: nominal, ordinal, intervalo e razão.

**Onde estudar**  
- Livros introdutórios, como *“Estatística Básica”* (muito utilizado em cursos de ciências da saúde).  
- Khan Academy (estatística básica, em inglês com legendas em português).  
- Coursera e edX (cursos introdutórios de estatística).

---

## 2. Estatística Descritiva

### 2.1 Medidas de Tendência Central
- **Média**, **mediana**, **moda**.  
- Quando usar cada medida e impacto em distribuições assimétricas (por exemplo, tempo de hospitalização).

### 2.2 Medidas de Dispersão
- **Variância**, **desvio-padrão**, **amplitude (range)**, **coeficiente de variação**.  
- Avaliação da variabilidade de parâmetros clínicos (ex.: colesterol, pressão arterial).

### 2.3 Representação Gráfica
- **Histogramas**, **boxplots**, **gráficos de barras**, **pizza**, **scatter plot**.  
- Aplicações em estudos de incidência/prevalência de doenças, resultados de exames etc.

**Onde estudar**  
- Khan Academy: módulos de estatística descritiva.  
- DataCamp: *Introduction to Data Visualization* (R ou Python).  
- Livro: “Bioestatística para leigos em estatística” (ou similar).

---

## 3. Probabilidade e Distribuições Estatísticas

### 3.1 Conceitos de Probabilidade
- **Eventos e Espaço Amostral**  
- **Teorema de Bayes** (aplicado em diagnósticos médicos).  
- **Sensibilidade, Especificidade, VPP (Valor Preditivo Positivo) e VPN (Valor Preditivo Negativo)**.

### 3.2 Principais Distribuições
- **Distribuição Normal (Gaussiana)**: relevância na área da saúde e testes de hipóteses.  
- **Distribuição Binomial e Poisson**: contagem de eventos (ocorrência de doenças, por exemplo).  
- **Distribuições Exponencial e Weibull**: análise de sobrevivência.

**Onde estudar**  
- Coursera: *“Biostatistics in Public Health”*.  
- Livros de probabilidade: “Probabilidade e Estatística” (Magalhães e Lima ou Bussab e Morettin).  
- Módulos de Probability em DataCamp.

---

## 4. Intervalos de Confiança e Testes de Hipóteses

### 4.1 Intervalos de Confiança (IC)
- **Conceito de Intervalo de Confiança**: IC de 95% para médias ou proporções.  
- Aplicações em estimativas de prevalência e ensaios clínicos.

### 4.2 Testes de Hipóteses
- **Hipótese Nula (H0) e Hipótese Alternativa (H1)**  
- **Erro Tipo I (α) e Erro Tipo II (β)**  
- **P-valor**: uso e cuidados (p-hacking).  
- **Testes comuns**: teste t (simples e pareado), ANOVA, qui-quadrado, teste de Fisher.

**Onde estudar**  
- Coursera: *Hypothesis Testing in Public Health*.  
- Literatura de Bioestatística (ex.: “Bioestatística” de Triola ou Zar).  
- Vídeos no YouTube (Canal *Estatística em Foco*, por exemplo).

---

## 5. Modelos de Regressão

### 5.1 Regressão Linear
- **Conceito**: relação entre variável dependente contínua (ex.: pressão arterial) e variáveis independentes (ex.: idade, peso, sexo).  
- **Interpretação de coeficientes**, **R²**, **validação de pressupostos** (normalidade dos resíduos, homocedasticidade).

### 5.2 Regressão Logística
- **Uso para variável dependente binária** (doença “sim”/“não”).  
- **Odds ratio (OR)**, **log odds** e interpretação clínica.  
- **Aplicações**: risco de desenvolver doença, probabilidade de um desfecho clínico.

### 5.3 Outras Técnicas
- **Regressão Poisson**: modelagem de contagem de eventos.  
- **Regressão Cox (Análise de Sobrevivência)**: tempo até evento (morte, recaída).

**Onde estudar**  
- Livros de Epidemiologia com foco em modelos de regressão (ex.: “Epidemiologia Básica”, da OMS).  
- Curso online: *Regression Models* (Coursera).  
- DataCamp: *Intro to Regression in R* / *Logistic Regression in Python*.

---

## 6. Análise de Sobrevivência

### 6.1 Conceitos
- **Tempo até o evento**: falecimento, recorrência de doença, sucesso de tratamento.  
- **Dados censurados**: pacientes que não atingiram o desfecho até o final do estudo.

### 6.2 Métodos
- **Função de Sobrevivência e Função de Risco**  
- **Curvas de Kaplan-Meier**  
- **Teste de log-rank**  
- **Modelo de Regressão de Cox** (Proportional Hazards)

**Onde estudar**  
- Coursera/edX: módulos de *Biostatistics – Survival Analysis*.  
- Livro: “Análise de Sobrevivência” (Colosimo e Giolo).  
- Artigos científicos na área médica (ex.: estudos oncológicos com Kaplan-Meier).

---

## 7. Planejamento de Experimentos e Ensaios Clínicos

### 7.1 Ensaios Clínicos
- **Desenho de estudo clínico**: randomização, cegamento (simples, duplo), grupos controle.  
- **Fases de ensaios (Fase I, II, III, IV)**  
- **Tamanho de amostra** e **poder estatístico**.

### 7.2 Outros Tipos de Estudos Epidemiológicos
- **Estudos transversais, caso-controle, coorte**  
- **Viés de seleção, viés de informação**  
- **Controle de confusão**

**Onde estudar**  
- Livros/Guias de Epidemiologia Clínica (ex.: “Clinical Epidemiology: The Essentials”).  
- Diretrizes de boas práticas de pesquisa clínica (ANVISA, FDA, EMA).  
- Coursera: *Design and Interpretation of Clinical Trials* (Johns Hopkins).

---

## 8. Ferramentas Computacionais

### 8.1 R e RStudio
- **Pacotes**: `tidyverse`, `ggplot2`, `survival`, `caret`.  
- **Shiny**: criação de dashboards interativos (úteis para apresentação de resultados a equipes médicas).

### 8.2 Python
- **Bibliotecas**: `pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib`, `seaborn`.  
- Aplicações em estatística e machine learning.

### 8.3 Outras Ferramentas
- **SPSS** (muito usado na pesquisa acadêmica).  
- **SAS** (bastante utilizado em farmacêuticas).  
- **Power BI / Tableau** (visualização de dados e relatórios interativos).

**Onde estudar**  
- DataCamp (cursos de R e Python para estatística).  
- R-bloggers (tutoriais e exemplos em R).  
- Documentação oficial Python (scipy, pandas, statsmodels).  
- Tutoriais no YouTube, LinkedIn Learning etc.

---

## 9. Machine Learning Básico para a Saúde

### 9.1 Conceitos Fundamentais
- **Aprendizado Supervisionado vs. Não Supervisionado**  
- **Classificação vs. Regressão**  
- **Validação Cruzada**, **overfitting**  
- **Métricas**: acurácia, sensibilidade, especificidade, AUC-ROC.

### 9.2 Exemplos de Aplicação
- **Classificação de imagens médicas** (radiologia).  
- **Análise preditiva**: risco de internação, probabilidade de complicações.  
- **Clustering**: segmentação de pacientes por similaridade clínica.

**Onde estudar**  
- Coursera: *Machine Learning for Healthcare* (Stanford).  
- Livro: *Introduction to Machine Learning with Python* (Andreas Müller, Sarah Guido).  
- Kaggle: competições de dados de saúde para prática.

---

## 10. Aprofundamento e Recursos Adicionais

### 10.1 Comunidades e Eventos
- **Meetups de Data Science** focados em saúde (Meetup.com).  
- **Conferências de Bioestatística ou Epidemiologia** (ex.: Associação Brasileira de Estatística).

### 10.2 Leitura e Pesquisa Contínua
- **PubMed, SciELO**: artigos científicos com aplicações de testes estatísticos em saúde.  
- **Grupos e fóruns online**: Stack Overflow (programação), Cross Validated (estatística).

### 10.3 Boas Práticas de Comunicação
- **Interpretação de resultados**: linguagem acessível a equipes médicas e gestores.  
- **Visualizações**: dashboards de indicadores de saúde para monitoramento de metas.

---

## Resumo da Trilha

1. **Fundamentos e conceitos básicos**: população vs. amostra, tipos de variáveis.  
2. **Estatística descritiva**: medidas de tendência central e dispersão, gráficos.  
3. **Probabilidade e distribuições**: normal, binomial, Poisson, aplicações em diagnósticos.  
4. **Intervalos de confiança e testes de hipóteses**: p-valor, teste t, qui-quadrado etc.  
5. **Modelos de regressão**: linear, logística, Poisson, Cox (sobrevivência).  
6. **Análise de sobrevivência**: Kaplan-Meier, log-rank, regressão Cox.  
7. **Planejamento de experimentos e ensaios clínicos**: randomização, cálculo de tamanho de amostra, poder.  
8. **Ferramentas computacionais**: R, Python, SPSS, SAS, visualização de dados.  
9. **ML básico para saúde**: classificação, regressão, métricas, exemplos práticos.  
10. **Aprofundamento e prática contínua**: leitura de artigos, participação em comunidades, comunicação efetiva de resultados.

Seguindo este roteiro e praticando constantemente, profissionais da saúde poderão aplicar métodos estatísticos robustos na tomada de decisão clínica e em pesquisa, contribuindo para a melhoria de processos e resultados na área da saúde.
