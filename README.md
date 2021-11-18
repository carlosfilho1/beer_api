<h2>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

No Projeto estou usando 
* Java 15
* Maven 3.8.3.

Banco JDBC
* Acessar o arquivo ```application.properties``` para pegar informações para acessar o H2, uma vez que ele funciona in-memory ou seja apos registrar o arquivo XML ficará salvo na memoria enquanto o Spring estiver em execução.

- Caminho abaixo para acessar os dados que foram registrado via XML. Ressalvo que ao preencher o arquivo xml, pode verificar as instancias que foram aplicados para o banco registrar e captura no arquivo ```/entity/Beer```
```
http://localhost:8080/api/v1/beers
```

