# PIG BANK

## Descrição:
  A presente apicação foi desenvolvida como desafio da DIO.
  Refere-se a um sistema de uma instituição bancária para gerenciar suas contas, clientes e transações.</center>

### Tecnologias

PIG BANK usa alguams das tecnlogias mais recentes do mercado:

* [**JAVA**] - Linguagem multiplataforma de alto desempenho;
* [**SRPING BOOT**] - Framework para desenvolvimento de aplicações web/coporativas;
* [**POSTGRESQL**] - Banco de dados relacional de código aberto;


### API

Path's funcionando com os verbos HTTP (**GET, POST, PUT E DELETE**):

Para analizar a documentação no SWAGGER basta subir a aplicação e acessar: http://localhost:8080/swagger-ui/index.htm

* /contas
* /contas/{id}
* /cliente
* /contas/{id}
* /transacao/sacar
* /transacao/depositar
* /transacao/sacar
* /transacao/transferir

Para rodar localmente, é necessário fazer configuração do application.properties, como for de preferência;

    Configurar um username, password e url para o banco a ser usado, como a seguir:
    
        application.properties:            
            spring.datasource.url=jdbc:postgresql://localhost:5432/pigbank
            spring.datasource.username={user_name}
            spring.datasource.password={passowrd_name}
            spring.datasource.driver-class-name=org.postgresql.Driver
            spring.jpa.hibernate.ddl-auto=update
            spring.jpa.show-sql=true
            spring.jpa.properties.hibernate.formart_sql=true             
---

Maiores detalhes podem ser encontrados na documentação:
[spring-boot-documentação](https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-features.html)        

**Free Software!**

PROJETO DESENVOLVIDO POR [Diego Patrício](https://github.com/diegojpatricio)