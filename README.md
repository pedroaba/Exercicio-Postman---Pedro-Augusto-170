# Exercício de Qualidade de Software

## Aluno 

Nome: Pedro Augusto Barbosa Aparecido
Matrícula: 170

## Contexto

Nessa atividade para a matéria de laboratório de qualidade de software, foi escolhido 
uma api do seriado Rick and Morty para realizar os testes.

## Como rodar?

Para poder executar os testes é preciso ter instalado a cli do postman e um plugin
para poder ter uma melhor visualização do relatório de testes

```shell
> $ npm i -g newman
```

```shell
> $ npm i -g newman-reporter-htmlextra
```

Depois disso feito precisa apenas rodar o comando abaixo:

```shell
newman run ".\Exercicio Teste de Api.postman_collection.json" -r htmlextra
```
