# Semana 1 - Fundamentos de API e Introdução ao Postman

## 📌 Objetivos da Semana
- Compreender o que é uma API e como funciona
- Entender os principais métodos HTTP (GET, POST, PUT, DELETE, PATCH)
- Aprender sobre headers, body e status codes
- Instalar e configurar o Postman
- Criar requisições básicas para treinar os conceitos

## 📚 Conceitos Estudados
- API: Interface de comunicação entre sistemas
- REST: Padrão baseado em recursos e métodos HTTP
- HTTP:
  - Métodos: GET (buscar), POST (criar), PUT (atualizar), DELETE (remover), PATCH (alterar parcialmente)
  - Status codes: 200 (OK), 201 (Created), 400 (Bad Request), 401 (Unauthorized), 404 (Not Found), 500 (Server Error)
  - Headers: Informações adicionais como Content-Type
  - Body: Corpo da requisição, normalmente em JSON

## 🛠️ Ferramentas Utilizadas
- [Postman](https://www.postman.com/) (app desktop)
- [JSON Placeholder](https://jsonplaceholder.typicode.com/)
- [ReqRes](https://reqres.in/)

## 🧪 Práticas Realizadas
- Criada conta no Postman
- Realizadas requisições GET e POST no JSONPlaceholder e ReqRes
- Testado uso de headers e envio de body JSON

### Exemplos:
- GET: https://jsonplaceholder.typicode.com/posts/1
- POST: https://reqres.in/api/users

```json
{
  "name": "Sandro",
  "job": "QA Tester"
}
