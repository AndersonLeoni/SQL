# SELECT & FILTROS

# SELECT 
  O principal comando de consulta dentro SQL, ele tem por finalizada extrair os dados das tabelas.
  Ele pode extrair as informações de uma ou mais tabelas simultaneamente.
  
  Este comando é o inicio para consultas mais avançadas dentro do banco de dados, pois ele perimite a utilização de junções, filtros,
  ornenações e outros comandos como calculos matemáticos.
  
  EXEMPLO do comando básico:
  
  ```
  SELECT * FROM nome_da_tabela
  ```
  
  **Desmembrando o comando**
  
  * SELECT inicio do comando.
  * (*) (significa trazer todo o conteúdo)
  * FROM a tabela que está extraindo os dados (ou tabelas)
  
  
 # WHERE
 O comando WHERE é utilizado para filtrar dados no SQL. Essa clausula sempre é seguida por uma expressão lógica.
 
 EXEMPLO da estrutura SELECT + WHERE
 
 ```
  SELECT * FROM nome_da_tabela WHERE id = dado;
  ```
 
 
