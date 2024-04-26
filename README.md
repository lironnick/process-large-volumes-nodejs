# Parallelizing Node.js varios processos

Uma forma de processar dados de um banco para outro de uma forma rapida 1 milhão de dados em 3 a 5 minutos em um mac imagina em um servidor de produção

## Running

Você precisará instalar o Docker e o Docker compose para poder ativar as instâncias dos bancos de dados, depois disso execute:

- docker-compose up -d
- npm ci
- npm run seed
- npm start

## Errors?

Caso você tenha recebido um erro de muitos processos abertos, tente diminuir o const CLUSTER_SIZE = 99
