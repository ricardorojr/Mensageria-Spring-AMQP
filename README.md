# Exemplo de Mensageria AMQP - RabbitMq

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/ricardorojr/source-springboot-java-8/blob/master/LICENCE) 


# Sobre o projeto

Mensageria: A aplicação consiste em modulos de pedidos sendo produtor enviando mensagem para consumidores que são: Cachback e Notificação, .


# Tecnologias utilizadas
## Back end
- Java 11 https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html
- Spring Boot
- JPA / Hibernate
- Maven
- Docker
- RabbitMq

## Implantação em produção
- Banco de dados: MySql
# Como executar o projeto
## Back end
Pré-requisitos: Java 11


```bash
# clonar repositório
git clonehttps://github.com/ricardorojr/Mensageria-Spring-AMQP.git
# entrar na pasta do projeto raiz
Abrir o terminal executar o comando: docker compose up
 1 -  porta: Mysql - 3306, após o comando ser executado entrar em algum gerenciador de banco de dados. 
 Ex: pgadmin, dbeaver; conectar no ServerHost = localhost, Port = 3306 
 
 
 2 - porta: RabbitMQ painel - 15672, abrir no Google Chrome por exemplo, http://localhost:15672/

# executar o projeto
  1 - Executar run no modulo de Orders-service
  2 - Executar run nos modulos CachaBack-service e Notificaion-service
```

# Autor
Ricardo Rodrigues de Oliveira Júnior
https://www.linkedin.com/in/ricardo-rodrigues-85983b176/
   
