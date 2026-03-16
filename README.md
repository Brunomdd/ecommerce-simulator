# 🛒 Sistema E-commerce Simples

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)](https://python.org)
[![License MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Simulador **CLI** de compras online em Python puro! Catálogo, carrinho inteligente, validações e **estoque persistente via JSON**.

## ✨ Funcionalidades
- 📋 Catálogo: lista produtos (iPhone, TV, etc.)
- 🛍️ Carrinho: adiciona/atualiza com validação estoque
- ✅ `leiaInt()`: entradas seguras
- 💳 Finalizar: calcula total, desconta estoque, limpa carrinho
- 💾 Salva `ecommerce.json` automaticamente

## 🚀 Como Rodar
```bash
git clone https://github.com/seuusuario/sistema-ecommerce
cd sistema-ecommerce
python main.py
Exemplo Menu:

text
1 - Catálogo
2 - Adicionar ao carrinho  
3 - Ver carrinho
4 - Finalizar compra
5 - Sair
📁 Estrutura
text
├── main.py      # 💻 Código principal
├── README.md    # 📖 Este guia
├── .gitignore   # 🗑️ Ignora arquivos
├── LICENSE      # ⚖️ MIT
└── requirements.txt
👨‍💻 Sobre
Bruno - Estudante TI 5º semestre UNICSUL/SP
Foco: Python, JSON, modularização, exceções.

GitHub stars

Feito com ❤️ em São Paulo! 🤝 PRs bem-vindas!

text

## 2. .gitignore (Novo arquivo)
Python
pycache/
*.py[cod]
*$py.class
.env
.venv/

Dados locais
ecommerce.json

IDEs
.vscode/
.idea/
*.swp
.DS_Store

text

## 3. requirements.txt
Projeto usa só stdlib Python!
Sem dependências externas
text

## 4. Comando Final Local
```bash
git add .
git commit -m "docs: adiciona README, gitignore e requirements"
git push
