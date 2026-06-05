# 📊 Análise do Mercado de Trabalho em Tecnologia e Dados

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) sobre profissionais que atuam na área de Tecnologia da Informação e Dados. A análise busca identificar características demográficas, níveis de experiência, cargos, salários e outros fatores relacionados ao mercado de trabalho.

Foram utilizadas técnicas de estatística descritiva, tratamento de dados faltantes, identificação de outliers, visualização de dados e análise de distribuição amostral para obter insights sobre o cenário profissional da área de tecnologia.

---

## 🛠 Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly Express
* SciPy
* SQLite
* Google Colab

---

## 📚 Bibliotecas Utilizadas

### Pandas

Responsável pela importação, manipulação, limpeza e análise dos dados.

### NumPy

Utilizada para cálculos matemáticos e estatísticos, como média, mediana, soma e desvio padrão.

### Matplotlib

Utilizada para a construção de gráficos e visualizações estatísticas.

### Seaborn

Biblioteca de visualização estatística utilizada para complementar análises gráficas e facilitar a interpretação dos dados.

### Plotly Express

Utilizada para a criação de gráficos interativos e visualizações dinâmicas.

### SciPy

Utilizada para cálculos estatísticos avançados, incluindo distribuição amostral e intervalos de confiança.

### SQLite

Biblioteca utilizada para integração com bancos de dados relacionais.

### Google Colab

Ambiente utilizado para desenvolvimento e execução da análise.

---

## 📂 Base de Dados

A base de dados utilizada contém informações de profissionais da área de tecnologia e dados.

### Informações da Base

* 4.271 registros
* 28 variáveis
* Dados demográficos
* Escolaridade
* Área de formação
* Cargo atual
* Nível profissional
* Experiência em tecnologia e dados
* Faixa salarial
* Região de residência

---

## 🔍 Exploração Inicial dos Dados

A etapa inicial consistiu na inspeção da estrutura da base para compreender sua composição e qualidade.

Foram analisados:

* Quantidade de linhas e colunas
* Tipos de dados
* Valores nulos
* Estatísticas descritivas
* Distribuição das variáveis

Essa etapa permitiu identificar inconsistências e compreender melhor as características do conjunto de dados.

---

## 👥 Análise de Perfil dos Profissionais

Foram realizadas análises para compreender o perfil dos participantes da pesquisa.

Os principais aspectos avaliados foram:

* Distribuição por gênero
* Faixa etária predominante
* Níveis profissionais
* Cargos ocupados
* Participação em cargos de gestão
* Relação entre idade, gênero e nível profissional

Essas análises ajudaram a traçar um panorama do perfil dos profissionais atuantes no mercado de tecnologia e dados.

---

## 📈 Estatística Descritiva

Foram aplicadas medidas estatísticas para compreender a distribuição das variáveis analisadas.

### Principais resultados

**Idade**

* Média: 31,17 anos
* Mediana: 30 anos
* Desvio padrão: 6,90
* Idade mínima: 18 anos
* Idade máxima: 54 anos

**Salário**

* Média: R$ 10.517,53
* Alta variabilidade entre os profissionais analisados
* Presença de valores extremos que impactavam significativamente a média

---

## 💰 Comparação Salarial por Gênero

Foi realizada uma comparação entre as médias salariais dos grupos presentes na pesquisa.

### Média salarial masculina

* R$ 11.724,55

### Média salarial feminina

* R$ 8.673,22

Os resultados indicam uma diferença salarial relevante entre os grupos analisados, evidenciando um tema importante para estudos sobre o mercado de trabalho em tecnologia.

---

## 🧹 Tratamento de Valores Faltantes

Durante a análise foram identificados registros com informações ausentes.

Para minimizar impactos nos resultados:

* Valores ausentes de gênero foram classificados como "Prefiro não informar".
* Valores ausentes de idade foram preenchidos utilizando a média da amostra.
* Valores ausentes de salário foram preenchidos utilizando a mediana salarial.

Esse processo garantiu maior consistência para as análises estatísticas posteriores.

---

## 🚨 Identificação e Tratamento de Outliers

Foram identificados valores extremos principalmente na variável salário.

A presença desses registros influenciava significativamente medidas como média e desvio padrão. Após a aplicação de técnicas estatísticas para detecção de outliers, foi criada uma base filtrada para análises complementares.

### Resultados após o tratamento

* Registros analisados: 3.945
* Média salarial: R$ 8.027,55
* Mediana salarial: R$ 7.625,50
* Salário máximo: R$ 19.992,00

A remoção dos valores extremos permitiu uma análise mais representativa da realidade observada na amostra.

---

## 📊 Visualização dos Dados

Foram utilizados gráficos estatísticos para apoiar a análise exploratória.

As visualizações permitiram:

* Identificar padrões de distribuição
* Detectar valores extremos
* Comparar grupos de profissionais
* Avaliar a dispersão salarial

Os gráficos contribuíram para uma interpretação mais clara dos resultados obtidos.

---

## 📉 Distribuição Amostral e Intervalo de Confiança

Também foram aplicadas técnicas de inferência estatística para estimar parâmetros populacionais a partir da amostra estudada.

### Resultados

* Média amostral salarial: R$ 9.904,39
* Desvio padrão: R$ 8.306,10
* Tamanho da amostra: 4.271 profissionais

### Intervalo de Confiança (95%)

R$ 9.655,19 a R$ 10.153,59

Esse resultado indica que, com 95% de confiança, a média salarial da população representada pela pesquisa encontra-se dentro desse intervalo.

---

## 🎯 Principais Conclusões

* A maioria dos profissionais possui entre 25 e 39 anos.
* O gênero masculino representa a maior parcela da amostra.
* Foi identificada uma diferença salarial entre homens e mulheres.
* A presença de outliers influencia significativamente os indicadores salariais.
* O tratamento dos dados resultou em análises mais consistentes.
* A média salarial estimada para a população encontra-se entre R$ 9.655,19 e R$ 10.153,59 com 95% de confiança.
* Técnicas de estatística descritiva e inferencial contribuíram para uma compreensão mais aprofundada do mercado de tecnologia e dados.

---


## 👩‍💻 Autora

**Isadora dos Santos Duarte**

