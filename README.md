## Sensor_DHT
Passo a Passo do sensor DHT22.



O DHT é um tipo de sensor usado principalmente em projetos de eletrônica e automação para medir temperatura e umidade do ar.

Existem dois modelos mais comuns:

DHT11 → mais simples, barato, mas com menor precisão.

DHT22 (ou AM2302) → mais caro, porém mais preciso e com maior faixa de medição.

🔹 # Como funciona?

Ele possui um termistor para medir a temperatura.

Usa um sensor capacitivo para medir a umidade.

Envia os valores em forma de sinal digital para o microcontrolador (como Arduino, ESP32, ESP8266 etc.).

🔹 # Para que serve?

Monitoramento de ambientes (casas, estufas, armazéns).

Sistemas de automação residencial.

Estações meteorológicas caseiras.

Controle de ventiladores, exaustores e climatizadores.

Projetos de IoT (Internet das Coisas).

---
# Passo a Passo 

1° Passo: Colocar o ESP32 na Breadboard.

![IMG_8142](https://github.com/user-attachments/assets/06204a1c-8d86-4c67-9d75-b48fd1081c74)

2° Passo: Colocar o DHT na nossa Breadboard.

![IMG_8143](https://github.com/user-attachments/assets/1d3f1d9a-292e-4f30-b68c-b4c12f429c74)

3° Passo: Colocar um jumper vermelho (positivo) 5V no ESP32 e o outro lado do jumper, na entrada VCC do DHT22

![IMG_8144](https://github.com/user-attachments/assets/aac7c64a-4a84-46c1-a25f-ce695a23cc35)

4° Passo: Colocar um jumper verde (ou de sua preverência) na porta 14 do ESP32 e o outro lado do jumper, na entrada SDA do DHT22

![IMG_8145](https://github.com/user-attachments/assets/a23fd112-c0c3-481f-9545-e97f7823c9ef)

5° Passo: Colocar um jumper preto (negativo) na porta GND do ESP32 e o outro lado do jumper, na entrada GND do DHT22

![IMG_8146](https://github.com/user-attachments/assets/b9cae7ea-00c7-4d21-9c42-88c16ea82690)

6° Passo: Conecte ao computador!

![IMG_8147](https://github.com/user-attachments/assets/f31c78da-ae13-43b0-a15d-f69502b4c0a2)

7° Passo: Adicione o código no computador. Logo, inicie o código, pressione/segure o botão 'BOOT' no ESP32 até aparecer 'Connecting' no computador.

![IMG_8148](https://github.com/user-attachments/assets/3a95a6b8-022f-4f22-8889-b0eff89cf36b)

8° Passo: Admira o resultado ;)

![IMG_8149](https://github.com/user-attachments/assets/745698e9-38c2-4353-b789-ebd87fd142b1)
