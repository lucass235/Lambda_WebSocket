# Lambda_WebSocket

Construção de webSocket utilizando api gateway e lambda

## Descrição do projeto

Este projeto tem como objetivo criar um webSocket utilizando api gateway e lambda para comunicação entre cliente e servidor onde o cliente enviará uma mensagem e o servidor responderá com uma mensagem de volta.

## Tecnologias utilizadas

- [python](https://www.python.org/)

- [aws](https://aws.amazon.com/pt/)

- [api gateway](https://aws.amazon.com/pt/api-gateway/)

- [lambda](https://aws.amazon.com/pt/lambda/)

- [websocket](https://developer.mozilla.org/pt-BR/docs/Web/API/WebSockets_API)

- [postman](https://www.postman.com/)

## Teste no Postman

link da api gateway socket: _wss://7ga43q8ah7.execute-api.us-east-1.amazonaws.com/demo_

- Criar uma conexão websocket

- Adicionar o endereço da api gateway socket

- Faz a conexão com o servidor

- Enviar uma mensagem para o servidor

```json
{ "action": "sendMessage", "message": "Ola websocket" }
```

- A mensagem é enviada para os clientes conectados no servidor

## Print dos testes

- Conexão ao servidor

![img_1](./img/conex%C3%A3o%20ao%20servidor.png)

- Enviando mensagem para o servidor do cliente 1

![img_2](./img/mensagem%20enviada%20ao%20sevirdor.png)

- Mensagem recebida pelo cliente 2

![img_3](./img/mensagem%20recebido%20usuario%202.png)

- Mensagem recebida pelo cliente 3

![img_4](./img/mensagem%20recebido%20usuario%203.png)
