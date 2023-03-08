# Exemplo de Mensageria AMQP - RabbitMQ

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/ricardorojr/source-springboot-java-8/blob/master/LICENCE) 


# Sobre o projeto

Mensageria: A aplicação consiste em modulos de pedidos sendo produtor enviando mensagem para consumidores que são: Cachback e Notificação.


# Tecnologias utilizadas
- Java 11 https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html
- Spring Boot
- JPA / Hibernate
- Maven
- Docker
- RabbitMq


# Como executar o projeto
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/ricardorojr/Mensageria-Spring-AMQP.git

#Primeiro passo, entrar na pasta do projeto raiz = Mensageria com Spring AMQP

Abrir o terminal executar o comando: docker compose up
1º - porta: Mysql - 3306, após o comando ser executado entrar em algum gerenciador de banco de dados. 
Ex: phpmyadmin ou dbeaver; conectar no ServerHost = localhost, Port = 3306 
 
 
2º - porta: RabbitMQ painel - 15672, abrir no Google Chrome por exemplo, http://localhost:15672/

# executar o projeto
1 - Executar run no modulo de Orders-service
2 - Executar run nos modulos CachaBack-service e Notificaion-service
```

# Autor
Ricardo Rodrigues de Oliveira Júnior
https://www.linkedin.com/in/ricardo-rodrigues-85983b176/
   
