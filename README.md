# Projeto-Integrador-IV

# Não comparecimento em consultas médicas: uma análise de dados públicos e seus impactos na Saúde

# Análise e Predição do Absenteísmo em Consultas Médicas

[Kaggle – Base de Dados](https://www.kaggle.com/datasets/joniarroba/noshowappointments)<br><br>
[Estatística Descritiva – Google Colab](https://colab.research.google.com/drive/1O4C8f0gfvjE8dX9hAqYSN7YPe9q4cZy5)<br><br>
[Machine Learning – Google Colab](https://colab.research.google.com/drive/10c4YzZnTqbHAaHGrF8DrqiGlYejQ9gO8)<br><br>
[Homepage](index_projeto.html)

## 📌 Visão Geral
Este projeto investiga o absenteísmo em consultas médicas utilizando dados públicos do Kaggle (110 mil registros).  
Combinamos **estatística descritiva**, **Machine Learning** e **desenvolvimento web** para:

- identificar padrões relacionados ao não comparecimento,
- prever a probabilidade de absenteísmo,
- sugerir intervenções práticas,
- exibir resultados em uma interface acessível.

O modelo **LightGBM** apresentou o melhor desempenho (AUC: 0.74).

---

## 🎯 Objetivo Geral
Desenvolver uma solução analítica e preditiva capaz de identificar fatores associados ao absenteísmo e apoiar decisões para reduzir faltas em consultas médicas.

---

## 🎯 Objetivos Específicos
- Explorar, limpar e tratar a base do Kaggle.  
- Realizar estatísticas descritivas para entender o comportamento dos pacientes.  
- Treinar e comparar modelos de Machine Learning.  
- Identificar variáveis com maior impacto no absenteísmo.  
- Desenvolver uma interface web para consulta dos resultados.  
- Propor intervenções baseadas em evidências.

---

## 🩺 Problema Investigado
O absenteísmo provoca:

- desperdício de recursos,
- aumento de filas e tempo de espera,
- redução da eficiência dos serviços de saúde.

O projeto busca compreender os fatores que influenciam o não comparecimento e desenvolver um modelo capaz de prever com precisão esses eventos.

---

## 🧪 Parte Experimental

### 🔹 Base de dados
- Fonte: Kaggle (No-Show Appointments)
- Total de registros: **110.527**
- Variáveis analisadas: idade, sexo, comorbidades, SMS, lead time, entre outras.

### 🔹 Etapas realizadas
- Limpeza e padronização dos dados  
- Verificação de duplicatas  
- Estatística descritiva  
- Treinamento de modelos:  
  - Regressão Logística  
  - Random Forest  
  - XGBoost  
  - LightGBM  
  - Rede Neural  
- Comparação de métricas (AUC, F1, Brier Score)  
- Seleção do melhor modelo  
- Desenvolvimento de aplicação web

---

## 🤖 Machine Learning – Resultados

### 🔹 Modelo escolhido
**LightGBM**  
- AUC-ROC: **0.74**  
- Brier Score: **0.14**  
- Melhor desempenho em dados desbalanceados  
- Boa interpretabilidade e excelente velocidade

### 🔹 Variáveis mais importantes
1. Tempo de espera (Waiting Time)  
2. Idade  
3. Recebimento de SMS  
4. Comorbidades  
5. Scholarship e Handicap  

---

## 🎯 Perfis de Risco Identificados

### 🔴 Alto risco
- jovens (< 25 anos)  
- espera longa (> 10 dias)  
- sem SMS  

### 🟠 Risco moderado
- horários menos convenientes  
- espera intermediária  

### 🟢 Baixo risco
- idosos com acompanhamento  
- comorbidades presentes  
- espera curta  

---

## 🛠️ Tecnologias utilizadas

| Categoria | Ferramentas |
|----------|-------------|
| Linguagem | Python |
| Análise de Dados | Pandas, NumPy |
| Visualização | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, LightGBM, XGBoost |
| Desenvolvimento Web | Flask / HTML / CSS / JS |
| Ambiente | VS Code, Jupyter Notebook |
| Dados | Kaggle Dataset |

---

## 🧩 Solução Proposta
Desenvolvemos uma solução integrada que:

- Prediz a chance de absenteísmo para cada paciente  
- Classifica automaticamente em níveis de risco  
- Permite visualização via interface web  
- Sugere intervenções personalizadas para redução de faltas  
- Apoia decisões em ambientes de saúde  

---

## 📝 Considerações Finais
- O absenteísmo é um problema multifatorial, mas previsível com dados.  
- Machine Learning, especialmente LightGBM, mostrou ótimo desempenho.  
- Comunicação automatizada (SMS/WhatsApp) pode reduzir faltas.  
- A solução desenvolvida integra análise, predição e interface web, trazendo valor real para serviços de saúde.  

---
