## O que é isso?
Este código-fonte é um exemplo de Spring Boot SSL (HTTPS).

Testado com
* Maven 3
* Java 8
* Spring Boot 2.2.4.RELEASE
* Spring Boot default embedded Tomcat 9
* Self-signed certificate (PKCS12)


## Como executar isso?
```bash

$ cd spring-boot-ssl

$ mvn clean package

$ java -jar target/spring-boot-web.jar

  access https://localhost:8443
```