# 📋 Relatório: Banco de Dados MySQL

## 🏭 1. Gerenciamento de Banco de Dados 

Comandos utilizados para iniciar o MySQL, criar, selecionar, consultar, alterar e remover bancos de dados e tabelas:

| AÇÃO / OBJETIVO | COMANDO SQL | DESCRIÇÃO |
|---|---|---|
| **Iniciar MySQL** | `mysql -u root` | Inicia o acesso ao servidor MySQL com o usuário root. |
| **Criar Banco** | `CREATE DATABASE nome_banco;` | Cria um novo banco de dados. |
| **Excluir Banco** | `DROP DATABASE nome_banco;` | Exclui um banco de dados e todo o seu conteúdo. |
| **Criar Tabela** | `CREATE TABLE tabela (coluna tipo);` | Cria uma nova tabela no banco de dados. |
| **Excluir Tabela** | `DROP TABLE tabela;` | Apaga uma tabela permanentemente. |
| **Inserir Dados** | `INSERT INTO tabela (colunas) VALUES (valores);` | Insere novos registros em uma tabela. |
| **Atualizar Dados** | `UPDATE tabela SET coluna = valor WHERE condicao;` | Atualiza dados existentes na tabela. |
| **Selecionar Dados** | `SELECT colunas FROM tabela;` | Seleciona e exibe dados de uma tabela. |
| **Selecionar Banco** | `USE nome_banco;` | Define o banco de dados ativo para o trabalho. |
| **Listar Bancos** | `SHOW DATABASES;` | Lista todos os bancos de dados existentes no servidor. |
| **Listar Tabelas** | `SHOW TABLES;` | Lista todas as tabelas do banco de dados selecionado. |
| **Ver Estrutura da Tabela** | `DESCRIBE tabela;` ou `DESC tabela;` | Mostra a estrutura, colunas e tipos de dados de uma tabela. |



