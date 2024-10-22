# Cp2_IA

O objetivo do nosso projeto nesse Cp era, utilizando led, chamar a atenção das pessoas sobre perigos próximos, sejam essas pessoas pedestres ou até mesmo motoristas. 
Utilizando um sensor de distância conectado a uma placa ESP32, ele detecta objetos de aproximando (como uma porta automática se fechando) e envia um sinal para um Broker, no casa o mosquitto, que por sua vez está conectado ao Node-RED.
O Node-RED irá armazenar e encaixar essa informação em um gráfico e enviar para um arduino.
O arduino está ligado a um led e dependendo da proximidade do objeto, a frequência com que o led pisca irá aumentar (caso esteja se aproximando). 
Há a possibilidade de utilização também de um buzzer, aumentando os métodos utilizados para de chamar a atenção.

Link do vídeo no youtube: https://youtu.be/9FcvbNARlzE
Link para o Wokwi: https://wokwi.com/projects/412474748400477185

Dentro do arquivo há o código utilizado no arduino ide, uma foto do circuito físico do arduino, o arquivo do fluxo no Node-RED e uma foto do mesmo. 
