# Provi - Desafio de Engenharia de Dados

## Propósito

O objetivo desse desafio é composto por três partes:

1. Julgar a sua experiência técnica;
1. Entender como você desenha soluções;

## O que avaliaremos:

Nós avaliaremos

- A qualidade do código: Padrões, clareza, comentários, estilo etc.
- A solução desenhada na totalidade;

## Instruções

- Por favor, crie uma base de dados docker local (PostgreSQL) para armazenar os resultados;
  O código utilizado para criá-la também deve ser compartilhado;
- Compartilhe os códigos em um repositório aberto no Github; *Rever*
- Não há necessidade alguma de interface visual para o desafio proposto.

## O Desafio

Extraír, transformar e armazenar informações da [API pública de pokemons (https://pokeapi.co/)](https://pokeapi.co/).

### Detalhes

Precisamos informações de *pokemons*, *suas habilidades* e *tipos*:

- **_Pokemons_**: Queremos informações como nome, altura e outras propriedades
  que julgar interessantes;
- **_Habilidades_**: Precisamos informações como nome, efeito e quaisquer
  outras informações que julgar legal;
- **_Tipos_**: Queremos informações da interação de danos com os demais tipos de pokemons.

As informações devem ser armazenadas em uma base postgresql, de maneira relacional,
no formato que julgar melhor. Queremos realizar análises SQL com dados gerados,
para isso, precisamos garantir que conseguiremos relacionar as 3 entidades de
forma clara e fácil.  


Observações: 

- A API pública de pokemons possuí uma biblioteca python. Para demonstrar
  seus conhecimentos, pedimos que não a utilize - e sim use as requisições HTTP.
- Se o volume de dados for grande, não há necessidade de fazer uma carga completa,
  apenas garanta que seja possível demonstrar a arquitetura e funcionalidade
  básica da sua solução.

# A entrega

A entrega consiste em todos os códigos que você utilizou para chegar ao resultado
detalhado acima.  
**Todos** os passos devem ser reproduzíveis - desde a extração das informações,
criação da base de dado local e armazenamento das informações nela.

Também queremos um desenho com o diagrama de relações das entidades que você
construir. É possível construir um diagrama através do site https://dbdiagram.io,
mas você pode usar a ferramenta que preferir.

# Links Úteis

- Docker
    + [Postgres with Docker and Docker compose a step-by-step guide for beginners](https://geshan.com.np/blog/2021/12/docker-postgres/#postgres-with-docker)
    + [Connecting to Postgresql in a docker container from outside](https://stackoverflow.com/questions/37694987/connecting-to-postgresql-in-a-docker-container-from-outside)

