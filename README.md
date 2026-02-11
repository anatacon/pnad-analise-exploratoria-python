# 📊 Análise Exploratória da PNAD Contínua – Mercado de Trabalho e Escolaridade

## 📌 Sobre o projeto
Este projeto apresenta uma **análise exploratória de dados (EDA)** utilizando a **PNAD Contínua**, com foco em indivíduos **ocupados**, buscando compreender a relação entre **escolaridade, idade e renda do trabalho**.

O objetivo principal é aplicar técnicas iniciais de análise de dados em um conjunto de dados real, de grande porte e amplamente utilizado em estudos socioeconômicos, demonstrando habilidades em **Python, pandas, limpeza de dados e comunicação de resultados**.

---

## 🎯 Objetivo
Realizar uma análise exploratória dos dados da PNAD Contínua com foco em indivíduos ocupados, investigando a relação entre escolaridade, idade e renda do trabalho.

---

## 🗂️ Base de dados
- **Fonte:** PNAD Contínua (IBGE) – versão disponibilizada no Kaggle  
- **Formato:** Parquet  
- **Ano:** 2024  
- **População analisada:** Pessoas com idade entre 14 e 100 anos  

A PNAD Contínua é uma pesquisa amostral realizada pelo IBGE que investiga características do mercado de trabalho e condições socioeconômicas da população brasileira.

---

## 🧾 Variáveis analisadas
Algumas das principais variáveis utilizadas no projeto incluem:

- **Idade**
- **Sexo**
- **Escolaridade**
- **Renda do trabalho**
- **Situação de trabalho (VD4002)**

---

## ⚠️ Limitações da base
A variável **VD4002 (situação de trabalho)** é aplicada apenas a indivíduos que já declararam vínculo de trabalho nas etapas anteriores do questionário da PNAD.  

Dessa forma, a base analisada contempla **exclusivamente indivíduos ocupados**, não incluindo pessoas fora da força de trabalho, como aposentados, estudantes ou pessoas que não exerceram atividade econômica na semana de referência.

Além disso, o conceito de ocupação adotado pela PNAD é amplo, abrangendo atividades formais, informais, eventuais ou realizadas por poucas horas, o que explica a presença de indivíduos em faixas etárias mais elevadas classificados como ocupados.

---

## 🧪 Etapas da análise
O projeto seguiu as seguintes etapas:

1. Leitura e entendimento da base de dados  
2. Análise das variáveis e do dicionário de dados  
3. Limpeza e tratamento dos dados  
4. Conversão de tipos e padronização de categorias  
5. Análise exploratória com estatísticas descritivas  
6. Criação de visualizações padronizadas  
7. Interpretação dos resultados e identificação de limitações  

---

## 📈 Principais análises realizadas
- Distribuição etária dos trabalhadores ocupados  
- Distribuição por sexo e escolaridade  
- Análise da renda do trabalho  
- Relação entre escolaridade e renda media  

---

## 🛠️ Ferramentas e tecnologias
- **Python**
- **pandas**
- **matplotlib**
- **seaborn**
- **Jupyter Notebook**

---

## 📌 Conclusão
- A base analisada contempla exclusivamente indivíduos ocupados  
- Observa-se uma associação positiva entre nível de escolaridade e renda media  
- A análise reforça a importância da correta interpretação das variáveis da PNAD  
- O projeto demonstra o potencial do uso de dados públicos para análises socioeconômicas  

---

## 👩‍💻 Autora
**Ana Claudia Casagrande Tacon**  
Projeto desenvolvido como parte da construção de um **portfólio para atuação na área de Dados**.

