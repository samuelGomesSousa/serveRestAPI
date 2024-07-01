# Bootcamp 01 Qualiters Club - serveRestAPI
Teste de API Rest do manual ao CI/CD

## O que é
Este repositório foi criado para o bootCamp de teste de API rest

## Tecnologias utilizadas
Postman web, 
newman v6.1.3, 
newman-report-htmlextra, 
node v21.6.1,


## Documentações
Doc da API: [Consulte swagger](https://serverest.dev/#/)

## como instalar o ambiente
- Instale o node na sua máquina
- Realize a instalação do newman de forma global [baixe aqui a dependencia](https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/)
- Realize a instalação da dependencia dos relatórios de forma global (opcional) [veja mais](https://www.npmjs.com/package/newman-reporter-htmlextra)
  
## Como rodar os testes
### Pelo postman
- Importe a collection e o environment
- Execute os testes de forma manual ou automatizada (Runner)

### pelo newman
- Abra um console de preferência
- Execute a seguinte linha de comando no diretório que está os arquivos: newman run ServeRest.postman_collection.json -e serveRest_test.postman_environment.json -r htmlextra
- Para ver o relatório em html, abra o diretório que se encontra os arquivos e acesse a pasta do newman.
