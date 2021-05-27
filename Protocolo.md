# Me dá uma ajudinha?

## Descrição do protocolo:

>
Um dos métodos utilizados foi o do protocolo Firmata que permitirá a comunicação de um computador e um microcontrolador via software (Victor Meriat, 2015) e o protocolo MQTT (Message Queue Telemetry Transport), desenvolvida pela IBM que se tornou um padrão de comunicação de mensagens da Internet das Coisas. Consiste em um protocolo simples e de fácil implementação em conversa entre máquinas (M2M – machine to machine) que fazem a assinatura e a leitura (publish /subscriber) das mensagens (Shirley Basílio, 2017).  Escolhemos também o Node-Red, por ser intuitivo e através dele faremos a integração do nosso projeto com o protocolo MQTT.                                                                                                         
> Na IDE do Arduino rodamos o protocolo Firmata:
> 
![WhatsApp Image 2021-05-26 at 22 56 19](https://user-images.githubusercontent.com/84140628/119753773-b5792a80-be75-11eb-80cc-b9a0b6fce0f8.jpeg)
> 
![WhatsApp Image 2021-05-26 at 22 56 31](https://user-images.githubusercontent.com/84140628/119753778-b742ee00-be75-11eb-8907-36eba6b3d959.jpeg)
>
![WhatsApp Image 2021-05-26 at 22 56 44](https://user-images.githubusercontent.com/84140628/119753783-b8741b00-be75-11eb-8536-a940545347ee.jpeg)

> 
Com o Node-Red aberto estruturamos nosso projeto da seguinte forma:
![WhatsApp Image 2021-05-26 at 22 10 22](https://user-images.githubusercontent.com/84140628/119754069-4819c980-be76-11eb-9ccf-66f5745a8044.jpeg)

> 
No bloco função "if" definimos:
![WhatsApp Image 2021-05-26 at 23 02 59](https://user-images.githubusercontent.com/84140628/119754275-9dee7180-be76-11eb-8a23-121bd116beca.jpeg)

> 
No bloco função "switch" definimos:

![WhatsApp Image 2021-05-26 at 23 03 14](https://user-images.githubusercontent.com/84140628/119754292-a5ae1600-be76-11eb-9c58-c633b4e165b6.jpeg)

