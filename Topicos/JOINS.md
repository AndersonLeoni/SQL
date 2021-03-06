## INNER JOIN
O INNER JOIN é o método de junção de tabelas mais conhecido. Ele retorna as informações que são comuns entre duas ou mais tabelas.

Exemplo da instrução INNER JOIN:

```sql
SELECT A.NOME, B.HOBBY FROM TABELA_ESQUEDAR A 
INNER JOIN TABELA_DIREITA B 
ON A.INDENTIFICADOR = B.IDENTIFICADOR
```

[INNER JOIN](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20INNER%20JOIN.sql)

## LEFT e RIGHT JOIN

Além da interseção, busca também resultados que não possuem interseção. Para LEFT JOIN são pegos os resultados da tabela a esquerda, além do resultado da interseção entre as duas tabelas, e para RIGHT JOIN são pegos os valores da tabela a direita, além do resultado da interseção entre as duas tabelas.

Exemplo da instrução LEFT JOIN
```sql
SELECT <colunas>
FROM Table_A A
LEFT JOIN Table_B B
ON A.Key = B.Key
```

Exemplo da instrução RIGHT JOIN
```sql
SELECT <colunas>
FROM Table_A A
RIGHT JOIN Table_B B
ON A.Key = B.Key
```

[LEFT E RIGHT JOIN](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20LEFT%20e%20RIGHT%20JOIN.sql)

## FULL JOIN
Retorna todos os registros de todas as tabelas da consulta

Exemplo da intrução FULL JOIN
```sql
SELECT A.NOME, B.HOBBY FROM
TABELA_ESQUERDA A
FULL JOIN TABELA_DIREITA B
ON A.IDENTIFICADOR = B.IDENTIFICADOR
```

## CROSS JOIN 
Retorna o produto cartesiano das duas tabelas (cruza as informações)

Exemplo da intrução CROSS JOIN
```sql
SELECT A.NOME, B.HOBBY FROM
TABELA_ESQUERDA A, TABELA_DIREITA B
```
[FULL JOIN e CROOS JOIN](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20FULL%20e%20CROSS%20JOIN.sql)

## UNION

Retorna a união de duas ou mais tabelas

Exemplo da intrução UNION
```sql
SELECT DISTINTC BAIRRO FORM TABELA_DE_CLIENTES
UNION
SELECT DISTINCT BAIRRO FROM TABELA_DE_VENDEDORES
```

[UNION](https://github.com/AndersonLeoni/SQL/blob/main/JOINS/Consultas%20UNION.sql)