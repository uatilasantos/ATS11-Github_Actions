# 🚀 ATS11 - GitHub Actions com FastAPI

Projeto desenvolvido para demonstrar a utilização de Integração Contínua (CI) com GitHub Actions em uma API simples utilizando FastAPI.

---

# 🛠️ Tecnologias Utilizadas

* 🐍 Python
* ⚡ FastAPI
* 🧪 Pytest
* 🔄 GitHub Actions

---

# 📌 Funcionalidades

A API possui as seguintes rotas:

```http
GET /
GET /somar/{a}/{b}
GET /multiplicar/{a}/{b}
```

---

# ▶️ Executando o Projeto

## 📦 Criar ambiente virtual

### Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

---

## 📥 Instalar dependências

```bash
pip install -r requirements.txt
```

---

## 🚀 Executar API

```bash
fastapi run main.py
```

ou

```bash
uvicorn main:app --reload
```

---

## 🧪 Executar testes

```bash
pytest test_main.py
```

---

# 🔄 CI com GitHub Actions

O workflow configurado no GitHub Actions realiza:

* ✅ Instalação das dependências
* ✅ Execução dos testes automatizados
* ✅ Testes em múltiplas versões do Python (3.10, 3.11 e 3.12)
* ✅ Teste de integração utilizando curl

Arquivo utilizado:

```bash
.github/workflows/ci.yml
```

---

# 🎯 Objetivo da Atividade

Simular um fluxo profissional utilizando:

* 🔹 Testes automatizados
* 🔹 Pull Requests
* 🔹 Proteção da branch main
* 🔹 Integração Contínua com GitHub Actions

---

# 👨‍💻 Autor

Uatila dos Santos Silva
