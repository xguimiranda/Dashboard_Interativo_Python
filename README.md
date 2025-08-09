<div align="center">
  <a href="https://dashboard-interativo-alura-gui.streamlit.app">
    
  </a>
</div>
<br>
<p align="center">
  <a href="https://dashboard-interativo-alura-gui.streamlit.app/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/website-%23007ACC?style=flat-square&logo=google-chrome&logoColor=white" alt="Site" />
  </a>
</p>



# 📊 Dashboard Interativo de Salários na Área de Dados

![Status](https://img.shields.io/badge/status-%20completo-green)
![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/streamlit-app-red?logo=streamlit)
![Licença](https://img.shields.io/badge/licença-MIT-green)

---

## 💡 Sobre o projeto
Este projeto foi desenvolvido durante a **Imersão de Dados com Python** da [Alura](https://www.alura.com.br/).

O objetivo é explorar e analisar dados salariais de profissionais da área de dados ao longo dos últimos anos, permitindo ao usuário **filtrar por ano, senioridade, tipo de contrato e tamanho da empresa** e visualizar métricas relevantes como:

- **Salário médio** e **máximo**
- **Total de registros** analisados
- **Cargo mais frequente**
- **Top 10 cargos por salário médio**
- **Distribuição de salários**

> O dataset consolidado foi salvo como `dados-imersao-final.csv` após transformações feitas nas primeiras aulas.

---

## 🌐 Acesso ao dashboard
Acesse a versão online do app:

🔗 **[Abrir no Streamlit](https://SEU-LINK-DO-STREAMLIT-AQUI)**

> Substitua o link acima pelo seu URL do Streamlit (ex.: `https://dashboard-interativo-alura-gui.streamlit.app`).

---

## ⚙️ Funcionalidades
- Filtros: **ano**, **senioridade**, **tipo de contrato**, **tamanho da empresa**.
- KPIs: **média**, **máximo**, **total de registros**, **cargo mais frequente**.
- Gráficos interativos (barras e histograma) para análise exploratória.
- Layout simples e responsivo com Streamlit.

---

## 🛠 Tecnologias utilizadas
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Streamlit](https://streamlit.io/)
- [Matplotlib](https://matplotlib.org/) / [Plotly](https://plotly.com/python/) *(se aplicável)*

---

## 📋 Pré-requisitos
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

# (Opcional, mas recomendado) Crie um ambiente virtual
python -m venv .venv

# Ative o ambiente virtual
# Windows (PowerShell):
.\.venv\Scripts\Activate.ps1
# Windows (CMD):
.\.venv\Scripts\activate.bat
# Linux/Mac:
source .venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
streamlit run app.py
```

---

## 🖼 Capturas de tela

> Salve as imagens na pasta `assets/` e mantenha os nomes abaixo (já incluídos neste pacote).

**Visão geral do dashboard**  
![Dashboard - Visão Geral](assets/dashboard-visao-geral.jpg)

**Página inicial do repositório**  
![Repositório - Home](assets/repo-home.jpg)

---

## 📂 Estrutura do repositório
```
Dashboard_Interativo_Python/
│
├── app.py                  # Código principal do dashboard
├── dados-imersao-final.csv # Base de dados utilizada
├── requirements.txt        # Dependências do projeto
├── README.md               # Documentação do projeto
└── assets/                 # Imagens e arquivos estáticos do README
```

---

## 🗺 Roadmap da Imersão
- **Aulas 1–3:** Limpeza, transformação e consolidação do dataset; exportação final em `dados-imersao-final.csv`.
- **Aula 4:** Construção do **dashboard interativo** em Streamlit com filtros e visualizações.
- **Aula 5 (opcional):** Publicação do app no **Streamlit Community Cloud** e ajuste fino da experiência.

---

## 🤝 Contribuindo
Contribuições são bem-vindas!  
1. Faça um fork
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit: `git commit -m 'feat: minha feature'`
4. Push: `git push origin minha-feature`
5. Abra um Pull Request

---

## 📄 Licença
Este projeto está sob a licença **MIT**.  
Sinta-se à vontade para reutilizar com os devidos créditos.

---

## 👤 Autor
**Guilherme Miranda**  
🔗 GitHub: [@xguimiranda](https://github.com/xguimiranda)  
🔗 LinkedIn: https://www.linkedin.com/in/SEU-PERFIL-AQUI
