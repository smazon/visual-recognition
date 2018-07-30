

# Watson Visual Recognition com Node-RED

Utilizando Watson VR com modelos standard ou customizados através da interface Node-RED.

## SETUP INICIAL:

### 1. Crie instâncias dos seguintes serviços

#### Node-RED Starter Kit: 

https://console.bluemix.net/catalog/starters/node-red-starter

#### Watson Visual Recognition:

https://console.bluemix.net/catalog/services/watson-vision-combined

### 2. Abra o  Node-RED Flow Editor e importe o código disponível neste repositório (Link abaixo);

Raw Code: 
#### Node-RED Flow: https://raw.githubusercontent.com/smazon/visual-recognition/master/nodered.json

![alt text](https://i.imgur.com/oG8FYYF.png)

### 3. Setup dos nós do Visual Recognition com as API-KEYs do serviço;

![alt text](https://i.imgur.com/DoyHIjv.png)


### 4. Observações:

I. Insira imagens para análise com terminação '.jpeg' or '.png';

II. Escolha o custom classifier id para análise (todos os classifier-ids disponíveis do seu serviço de Watson VR serão listados) ou deixe como 'default;

III. Clique no botão de 'Submit' e veja a resposta do serviço! \o/
