# Iteflix

O Iteflix é um sistema simples desenvolvido em PHP, usando um banco de dados MySQL.  
O projeto contém a pasta principal do sistema (Iteflix) e o arquivo de banco de dados (iteflix.sql).

------------------------------------------------------------

## Estrutura do Projeto

Iteflix/
- Iteflix/        -> Arquivos principais do sistema
- iteflix.sql     -> Banco de dados MySQL

------------------------------------------------------------

## Como Executar o Projeto

1. Clone o repositório:
   git clone https://github.com/Erik-Yuta/Iteflix.git

2. Entre na pasta do projeto:
   cd Iteflix

3. Crie um banco de dados no MySQL (exemplo: iteflix_db)

4. Importe o arquivo SQL:
   mysql -u SEU_USUARIO -p iteflix_db < iteflix.sql

5. Configure a conexão com o banco no arquivo de configuração do sistema:
   host: localhost
   usuário: root
   senha: (deixe vazio se usar XAMPP)
   banco: iteflix_db

6. Coloque o projeto no servidor local (XAMPP, WAMP ou Laragon)

7. Acesse no navegador:
   http://localhost/Iteflix/Iteflix/

------------------------------------------------------------

## Tecnologias Usadas

- PHP
- MySQL
- HTML
- CSS

------------------------------------------------------------

## Possíveis Melhorias Futuras

- Sistema de login
- Painel administrativo
- Layout responsivo
- Organização em MVC
- Mais validações e segurança

------------------------------------------------------------
