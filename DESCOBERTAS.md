# 🔑 Diferença entre Chave Primária e Chave Estrangeira

| **Chave Primária (`PRIMARY KEY`)** | **Chave Estrangeira (`FOREIGN KEY`)** |
|---|---|
| Identifica cada registro de forma única. | Liga uma tabela a outra. |
| Não pode ter valores repetidos. | Pode ter valores repetidos. |
| Identifica o registro da própria tabela. | Faz referência a um registro de outra tabela. |
| Geralmente é o `id`. | Geralmente é algo como `usuario_id` ou `aluno_id`. |
| Existe para garantir a identificação dos dados. | Existe para criar relacionamentos entre tabelas. |

