# ticket-payment-rabbitmq

Este projeto consiste em duas aplicações principais: uma para gerar ingressos e outra para processar pagamentos. Ambas as aplicações são desenvolvidas em Node.js e se comunicam através do RabbitMQ.

## Estrutura do Projeto
- **ticket**: Responsável por criar e gerenciar os ingressos.
- **payment**: Responsável por processar os pagamentos dos ingressos.

## Tecnologias
- Node.js
- RabbitMQ
- Docker

## Comandos
```bash
# Instale as dependências para cada aplicação:
cd ticket
npm install
cd ../payment
npm install

# Inicie o RabbitMQ:
sudo service rabbitmq-server start

# Execute as aplicações:
cd ticket
npm start
cd ../payment
npm start
```
