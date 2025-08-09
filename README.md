# 📊 Dashboard de Salários na Área de Dados

Este projeto é um **dashboard interativo** desenvolvido em **Python** com **Streamlit**, que permite explorar dados salariais de diferentes cargos da área de dados, filtrando por ano, senioridade, tipo de contrato e tamanho da empresa.  
O deploy está disponível em: **[Acessar Dashboard](https://python-deploy-dashboard.streamlit.app)**  

---

## 🚀 Funcionalidades

- **Filtros Interativos**:  
  - Ano  
  - Senioridade  
  - Tipo de contrato  
  - Tamanho da empresa  

- **Métricas Gerais (KPIs)**:  
  - Salário médio anual (USD)  
  - Salário máximo anual (USD)  
  - Total de registros  
  - Cargo mais frequente  

- **Visualizações Gráficas**:  
  - Top 10 cargos por salário médio  
  - Distribuição de salários  
  - Proporção dos tipos de trabalho (presencial, remoto, híbrido)  
  - Mapa de salários médios para Cientistas de Dados por país  

- **Tabela de Dados Detalhados** com possibilidade de rolagem e filtragem.

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.x](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)

---

## 📂 Estrutura do Projeto

```

📁 dashboard-salarios
│-- app.py               # Código principal do dashboard
│-- requirements.txt     # Dependências do projeto
│-- README.md            # Documentação do projeto

````

---

## 📦 Instalação e Execução Local

1. **Clone este repositório**:
```bash
git clone https://github.com/seu-usuario/dashboard-salarios.git
cd dashboard-salarios
````

2. **Crie e ative um ambiente virtual**:

```bash
python -m venv .venv
source .venv/Scripts/activate  # Windows (Git Bash)
# ou
.venv\Scripts\activate         # Windows (cmd/powershell)
# ou
source .venv/bin/activate      # Linux/Mac
```

3. **Instale as dependências**:

```bash
pip install -r requirements.txt
```

4. **Execute o Streamlit**:

```bash
streamlit run app.py
```

---

## 🌐 Deploy

O projeto está hospedado no **Streamlit Cloud**:
🔗 **[Acessar Dashboard Online](https://python-deploy-dashboard.streamlit.app)**

---

## 📊 Fonte dos Dados

Os dados utilizados neste dashboard vêm do repositório público:
[https://github.com/vqrca/dashboard\_salarios\_dados](https://github.com/vqrca/dashboard_salarios_dados)

---

## 📜 Licença

Este projeto é de uso livre para fins educacionais e não possui licença comercial.

---

✍️ Desenvolvido com ❤️ utilizando **Python + Streamlit**.
