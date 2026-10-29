# ☕ CoffeeAI — Visualizador de Dados

Aplicação web em **Streamlit** para carregar planilhas Excel (`.xlsx`) e explorar rapidamente os dados do mercado de café: pré-visualização, resumo estatístico, filtros e gráficos.

## ✨ Funcionalidades

- Upload de arquivos `.xlsx`.
- Pré-visualização das primeiras linhas e resumo estatístico (`describe`).
- Filtro por coluna e valor.
- Gráficos de **linha** e **barra** com seleção dos eixos X e Y (o eixo Y precisa ser numérico).
- Mensagens de erro claras para colunas inválidas.

## 🛠️ Tecnologias

- Python 3.9+
- [Streamlit](https://streamlit.io/)
- [pandas](https://pandas.pydata.org/) e openpyxl (leitura de Excel)
- Pillow

## 🚀 Como executar

```bash
git clone https://github.com/pedrobernardone/coffee-ai.git
cd coffee-ai

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

pip install streamlit pandas pillow openpyxl
streamlit run main.py
```

A aplicação abrirá no navegador (por padrão em `http://localhost:8501`).

## 📁 Estrutura

```text
├── main.py      # Aplicação Streamlit
├── assets/      # Favicon
└── README.md
```

## 🔐 Privacidade

Os arquivos enviados são processados apenas na sessão em execução e não são armazenados pela aplicação.

## 👤 Autor

**Pedro Bernardone**
