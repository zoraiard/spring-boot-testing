# spring-boot-testing - Demo project for Spring Boot
A simple Spring boot maven project to demonstrate testing Spring Data JPA repositories.


O Spring Boot oferece a anotação @DataJpaTest para testar os componentes  da camada de persistência configuram automaticamente os banco de dados em memória  percorrendo as classe @Entity  e os repositórios JPA Spring Data. A anotação @DataJpaTest não carrega outros beans Spring (@Components, @Controller, @Service e anotações beans) no ApplicationContext. 

Para testar os Repositórios JPA Spring Data ou qualquer outro componente JPA-relacional , Spring Boot fornece a anotação @DataJpaTest. Podemos adicioná-lo ao nossos testes de unidade ele configurará um Spring application context . 
