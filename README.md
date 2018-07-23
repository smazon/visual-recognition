

# Watson Visual Recognition com Node-RED

Utilizando Watson VR com modelos standard ou customizados através da interface Node-RED.

## SETUP INICIAL:

### 1. Crie instâncias dos seguintes serviços

#### Node-RED Starter Kit: 

https://console.bluemix.net/catalog/starters/node-red-starter

#### Watson Visual Recognition:

https://console.bluemix.net/catalog/services/watson-vision-combined

### 2. Abra o  Node-RED Flow Editor e importe o código disponível neste repositório (Link abaixo);

Raw Code: https://raw.githubusercontent.com/munhozpf/Watson-VR_on_Node-RED/master/Watson-VR_Node-RED_Flow.json

#### Node-RED Flow:

![alt text](https://i.imgur.com/oG8FYYF.png)

### 3. Setup dos nós do Visual Recognition com as API-KEYs do serviço;

![alt text](https://i.imgur.com/DoyHIjv.png)


### 4. Observações:

I. Insert some image URL that ends with '.jpeg' or '.png';

II. Choose a custom classifier id (all avaiable custom classifier-ids from your Watson VR service will be showed below the fields) or leave 'default' as classifier id, otherwise the WebApp won't work;

III. Hit Submit button and enjoy the results!
