# Fast Seguros – Automação de Cotações

> **PT-BR:** Ferramenta em Python para automatizar o fluxo de cadastro e cotação de seguros (auto, frotas, vida e consórcio), integrando interface gráfica com planilhas Excel.  
> **EN:** Python automation tool to streamline insurance quotation workflows (auto, fleets, life, and consórcio), combining a GUI interface with Excel spreadsheets.

---

## 📌 Descrição | Description

**PT-BR**  
Este projeto foi desenvolvido como parte do **TCC de Ciência da Computação** e tem como objetivo **otimizar o fluxo de cotações** em uma corretora de seguros.  
A aplicação permite:

- Cadastro e validação de dados de clientes  
- Escolha do tipo de produto (Auto, Frota, Vida, Consórcio)  
- Registro estruturado das cotações em planilhas Excel  
- Interface amigável via **PySimpleGUI**

Os dados são organizados em:

- `Base_Clientes/Clientes.xlsx` – base geral de clientes  
- `Cotações_Clientes/Cotacoes_Auto.xlsx`  
- `Cotações_Clientes/Cotacoes_Frota.xlsx`  
- `Cotações_Clientes/Cotacoes_Vida.xlsx`  
- `Cotações_Clientes/Cotacoes_Consorcio.xlsx`  

**EN**  
This project was developed as part of a **Computer Science graduation thesis (TCC)** and aims to **optimize insurance quotation workflows** in a brokerage.  
The application provides:

- Client data entry and validation  
- Product selection (Auto, Fleet, Life, Consórcio)  
- Structured quotation records into Excel spreadsheets  
- User-friendly GUI with **PySimpleGUI**

Data is organized into:

- `Base_Clientes/Clientes.xlsx` – main clients database  
- `Cotações_Clientes/Cotacoes_Auto.xlsx`  
- `Cotações_Clientes/Cotacoes_Frota.xlsx`  
- `Cotações_Clientes/Cotacoes_Vida.xlsx`  
- `Cotações_Clientes/Cotacoes_Consorcio.xlsx`  

---

## 🧰 Stack

- **Python 3.x**
- **PySimpleGUI** (GUI)
- **pandas** (manipulação de dados / data handling)
- **openpyxl** (integração com Excel)

---

## ▶️ Como rodar a automação (código-fonte) | How to run (source code)

### PT-BR

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/Joaolbero/fast-seguros-automation.git
   cd fast-seguros-automation

2. **(Opcional, mas recomendado) Criar ambiente virtual**

python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
# source .venv/bin/activate

3. **Instalar dependências**

pip install -r requirements.txt

4. **Garantir a estrutura de pastas/arquivos**

• Base_Clientes/Clientes.xlsx
• Cotações_Clientes/*.xlsx

5. **Executar a aplicação**

python auto_seg.py

**EN**

1. **Clone the repository**

git clone https://github.com/Joaolbero/fast-seguros-automation.git
cd fast-seguros-automation


2. **(Optional but recommended) Create a virtual environment**

python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
# source .venv/bin/activate


3. **Install dependencies**

pip install -r requirements.txt


4. **Make sure the folder/file structure exists**

• Base_Clientes/Clientes.xlsx
• Cotações_Clientes/*.xlsx

5. **Run the application**

python auto_seg.py

💻 Executável para Windows | Windows executable

PT-BR
O repositório contém um executável gerado com PyInstaller:

auto_seg.exe (raiz do projeto)

dist/auto_seg.exe (build final)

Isso permite rodar a automação em máquinas Windows sem precisar instalar Python, desde que a estrutura de pastas/planilhas esteja correta.

EN
The repo includes a PyInstaller-built executable:

auto_seg.exe (project root)

dist/auto_seg.exe (final build)

This allows running the tool on Windows without installing Python, as long as the folder and spreadsheet structure is in place.

🗂️ Estrutura do projeto | Project structure

fast-seguros-automation/

├─ auto_seg.py

├─ auto_seg.exe

├─ requirements.txt

├─ pyproject.toml

├─ LICENSE

├─ Base_Clientes/

│  └─ Clientes.xlsx

├─ Cotações_Clientes/

│  ├─ Cotacoes_Auto.xlsx

│  ├─ Cotacoes_Consorcio.xlsx

│  ├─ Cotacoes_Frota.xlsx

│  └─ Cotacoes_Vida.xlsx

├─ build/             # artefatos do PyInstaller (pode ser ignorado no Git)

├─ dist/              # executável final (PyInstaller)

└─ Anotações/         # notas e arquivos auxiliares (opcional, para estudo)

📄 Licença | License

Este projeto é licenciado sob os termos da MIT License.
This project is licensed under the terms of the MIT License.
Consulte o arquivo LICENSE para mais detalhes.

👤 Autor | Author

João Vitor Albero — GitHub · LinkedIn