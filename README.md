# DSMeta
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/JairTorezone/dsmeta-spring-react/blob/main/LICENCE) 

# Sobre o projeto

https://dsmeta-torezone.netlify.app/

DSMeta é uma aplicação full stack construída durante a edição da **Semana Spring React** (#sds-dsmeta), evento organizado pela DevSuperior.

A aplicação consiste em um app de consulta de vendas, no qual poderá buscar vendas em um dado intervalo de datas, e notificar via SMS os dados dos melhores vendedores. Foi desenvolvido o back end com Java e Spring, e o front end com React. 

## Layout web
![Web 1](https://github.com/JairTorezone/dsmeta-spring-react/blob/main/frontend/src/assets/img/dsmetaa.png)


## Layout mobile
![Mobile 1](https://github.com/JairTorezone/dsmeta-spring-react/blob/main/frontend/src/assets/img/dsmeta-mobile.png) ![Mobile 2](https://github.com/JairTorezone/dsmeta-spring-react/blob/main/frontend/src/assets/img/dsmeta-mobile1.png)



# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- Spring Security
- JPA / Hibernate
- Maven
- Twilio
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Hooks: useState e useEffect
- Axios
- Datepicker

## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: H2 Database
- API testar: Postman

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone git@github.com:JairTorezone/dsmeta-spring-react.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone git@github.com:JairTorezone/dsmeta-spring-react.git

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start / yarn dev
```

# Autor

Jair Torezone E Ribeiro

https://www.linkedin.com/in/jair-torezone

