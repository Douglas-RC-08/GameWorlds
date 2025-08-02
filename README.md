# 🎮 GameWorlds

Sistema web completo desenvolvido como projeto acadêmico do curso de Cibersegurança da PUCPR, com foco em **práticas seguras de desenvolvimento**, **gestão de projeto com SCRUM** e **aplicação real de conceitos de segurança cibernética**.

---

## 🧠 Objetivo

O **GameWorlds** permite que usuários se cadastrem, adicionem jogos, façam avaliações e interajam com a comunidade. O projeto também enfatiza a **proteção de dados sensíveis**, **responsividade** e **segurança ponta-a-ponta**.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5, CSS3, JavaScript**
- **PHP com MySQL**
- **Criptografia híbrida (AES + RSA)**
- **Hash de senhas com bcrypt**
- **Expressões Regulares para validação**
- **Esteganografia para credenciais**
- **Git + Trello + Metodologia SCRUM**

---

## 🔐 Funcionalidades de Segurança Implementadas

- ✅ Validação de campos com expressões regulares (e-mail, senha, CPF/CNPJ, telefone)
- ✅ Exigência de senhas fortes no cadastro
- ✅ Senhas armazenadas com **função HASH**
- ✅ Confirmação de cadastro por e-mail
- ✅ **Autenticação em dois fatores (2FA)**
- ✅ Criptografia híbrida de ponta-a-ponta (com IV aleatório, AES + RSA e padding)
- ✅ Sessão com expiração automática definida pela equipe
- ✅ Proteção de URLs para usuários autenticados
- ✅ Usuário do MySQL com **permissões restritas**
- ✅ Credenciais do banco armazenadas em arquivo separado usando esteganografia

---

## 📄 Estrutura do Projeto

- GameWorlds/
- ├── frontend/ # HTML/CSS/JS das páginas
- ├── backend/ # Scripts PHP de autenticação e persistência
- ├── assets/ # Imagens e ícones de jogos
- ├── config/ # Configuração do BD com esteganografia
- ├── sql/ # Scripts de criação do banco
- └── README.md


---

## ✅ Requisitos Atendidos (por SPRINT)

### 🟦 SPRINT 1
- Página de cadastro e login de usuário
- Recuperação de senha por e-mail
- Confirmação de conta por e-mail
- Responsividade completa do sistema
- Senha forte + HASH + 2FA + Expressões regulares

### 🟧 SPRINT 2
- Criação de usuário com permissão limitada no MySQL
- Expiração automática da sessão
- Proteção de páginas com autenticação obrigatória
- Esteganografia no `config.php`

### 🟥 SPRINT 3
- Criptografia híbrida de ponta-a-ponta (front ⇄ back)
- AES com IV aleatório, chave simétrica e padding

---

## 🧪 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/Douglas-RC-08/GameWorlds.git
   
2. Desoculte/extraia o config.php com as credenciais via esteganografia (documentação incluída).

3. Importe o banco de dados com o arquivo sql/script.sql.

4. Inicie o servidor local (XAMPP, WAMP ou outro).
