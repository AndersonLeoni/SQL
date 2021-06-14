# SQL

Repositório voltado aos estudos de SQL e PL/SQL

## INNER JOIN
O INNER JOIN é o método de junção de tabelas mais conhecido. Ele retorna as informações que são comuns entre duas ou mais tabelas.

Exemplo da instrução:

```sql
SELECT A.NOME, B.HOBBY FROM TABELA_ESQUEDAR A 
INNER JOIN TABELA_DIREITA B 
ON A.INDENTIFICADOR = B.IDENTIFICADOR
```
