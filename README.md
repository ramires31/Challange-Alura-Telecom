# 📊 Análise de Evasão de Clientes – Telecom X

Este projeto faz parte de um desafio de análise de dados da empresa fictícia **Telecom X**, cujo objetivo é investigar os motivos da evasão de clientes (churn) e gerar insights para ajudar na retenção de usuários.

## 🚀 Objetivo

A **Telecom X** enfrenta altos índices de evasão de clientes e precisa entender os fatores que influenciam esse comportamento. O projeto foca em aplicar o processo **ETL**:

- **Extração** dos dados de uma API via JSON.
- **Transformação** dos dados em um DataFrame estruturado.
- **Limpeza e tratamento** de dados aninhados.
- **Análise exploratória (EDA)** com gráficos e insights.
- **Geração de relatório com conclusões e sugestões**.

---

## 📁 Estrutura do Projeto
📂 Telecom-X-Churn-Analysis
---
├── TelecomX_Data.json        
├── TelecomX_Analysis.ipynb    
├── README.md                 

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- JSON

---

## 📌 Principais Passos Realizados

- ✅ Carregamento dos dados a partir de arquivo JSON.
- ✅ Transformação de colunas aninhadas (`customer`, `phone`, `internet`, `account`).
- ✅ Tratamento de valores nulos e conversão de tipos.
- ✅ Análise exploratória com `countplot`, `boxplot` e anotações nos gráficos.
- ✅ Geração de insights visuais sobre o comportamento de churn.

---

## 📈 Exemplos de Insights

- Clientes com contratos **mensais** são os que mais cancelam.
- Usuários de **fibra óptica** têm maior taxa de evasão.
- **Cobrança eletrônica** também está associada a maiores taxas de churn.
- O valor médio da mensalidade tende a ser maior entre clientes que cancelaram.

---

## 📄 Conclusão

A análise permitiu identificar **padrões de comportamento dos clientes** que ajudam a entender melhor os fatores associados à evasão. Esses resultados podem ser usados pela equipe de Data Science para:

- Criar modelos preditivos de churn.
- Desenvolver ações de retenção personalizadas.
- Testar estratégias como incentivo a contratos mais longos.

---

## 💡 Sugestões para a Empresa

- Oferecer **descontos ou bônus** para contratos de longa duração.
- Melhorar a experiência de clientes com internet de fibra óptica.
- Avaliar a usabilidade e confiabilidade do sistema de cobrança eletrônica.

---

## ✍️ Autor

**Ramires Rocha da Silva**  
Estudante de Engenharia Eletrônica – Universidade de Brasília (UnB)  
Participante do desafio de Data Science – ONE | TECH FOUNDATION - Especialização Data Science

---

## 📬 Contato

- [LinkedIn](https://www.linkedin.com/in/ramires-rocha-8a698a1b7/)
- [Email](mailto:ramiresrch15@gmail.com)

---

> Este projeto foi desenvolvido com fins educacionais e para prática de análise de dados reais em ambiente controlado.

