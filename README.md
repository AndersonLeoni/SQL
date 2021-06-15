# SQL

Repositório voltado aos estudos de SQL e PL/SQL

## INNER JOIN
O INNER JOIN é o método de junção de tabelas mais conhecido. Ele retorna as informações que são comuns entre duas ou mais tabelas.

Exemplo da instrução INNER JOIN:

```sql
SELECT A.NOME, B.HOBBY FROM TABELA_ESQUEDAR A 
INNER JOIN TABELA_DIREITA B 
ON A.INDENTIFICADOR = B.IDENTIFICADOR
```

[INNER JOIN](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20INNER%20JOIN.sql)

LEFT e RIGHT JOIN

Além da interseção, busca também resultados que não possuem interseção. Para LEFT JOIN são pegos os resultados da tabela a esquerda, além do resultado da interseção entre as duas tabelas, e para RIGHT JOIN são pegos os valores da tabela a direita, além do resultado da interseção entre as duas tabelas.

[LEFT E RIGHT JOIN](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20LEFT%20e%20RIGHT%20JOIN.sql)


