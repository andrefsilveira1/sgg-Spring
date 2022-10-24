# sgg-Spring
Trabalho da disciplina "Projeto Detalhado de Software" - UFRN 2022

# Atenção !

Para iniciar esse projeto, é necessário que o **maven** esteja instalado em seu ambiente de desenvolvimento. Além disso, note que o repositório utilizado para o projeto ser

## Passo a passo para instalação no Linux:

- `sudo apt-get update` -> atualizar o apt-get
- `sudo apt-get -y install maven` -> instalar o maven
- `mvn -version` -> Checar se o maven foi instalado corretamente.


## Na pasta do projeto:

Depois de ter clonado o repositório e o Maven instalado na sua máquina, rode o comando na pasta index:
- `mvn clean install`

## Para rodar o server: 

Com tudo pronto, é hora de rodar o projeto e ver se está tudo funcionando. rode o comando:
- `mvn spring-boot:run`

## Por fim, recomendo instalar o Postman para auxiliar nos testes da API. 
- `sudo apt update`
- `sudo apt-get install snapd` -> instale o snap (caso não tenha)
- `snap --version` -> Cheque a versão do snap
- `sudo snap install postman --edge`
- `postman`




