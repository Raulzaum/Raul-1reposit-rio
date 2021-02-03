# **Repositório-Projeto MQTT- Raul Gomes**
Tal repositório fora criado para mostrar um pouco sobre meu projeto feito na Sprint 8, parte do curso de Redes, localizado na Rede SENAI de Informática.
## Objetivo
O objetivo do projeto se baseia em utilizarmos um Arduino UNO e um Sensor Magnético, para que assim, possamos monitorar remotamente a porta do Rack de Rede e também recebermos informações sobre a mesma, nos sendo apresentado o estado na qual se encontra, variando apenas entre _ABERTO_ e _FECHADO_. Para isso, foi utilizado o protocolo [MQTT](https://pt.wikipedia.org/wiki/MQTT) (_Message Queuing Telemetry Transport_), onde o mesmo envia a informação via Internet para um servidor MQTT localizado na [AWS](https://www.google.com/search?q=AWS&oq=AWS&aqs=chrome..69i57j35i39j0i395i433l3j0i395j69i60l2.1012j1j7&sourceid=chrome&ie=UTF-8) (_Amazon Web Service_), através de um aplicativo instalado no celular do cliente MQTT ([MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=pt_BR&gl=US)).
![68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67](https://user-images.githubusercontent.com/78221726/106684408-2df56c00-65a5-11eb-8a4a-f645efc30f3e.png)
Foram utilizadas as seguintes bibliotecas:

- [UIPEthernet](https://www.arduino.cc/reference/en/libraries/uipethernet/) (conexão do ENC28J60 com o Arduino)
- [PubSubClient](https://www.arduino.cc/reference/en/libraries/pubsubclient/) (cliente MQTT para o Arduino)
## Materiais
- [Arduino Uno](https://www.arduino.cc/reference/en/)
- [Módulo Ethernet (ENC28J60)](https://www.elecrow.com/wiki/index.php?title=ENC28J60_Ethernet_Module)
- [Sensor Magnético (MC-38)](https://blogmasterwalkershop.com.br/arduino/como-usar-com-arduino-sensor-magnetico-com-fio-para-alarme-mc-38/)
- [Jumpers](https://www.baudaeletronica.com.br/prototipagem/jumpers)
## Circuito
![Senai](https://user-images.githubusercontent.com/78221726/106684992-431eca80-65a6-11eb-9842-7f61d8a571f5.png)
Autor: Raul Gomes
