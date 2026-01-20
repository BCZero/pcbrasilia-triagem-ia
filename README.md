# 🏛️ Triagem Inteligente - PCDF (Demo)

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


## 💻 Como Rodar o Projeto Localmente

Siga os passos abaixo para executar a aplicação em sua máquina:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/pcbrasilia-triagem-ia.git](https://github.com/SEU-USUARIO/pcbrasilia-triagem-ia.git)
   cd pcbrasilia-triagem-ia


2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
  python -m venv venv

  # No Windows:
  .\venv\Scripts\activate
  
  # No Linux/Mac:
  source venv/bin/activate
```

3. Instale dependências
```bash
pip install -r requirements.txt
```

4. Execute a aplicação
```bash
streamlit run app.py
```
5. Acesse no navegador: O Streamlit abrirá automaticamente uma aba em http://localhost:8501.

Desenvolvido por **Bruno Sampaio** *Estudante de Análise e Desenvolvimento de Sistemas*
