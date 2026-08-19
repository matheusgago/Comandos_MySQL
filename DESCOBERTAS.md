## 🔑 Diferença entre Chave Primária e Chave Estrangeira

| **Chave Primária (`PRIMARY KEY`)** | **Chave Estrangeira (`FOREIGN KEY`)** |
|---|---|
| Identifica cada registro de forma única. | Liga uma tabela a outra. |
| Não pode ter valores repetidos. | Pode ter valores repetidos. |
| Identifica o registro da própria tabela. | Faz referência a um registro de outra tabela. |
| Geralmente é o `id`. | Geralmente é algo como `usuario_id` ou `aluno_id`. |
| Existe para garantir a identificação dos dados. | Existe para criar relacionamentos entre tabelas. |


## 🔑 O que descobri sobre id

O id normalmente é usado para identificar cada registro de uma tabela de forma única. Ele geralmente é definido como uma chave primária (PRIMARY KEY) e pode usar AUTO_INCREMENT para que o banco gere os números automaticamente.


## 📖 sobre o mysql
Banco de dados

É onde ficam organizadas as tabelas.

Tabela

Armazena os registros e as colunas.

Coluna

Representa um tipo de informação.
