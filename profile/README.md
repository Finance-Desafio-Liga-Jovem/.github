# Finance

---

## 🇬🇧 English

### 📖 Project Overview
**Financial Organizer** is our submission for **Desafio Liga Jovem 2025**, promoted by Sebrae. We are a team of students from **Universidade Católica de Brasília (UCB)**. Our goal is to tackle Brazil’s widespread household debt problem (nearly 70% of the population), by providing a simple, user-friendly web application to register and organize income, expenses and debts—far more engaging than a boring spreadsheet.

### 🚀 Features
- **User Registration & Authentication**
- **Dashboard** with overview of income, expenses and outstanding debts
- **Transaction Management**: add, edit, categorize earnings and payments
- **Debt Tracker**: schedule payment dates, view amortization
- **Reports & Charts**: monthly summaries and trend visuals

### 🛠️ Technologies
- **Frontend**: Angular 19 (standalone components, Angular Material, Bootstrap, SweetAlert2)
- **Backend**: Java Spring Boot
- **Database**: PostgreSQL
- **Hosting**: _(TBD)_

### 🔧 Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR_ORG/financial-organizer.git
   cd financial-organizer
   ```

2. **Backend (Spring Boot)**
   - Configure your PostgreSQL database (create database and user).
   - Copy `backend/.env.example` to `backend/.env` and fill in your DB credentials.
   - From `/backend` folder:
     ```bash
     ./mvnw clean install
     ./mvnw spring-boot:run
     ```
   - App will start at `http://localhost:8080`.

3. **Frontend (Angular)**
   - From `/frontend` folder:
     ```bash
     npm install
     ng serve --open
     ```
   - App will open at `http://localhost:4200`.

### 📝 Usage
1. Register a new account or log in.
2. On your dashboard, start adding your income, expenses and debts.
3. Use the **Reports** tab to visualize monthly trends.
4. Schedule debt payments and track progress until fully paid off.

### 🤝 Contributing
We welcome community contributions!
1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) and [Contribution Guidelines](CONTRIBUTING.md).

### 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🇧🇷 Português

### 📖 Visão Geral do Projeto
**Organizador Financeiro** é nossa proposta para o **Desafio Liga Jovem 2025**, promovido pelo Sebrae. Somos uma equipe de estudantes da **Universidade Católica de Brasília (UCB)**. Nosso objetivo é enfrentar o problema generalizado de endividamento familiar no Brasil (quase 70% da população), oferecendo uma aplicação web simples e amigável para registrar e organizar ganhos, despesas e dívidas—muito mais atraente que uma planilha entediante.

### 🚀 Funcionalidades
- **Cadastro e Autenticação de Usuário**
- **Dashboard** com visão geral de ganhos, despesas e dívidas em aberto
- **Gerenciamento de Transações**: adicionar, editar e categorizar rendimentos e pagamentos
- **Rastreador de Dívidas**: agendar datas de pagamento e acompanhar amortização
- **Relatórios e Gráficos**: resumos mensais e visuais de tendências

### 🛠️ Tecnologias
- **Frontend**: Angular 19 (componentes standalone, Angular Material, Bootstrap, SweetAlert2)
- **Backend**: Java Spring Boot
- **Banco de Dados**: PostgreSQL
- **Hospedagem**: _(a definir)_

### 🔧 Instalação e Configuração

1. **Clone o repositório**
   ```bash
   git clone https://github.com/YOUR_ORG/financial-organizer.git
   cd financial-organizer
   ```

2. **Backend (Spring Boot)**
   - Configure seu banco PostgreSQL (crie database e usuário).
   - Copie `backend/.env.example` para `backend/.env` e preencha as credenciais do BD.
   - No diretório `/backend`:
     ```bash
     ./mvnw clean install
     ./mvnw spring-boot:run
     ```
   - A aplicação iniciará em `http://localhost:8080`.

3. **Frontend (Angular)**
   - No diretório `/frontend`:
     ```bash
     npm install
     ng serve --open
     ```
   - A aplicação abrirá em `http://localhost:4200`.

### 📝 Como Usar
1. Cadastre-se ou faça login.
2. No dashboard, comece a adicionar ganhos, despesas e dívidas.
3. Use a aba **Relatórios** para visualizar tendências mensais.
4. Agende pagamentos de dívidas e acompanhe até quitação total.

### 🤝 Contribuindo
Contribuições são bem-vindas!
1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b feature/sua-funcionalidade`
3. Faça commit das suas alterações: `git commit -m "Adiciona nova funcionalidade"`
4. Envie para sua branch: `git push origin feature/sua-funcionalidade`
5. Abra um Pull Request

Siga nosso [Código de Conduta](CODE_OF_CONDUCT.md) e as [Diretrizes de Contribuição](CONTRIBUTING.md).

### 📜 Licença
Este projeto é licenciado sob a MIT License. Veja [LICENSE](LICENSE) para mais detalhes.
