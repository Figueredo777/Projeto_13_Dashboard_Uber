# 🚕 Projeto_13_Dashboard_Uber

Um **Dashboard interativo** desenvolvido com **Streamlit**, **Pandas** e **Plotly**, utilizando um dataset real de corridas do Uber em Nova York.  
O projeto permite analisar padrões de tarifa, horários mais caros, volume de corridas e distribuição geográfica dos pickups ao longo dos anos.

---

## 🧠 Situação-Problema

A equipe de análise de uma empresa de transporte urbano precisa entender melhor o comportamento das corridas e tarifas ao longo dos anos para:

- Identificar horários de maior faturamento  
- Entender sazonalidade mensal nas corridas  
- Visualizar geograficamente onde se concentram os passageiros  
- Analisar tendências de tarifas ao longo do tempo  
- Suportar decisões de expansão e otimização da frota  

Para isso, os alunos devem criar um **dashboard funcional e intuitivo**, capaz de oferecer insights rápidos e acionáveis sobre as corridas de Uber.

---

## 🎯 Objetivo Educacional

- Aprender a manipular dados de tempo (**year**, **month**, **hour**)  
- Criar KPIs utilizando o `st.metric`  
- Construir gráficos interativos com Plotly Line Chart  
- Ler e filtrar dados com eficiência  
- Trabalhar com visualização geográfica usando `st.map`  
- Desenvolver dashboards profissionais com Streamlit usando Containers e Sidebar  
- Treinar lógica de UX para dashboards reais

---

## ⚙️ Funcionalidades do Dashboard

### 📌 KPIs
- **Total de Corridas**
- **Total Tarifado ($)**
- **Tarifa Mais Cara**
- **Quantidade Total de Passageiros**

### 📊 Visualizações
- **Tarifa ao longo das horas do dia**  
- **Tarifa ao longo dos meses**  
- **Mapa de corridas com coordenadas válidas (NYC area)**  
- Filtro interativo por **período (ano inicial → ano final)**  

### 🧩 Filtros Interativos
- Slider de período (2009 a 2015)  
- Filtro automático que refina todos os gráficos e métricas  

### 🌍 Mapa das Corridas
O mapa é plotado apenas para coordenadas dentro dos limites de:

- Longitude: `-74.27` a `-73.68`  
- Latitude: `40.49` a `40.92`  

Garantindo visualização limpa, evitando ruídos de coordenadas inválidas.

---

