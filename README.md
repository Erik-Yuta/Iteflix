# 🎬 Iteflix — Plataforma de Catálogo de Filmes, Séries e Esportes

O **Iteflix** é um sistema web desenvolvido como trabalho acadêmico, simulando uma plataforma de catálogo de filmes, séries, conteúdo esportivo e páginas de itens populares.  
O projeto inclui autenticação, páginas organizadas por categoria, painel (dashboard) e integração com banco de dados MySQL.

---

## 🚀 Tecnologias Utilizadas

- **PHP**
- **HTML5**
- **CSS3**
- **MySQL**
- Servidor local: **XAMPP / WAMP / Laragon**
---

## 📌 Funcionalidades

✔️ Sistema de Login  
✔️ Dashboard do usuário  
✔️ Catálogo dividido por categorias:  
   - 🎥 Filmes  
   - 📺 Séries  
   - ⚽ Esportes  
   - ⭐ Populares  
✔️ Controle de sessão  
✔️ Banco de dados incluso (iteflix.sql)

---

## 📁 Estrutura do Projeto

```
Iteflix/
│
├── Seguranca/         # Arquivos de segurança e validação de login
├── filmes/            # Conteúdo de filmes
├── series/            # Conteúdo de séries
├── esportes/          # Conteúdos esportivos
├── populares/         # Itens populares
│
├── dashboard.php      # Painel do usuário
├── dashboard.css      # Estilos do dashboard
├── index.php          # Página inicial
├── login.php          # Tela de login
├── conexao.php        # Conexão com o MySQL
│
├── iteflix.sql        # Banco de dados
└── README.md
```

---

## 🛠️ Como Rodar o Projeto Localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/Erik-Yuta/Iteflix.git
```

### 2️⃣ Mover para o servidor local (XAMPP)
```
C:/xampp/htdocs/Iteflix
```

### 3️⃣ Importar o banco
- Acesse o phpMyAdmin  
- Crie um banco chamado **iteflix**  
- Importe o arquivo **iteflix.sql**

### 4️⃣ Executar no navegador
```
http://localhost/Iteflix
```

---

## 🎯 Objetivo do Projeto

Projeto desenvolvido para fins acadêmicos, com foco em:

- Prática de PHP  
- Manipulação de banco MySQL  
- Sistema de login  
- Organização de páginas e categorias  
- Desenvolvimento de layout básico  
