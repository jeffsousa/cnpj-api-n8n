# Consulta CNPJ API - n8n

Projeto desenvolvido utilizando n8n para consulta de informações empresariais através da BrasilAPI.

## Objetivo

Receber um CNPJ através de um endpoint HTTP e retornar informações cadastrais simplificadas da empresa.

## Tecnologias Utilizadas

* n8n
* Docker
* Webhook
* HTTP Request
* BrasilAPI
* GitHub

## Endpoint

Método:

GET

Exemplo:

/cnpj/12975887000112

## Exemplo de Retorno

{
"cnpj": "12975887000112",
"razao_social": "COOPERCARNE-COOPERATIVA DOS COMERCIANTES DE CARNE DO ESTADO DE GOIAS",
"nome_fantasia": "COOPERCARNE",
"municipio": "RIO VERDE",
"uf": "GO",
"cep": "75901970",
"situacao": "ATIVA",
"porte": "DEMAIS"
}

## Fluxo

Webhook
↓
Consulta BrasilAPI
↓
Tratamento dos Dados
↓
Resposta JSON

## Funcionalidades

* Consulta de CNPJ em tempo real
* Consumo de API REST
* Padronização dos dados retornados
* Resposta simplificada em JSON

## Autor

Jefferson Sousa
