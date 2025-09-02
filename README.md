# 🚀 Flask Hello World com várias dependências  

[![Python](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)  
[![Flask](https://img.shields.io/badge/flask-3.0-brightgreen.svg)](https://flask.palletsprojects.com/)  
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)  
[![Lint](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)  
[![Tests](https://img.shields.io/badge/tests-passing-brightgreen.svg)](#)  
[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](https://www.docker.com/)  

---

## 📖 Sobre o projeto
Este é um projeto básico em **Flask** que gera uma página simples de **"Hello World"**,  
mas vem acompanhado de várias dependências no `requirements.txt` para treinar:  
- Ambientes virtuais  
- CI/CD com GitHub Actions  
- Dependabot  
- Docker  

---

## 🛠️ Como rodar localmente

```bash
# cria venv
python3 -m venv .venv
source .venv/bin/activate   # Linux/Mac
# no Windows: .venv\Scripts\activate

# instala dependências
pip install -r requirements.txt

# roda o app
python app.py
```

Acesse no navegador: 👉 http://localhost:5000  

---

## 🐳 Rodando com Docker

```bash
docker build -t flask-hello .
docker run -p 5000:5000 flask-hello
```

---

## 📦 Dependências principais

- Flask  
- Gunicorn  
- Requests  
- Pandas + Numpy  
- SQLAlchemy + Psycopg2  
- Redis + Celery  
- Pytest, Black, Flake8  

---

## 🤝 Contribuindo

1. Faça um fork  
2. Crie uma branch (`git checkout -b feature/nova-feature`)  
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)  
4. Faça push (`git push origin feature/nova-feature`)  
5. Abra um Pull Request  

---

## 📜 Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.  
