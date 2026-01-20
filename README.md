# 🏛️ Triagem Inteligente - PC Brasília (Demo)

Este projeto é uma aplicação web desenvolvida para a disciplina de **Fundamentos de Deep Learning & Prompt Engineering**. A ferramenta utiliza Machine Learning para classificar a 
prioridade de ocorrências policiais e um sistema de Mini-RAG para fornecer orientações de procedimentos baseadas em uma base de conhecimento.

## 🚀 Funcionalidades

- **Classificação de Prioridade:** Um modelo de Random Forest que analisa o tipo de crime, local, período e outros fatores para prever se a prioridade é Alta, Média ou Baixa.
- **Assistente Inteligente (Mini-RAG):** Uma base de conhecimento que retorna procedimentos específicos (ex: Lei Maria da Penha) ao detectar palavras-chave na consulta do usuário.
- **Interface Interativa:** Desenvolvida inteiramente em Python com Streamlit.

## 🛠️ Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) (Interface Web e Deploy)
- [Scikit-Learn](https://scikit-learn.org/) (Pipeline de Machine Learning e Random Forest)
- [Pandas](https://pandas.pydata.org/) & [Numpy](https://numpy.org/) (Manipulação de dados)

## 📁 Estrutura de Arquivos

- `app.py`: Código fonte da aplicação e lógica do modelo.
- `requirements.txt`: Lista de dependências para o ambiente de execução.

## 🔗 Acesse a Aplicação

Acesse o projeto rodando ao vivo aqui:  
👉 https://pcbrasilia-triagem-ia-drdbcnyhv5yxthbtbuqgq2.streamlit.app/

---
Desenvolvido por **Bruno Sampaio** *Estudante de Análise e Desenvolvimento de Sistemas*
