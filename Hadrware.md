# Descrição do Hardware utilizado:

## Me dá uma ajudinha?

> 
Nosso projeto relacionou a luz de ré do veículo como uma forma de se conectar com o nosso sistema, dito isso, a intensidade da luz será utilizada como uma informação de entrada, e por consequência, após realizar essa leitura, através de um micro servo e um led realizaremos uma mensagem de saída.

>
Para a confecção do projeto selecionamos uma placa Arduino para transmitir as mensagens entre o LED, sensor e atuador. Essa transmissão ocorre através de Jumpers que conectam os componentes e nos possibilitam prolongar a distância entre o led e a bandeira. A bandeira consiste em uma folha de papel e sua base foi estruturada em um palito de sorvete fixada na hélice de um micro servo que tem como função rotacionar esse objeto para sinalizar ao condutor que o limite está próximo. Esse limite foi calculado pelo sensor de luminosidade que estará na protoboard de 400 pontos, além disso, selecionamos resistores para evitar a sobrecarga nos componentes, e para finalizar utilizamos uma fonte ajustável para a protoboard com a finalidade de alimentar nosso sistema.

>**Quantidade	Componente**
1	Arduino Uno R3 mais cabo Usb para Arduino
1	Protoboard 400 pontos
1	Micro Servo 9g SG90
1	Fonte ajustável para protoboard
1	Sensor de luminosidade LDR 5mm
1	Resistor – resistência de 10R Ω
1	Resistor 10k
1	Led Difuso 5mm da cor verde
9	Jumpers Macho-Fêmea 10cm, cada jumper.
2	Jumpers Macho-Macho 10cm, cada jumper.
1	Palito de sorvete
1	Bandeira de papel


>
Além do mais, um dos métodos utilizados foi o do protocolo MQTT (Message Queue Telemetry Transport), desenvolvida pela IBM que se tornou um padrão de comunicação de mensagens da Internet das Coisas. Consiste em um protocolo simples e de fácil implementação de conversa entre máquinas (M2M – machine to machine) que fazem a assinatura e a leitura (publish /subscriber) das mensagens (Shirley Basílio, 2017).

