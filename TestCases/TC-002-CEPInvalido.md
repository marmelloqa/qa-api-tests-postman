# TC-002 - CEP inválido

## Objetivo
Validar consulta de CEP inexistente.

## Endpoint

GET https://viacep.com.br/ws/99999999/json/

## Resultado Esperado

- Status 200
- Campo "erro": true
