# Desafio back-end

O trabalho de um desenvolvedor back-end envolve, mas não é limitado a, desenvolver e manter nossa nuvem de microsserviços escritos em Java - que incluem tecnologias como APIs REST com Spring Cloud e MySQL como base de dados. Além disso, também é necessário pensamento crítico a fim de tomar as melhores decisões.

## Tecnologias
- Java 11
- Spring
- Maven
- MySQL
- Git

## Requisitos
Você precisa criar uma **API REST** para armazenar uma lista de produtos de diferentes fornecedores para ser usada em nossa aplicação.

A entidade ```supplier``` deve ter os seguintes campos:
```txt
* id
* name
* date of creation
* date of the last update
```

Você **não precisa** criar _endpoints_ para gerenciar os fornecedores. Apenas criar uma tabela e inserir pelo menos 3 registros para serem usados nos _endpoints_ dos produtos.

Os campos dos produtos são:
```txt
* id
* name
* quantity in stock
* unit price
* supplier_id (reference to suppliers table)
* date of creation
* date of the last update
```

E a API deve ter um CRUD completo dos produtos com os seguintes recursos:
```txt
* An endpoint to list all product;
* An endpoint to see just one product by 'id';
* An endpoint to insert a new product;
* An endpoint to update a product;
* An endpoint to delete a product;
- An endpoint to increase or decrease the quantity stock
```

Você deve providenciar o _script_ da base de dados, o código-fonte da API, a forma como a API deve ser usada (pode ser uma coleção do Postman ou uma sequência de comandos cURL); criar um arquivo README.md para explicar como instalar e usar a API. Por fim, você deve adicionar o projeto a um repositório no GitHub e nos enviar o link para acessar sua implementação.

**Boa sorte!**