# API rest + Java + Spring

## Tools
- Spring Tools Suit (STS)
- Postman

## About
A small system about users and your departments.

## Functionalities

- get users
- get user by id
- insert new user

## General configuration

### Maven resource plugin configuration
```
<plugin>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-resources-plugin</artifactId>
	<version>3.1.0</version>
</plugin>
```
### Database configuration
```
# Datas to stablish a conection with h2
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=

# Client web configuration for h2
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

# Configuration to show SQL in console line
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
