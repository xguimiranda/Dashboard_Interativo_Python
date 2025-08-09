# 📊 Dashboard Interativo de Salários na Área de Dados

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/streamlit-app-red?logo=streamlit)
![Licença](https://img.shields.io/badge/licença-MIT-green)

---

## 📌 Índice
1. [Sobre o projeto](#sobre-o-projeto)
2. [Acesso ao dashboard](#acesso-ao-dashboard)
3. [Funcionalidades](#funcionalidades)
4. [Tecnologias utilizadas](#tecnologias-utilizadas)
5. [Pré-requisitos](#pré-requisitos)
6. [Como executar o projeto localmente](#como-executar-o-projeto-localmente)
7. [Capturas de tela](#capturas-de-tela)
8. [Estrutura do repositório](#estrutura-do-repositório)
9. [Contribuindo](#contribuindo)
10. [Licença](#licença)
11. [Autor](#autor)

---

## 💡 Sobre o projeto
Este projeto foi desenvolvido durante a **Imersão de Dados com Python** da [Alura](https://www.alura.com.br/).

O objetivo é explorar e analisar dados salariais de profissionais da área de dados ao longo dos últimos anos, permitindo ao usuário **filtrar por ano, senioridade, tipo de contrato e tamanho da empresa** e visualizar métricas relevantes como:

- Salário médio e máximo
- Cargo mais frequente
- Distribuição de salários
- Top 10 cargos por salário médio

---

## 🌐 Acesso ao dashboard
Você pode acessar o dashboard online clicando no link abaixo:

🔗 **[Acessar Dashboard no Streamlit](https://SEU-LINK-DO-STREAMLIT-AQUI)**

---

## ⚙️ Funcionalidades
- Filtro por **ano**, **senioridade**, **tipo de contrato** e **tamanho da empresa**.
- Cálculo dinâmico de **média salarial**, **máximo**, **total de registros** e **cargo mais frequente**.
- Visualização em **gráficos interativos**.
- Interface responsiva e intuitiva.

---

## 🛠 Tecnologias utilizadas
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Streamlit](https://streamlit.io/)
- [Matplotlib](https://matplotlib.org/) / [Plotly](https://plotly.com/python/) *(se aplicável)*

---

## 📋 Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina:
- **Git**
- **Python 3.10+**
- **Pip**

---

## 🚀 Como executar o projeto localmente
```bash
# Clone este repositório
git clone https://github.com/xguimiranda/Dashboard_Interativo_Python.git

# Acesse a pasta do projeto
cd Dashboard_Interativo_Python

# Crie um ambiente virtual
python -m venv .venv

# Ative o ambiente virtual
# Windows:
.\.venv\Scripts\activate
# Linux/Mac:
source .venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
streamlit run app.py
🖼 Capturas de tela
📌 Adicione suas imagens na pasta assets/ e atualize os links abaixo:



📂 Estrutura do repositório
php
Copy
Edit
Dashboard_Interativo_Python/
│
├── app.py                  # Código principal do dashboard
├── dados-imersao-final.csv # Base de dados utilizada
├── requirements.txt        # Dependências do projeto
├── README.md               # Documentação do projeto
└── assets/                 # Imagens e outros arquivos estáticos
🤝 Contribuindo
Contribuições são sempre bem-vindas!
Se você tiver alguma ideia para melhorar o projeto:

Faça um fork do repositório

Crie uma branch para sua feature (git checkout -b minha-feature)

Commit suas alterações (git commit -m 'Adiciona nova feature')

Envie para o GitHub (git push origin minha-feature)

Abra um Pull Request

📄 Licença
Este projeto está sob a licença MIT.
Veja o arquivo LICENSE para mais detalhes.

👤 Autor
Guilherme Miranda
📧 [Seu e-mail aqui]
🔗 LinkedIn | GitHub