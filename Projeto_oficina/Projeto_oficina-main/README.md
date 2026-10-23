# ⚙️ Oficina Mecânica — SAEP / SENAI

<p align="center">
  <img src="static/img/banner.png" alt="Banner Oficina Mecânica" width="100%">
</p>

<p align="center">
  <strong>Mais organização. Mais controle. Mais resultados.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## 📌 Sobre o projeto

O **Oficina Mecânica** é um sistema web desenvolvido no contexto acadêmico do **SAEP / SENAI**, com o objetivo de facilitar o gerenciamento das atividades de uma oficina mecânica.

A aplicação utiliza Python no backend, páginas HTML na interface e MySQL para armazenar e organizar os dados, proporcionando uma estrutura para administrar clientes, veículos e agendamentos de serviços.

## ✨ Funcionalidades

| Recurso | Descrição |
|---|---|
| 🔐 Autenticação | Login e controle de acesso por sessão |
| 👥 Clientes | Cadastro, consulta, edição e exclusão |
| 🚘 Veículos | Gerenciamento de veículos vinculados aos clientes |
| 📅 Agendamentos | Organização de serviços e datas |
| 📊 Dashboard | Visualização de informações gerais do sistema |
| 🗄️ Banco de dados | Persistência das informações utilizando MySQL |
| 🔒 Segurança | Hash de senhas com Bcrypt |

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem utilizada no backend.
- **Flask:** framework para criação da aplicação web.
- **MySQL:** banco de dados relacional.
- **mysql-connector-python:** integração entre Python e MySQL.
- **Bcrypt:** geração e verificação de hashes.
- **HTML5:** estrutura das páginas.
- **CSS3:** estilização da interface.
- **JavaScript:** interatividade no frontend.
- **Jinja2:** renderização dinâmica dos templates.

## 📂 Estrutura do projeto

```text
oficina/
├── __pycache__/
├── static/
│   ├── css/
│   ├── js/
│   └── img/
│       └── banner.png
├── templates/
│   ├── agendamentos.html
│   ├── base.html
│   ├── clientes.html
│   ├── dashboard.html
│   ├── login.html
│   ├── principal.html
│   └── veiculos.html
├── agendamento.py
├── app.py
├── autenticacao.py
├── banco.py
├── clientes.py
├── db.sql
├── guia_passo_a_passo_aula.md
├── rotas.py
└── veiculos.py
```

## 🚀 Como executar

### 1. Pré-requisitos

Antes de iniciar, instale:

- Python 3
- MySQL Server
- Navegador atualizado

### 2. Instale as dependências

Abra o terminal na pasta do projeto e execute:

```bash
pip install flask mysql-connector-python bcrypt
```

### 3. Configure o banco de dados

Inicie o MySQL e execute o arquivo `db.sql` utilizando o MySQL Workbench ou outro cliente compatível.

Verifique se o banco, o usuário e a senha correspondem às configurações definidas em `banco.py`.

### 4. Execute a aplicação

No terminal, dentro da pasta `oficina`, execute:

```bash
python app.py
```

### 5. Acesse o sistema

Abra o navegador no endereço local configurado pela aplicação. Com a configuração padrão do Flask:

```text
http://127.0.0.1:5000
```

## 🗄️ Banco de dados

O banco de dados organiza as informações utilizadas pelo sistema. Entre as entidades previstas estão:

- **Usuários:** informações de acesso.
- **Clientes:** dados cadastrais.
- **Veículos:** informações dos veículos e seus proprietários.
- **Agendamentos:** serviços, datas, status e valores estimados.

O arquivo `db.sql` contém o script utilizado para configurar o banco de dados.

## 📁 Principais arquivos

| Arquivo | Responsabilidade |
|---|---|
| `app.py` | Inicialização da aplicação |
| `banco.py` | Conexão com o MySQL |
| `autenticacao.py` | Autenticação de usuários |
| `clientes.py` | Operações de clientes |
| `veiculos.py` | Operações de veículos |
| `agendamento.py` | Operações de agendamentos |
| `rotas.py` | Definição das rotas |
| `db.sql` | Script do banco de dados |

## 🎯 Objetivo acadêmico

Aplicar conhecimentos de Desenvolvimento de Sistemas na construção de uma aplicação web, integrando backend, frontend, banco de dados relacional e mecanismos de autenticação.

## 🏫 Instituição

<p align="center">
  <strong>SENAI — Serviço Nacional de Aprendizagem Industrial</strong><br>
  Projeto acadêmico desenvolvido no contexto do SAEP.
</p>

---

<p align="center">
  ⚙️ <strong>Oficina Mecânica</strong><br>
  <em>Tecnologia a serviço da mecânica!</em>
</p>

