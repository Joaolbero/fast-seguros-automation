<p align="center">
  <img src="./icon/icon.png" alt="Project Icon" width="200" height="200">
</p>

# ⚡ Fast Seguros Automation / Insurance Automation Tool

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-active-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/PROJECT_TYPE-automation-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/TECH_STACK-Python,_PySimpleGUI,_Pandas,_OpenPyXL-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/DEPENDENCIES-3-lightgrey?style=for-the-badge">
  <img src="https://img.shields.io/badge/FEATURES-GUI,_Excel_Integration,_Client_Validation-lightgrey?style=for-the-badge">
  <img src="https://img.shields.io/badge/LICENSE-MIT-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/VERSION-1.0.0-red?style=for-the-badge">
  <a href="https://github.com/Joaolbero">
    <img src="https://img.shields.io/badge/AUTHOR-João_Albero-black?style=for-the-badge">
  </a>
  <img src="https://img.shields.io/github/last-commit/Joaolbero/fast-seguros-automation?style=for-the-badge">
</p>

---

## 📄 Descrição / Description

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| Automação em Python criada para otimizar o fluxo de cotações de seguros (Auto, Frota, Vida, Consórcio). Usa interface gráfica com PySimpleGUI e integra diretamente com planilhas Excel, fazendo parte do TCC em Ciência da Computação. | Python automation tool built to optimize insurance quotation workflows (Auto, Fleet, Life, Consórcio). Uses a GUI built with PySimpleGUI and integrates directly with Excel spreadsheets as part of a Computer Science graduation thesis project. |

---

## ✨ Funcionalidades / Features

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| • Cadastro e validação de clientes<br>• Escolha do tipo de produto (Auto, Frota, Vida, Consórcio)<br>• Registro das cotações em planilhas Excel organizadas por categoria<br>• Interface amigável em PySimpleGUI | • Client registration and validation<br>• Product selection (Auto, Fleet, Life, Consórcio)<br>• Storing quotations in Excel spreadsheets organized by category<br>• User-friendly GUI using PySimpleGUI |

---

## ▶️ Como executar / How to run

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| 1. Clonar o repositório<br>2. (Opcional) Criar ambiente virtual<br>3. Instalar dependências<br>4. Garantir a estrutura de planilhas<br>5. Executar `auto_seg.py` | 1. Clone the repository<br>2. (Optional) Create a virtual environment<br>3. Install dependencies<br>4. Ensure spreadsheet structure<br>5. Run `auto_seg.py` |

### 🔧 Comandos principais / Main commands

Clone do repositório:

    git clone https://github.com/Joaolbero/fast-seguros-automation.git
    cd fast-seguros-automation

Criar ambiente virtual (opcional):

    python -m venv .venv

Ativar venv (Windows):

    .venv\Scripts\activate

Instalar dependências:

    pip install -r requirements.txt

Executar aplicação:

    python auto_seg.py

---

## 💽 Executável para Windows / Windows executable

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| O repositório inclui um executável gerado com PyInstaller, permitindo rodar a automação sem instalar Python, desde que a estrutura de pastas e planilhas esteja correta. | The repository includes a PyInstaller-built executable, allowing the automation to run without Python as long as the folder and spreadsheet structure is in place. |

Arquivos principais do executável:

    auto_seg.exe
    dist/auto_seg.exe

---

## 🗂️ Estrutura do projeto / Project structure

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| auto_seg.py<br>auto_seg.exe<br>requirements.txt<br>pyproject.toml<br>Base_Clientes/Clientes.xlsx<br>Cotações_Clientes/Cotacoes_Auto.xlsx<br>Cotações_Clientes/Cotacoes_Frota.xlsx<br>Cotações_Clientes/Cotacoes_Vida.xlsx<br>Cotações_Clientes/Cotacoes_Consorcio.xlsx<br>build/ (artefatos PyInstaller)<br>dist/ (build final)<br>Anotações/ | auto_seg.py<br>auto_seg.exe<br>requirements.txt<br>pyproject.toml<br>Base_Clientes/Clientes.xlsx<br>Cotações_Clientes/Cotacoes_Auto.xlsx<br>Cotações_Clientes/Cotacoes_Frota.xlsx<br>Cotações_Clientes/Cotacoes_Vida.xlsx<br>Cotações_Clientes/Cotacoes_Consorcio.xlsx<br>build/ (PyInstaller artifacts)<br>dist/ (final build)<br>Anotações/ |

---

## 📄 Licença / License

| 🇧🇷 PT-BR | 🇺🇸 EN |
| --- | --- |
| Projeto licenciado sob os termos da MIT License. Consulte o arquivo `LICENSE` para mais detalhes. | Project licensed under the terms of the MIT License. See the `LICENSE` file for more details. |

---

## 👤 Autor / Author

Criado por João Albero · 2025  
Created by João Albero · 2025