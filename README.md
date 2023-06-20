# Materiais
Esse repositório PÚBLICO tem o objetivo de guardar datasheets importantes sobre os materiais que usamos.

[![Como montar seu robo VSSS IEEE](https://img.shields.io/badge/Como_montar_seu_robo_VSSS_IEEE-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/CSqQj6XjWUg)

# Lista de conexão
* Capacitor cerâmico de 50pF
* Capacitor cerâmico de 100nF
* 2 - Interruptores
* Conector XT60 Macho
* Cabo para autofalante (Soldar no XT60 e na placa)
* Capacitor eletrolítico de 330uF(**O disponível no lab é o de 220uF, portanto será ele**); ≥10v
* Capacitor poliéster 1uF
* Resistor de 10k
* Resistor de 30Ω
* Led vermelho alto brilho 5mm
* LM7805
* Esp32 doit devkit
* Módulo nrf24l0
* Mpu 6050
* Diodo Schottky com queda de tensão baixa em 5v e que aguente até 1 A (Pedir para a Samantha)

#Observações:
* Interruptores - Ambos os interruptores disponíveis são de 90°. Em deles será necessário entortar os terminais. Como na figura abaixo:
<div style="display: inline_block" align="center">
<img align="center" alt="Motores_com_fita" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Interruptor90.png?raw=true"/>
<img align="center" alt="Motores_com_fita" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Interruptor0.png?raw=true"/>
<br>
Os interruptores soldados na placa ficam assim:
<br>
<img align="center" alt="Motores_com_fita" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/InterruptorSoldados.png?raw=true"/>
</div>

  
* Motores - Soldar os fios e colocar fita isolante cobrindo a solda para que não haja contato entre as soldas dos motores.
Imagem a seguir de como deve ficar:
<div style="display: inline_block" align="center">
<img align="center" alt="Motores_com_fita" height="500" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Motores.png?raw=true"/>
</div>

* Componentes soldados diretamente na placa (capacitores, diodo e regulador LM7805):
<div style="display: inline_block" align="center">
<img align="center" alt="Componentes 1" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Componentes%20montados%20no%20PCB.jpg?raw=true"/>
<img align="center" alt="Componentes 2" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Componentes%202.jpg?raw=true"/>
<img align="center" alt="Componentes 3" height="400" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Componentes%203.jpg?raw=true"/>
</div>
<br>
* Sensor de Mouse: O circulo amarelo indicado na figura abaixo representa o terminal 1 do sensor.

<div style="display: inline_block" align="center">
<img align="center" alt="Esquematico_sensor_mouse" height="300" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Esquematico_sensor_mouse.png?raw=true"/>
[<img align="center" alt="DataSheet_sensor_mouse" height="300" src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Pinout_sensor_mouse.png?raw=true"/>](https://github.com/HumaMaquina/Materiais/blob/main/datasheets/Mouse_sensor_ADNS3050.pdf)
</div>

# Lista de conexões dos componentes ![Última atualização](https://img.shields.io/github/last-commit/HumaMaquina/Materiais?label=Última%20atualização&style=flat&color=blue&labelColor=grey&logo=github&logoColor=white&date_format=DD%2FMM%2FYY%20-%20HH%3A%MM%20%28UTC%29)
<img src="https://github.com/HumaMaquina/Materiais/blob/main/assets/Esquematico_placaV1.jpg?raw=true">
Sujeita a mudanças:

| QUANTIDADE | COMPONENTE             | CONEXÃO                      | PORTAS (n°)       | DESCRIÇÃO |
|------------|------------------------|------------------------------|-------------------|-----------|
| 1          | ESP32 DEVKIT V1 - DOIT | Ponte H TB6612FNG            | D13 - PWMA        |           |
|            |                        |                              | D25 - PWMB        |           |
|            |                        |                              | D12 - AI2         |           |
|            |                        |                              | D14 - AI1         |           |
|            |                        |                              | D27 - BI2         |           |
|            |                        |                              | D26 - BI1         |           |
|            |                        |                              | 3V3 - STBY        |           |
|            |                        |                              | 3V3 - VCC         |           |
|            |                        |                              | GND - GND         |           |
|            |                        | ADNS-3050                    | D19 - MISO        |           |
|            |                        |                              | D2 - NCS          |           |
|            |                        |                              | D23 - MOSI        |           |
|            |                        |                              | D18 - SCLK        |           |
|            |                        |                              | 3V3 - VDD         |           |
|            |                        |                              | GND - GND         |           |
|            |                        | MPU-6050 DIP                 | 3V3 - VCC         |           |
|            |                        |                              | GND - GND         |           |
|            |                        |                              | D22 - SCL         |           |
|            |                        |                              | D21 - SDA         |           |
|            |                        |                              | D33 - INT         |           |
|            |                        | NRF24L01                     | 3V3 - VCC         |           |
|            |                        |                              | D5 - CSN          |           |
|            |                        |                              | D23 - MOSI        |           |
|            |                        |                              | D4 - CE           |           |
|            |                        |                              | D18 - SCK         |           |
|            |                        |                              | D19 - MISO        |           |
| 1          | Ponte H TB6612FNG      | ESP32 DEVKIT V1 - DOIT       | PWMA - D13        |           |
|            |                        |                              | PWMB - D25        |           |
|            |                        |                              | AI2 - D12         |           |
|            |                        |                              | AI1 - D14         |           |
|            |                        |                              | BI2 - D27         |           |
|            |                        |                              | BI1 - D26         |           |
|            |                        |                              | STBY - 3V3        |           |
|            |                        |                              | VCC - 3V3         |           |
|            |                        |                              | GND - GND         |           |
|            |                        | Resistor 1K Ohms             | STBY - Resistor   |           |
|            |                        | MicroMotor                   | AO1 - Motor1 +    |           |
|            |                        |                              | AO2 - Motor1 -    |           |
|            |                        |                              | BO2 - Motor 2 +   |           |
|            |                        |                              | BO1 - Motor 2 -   |           |
|            |                        | Switch Motor                 | VM - 2            |           |
| 1          | MPU-6050 DIP           | ESP32 DEVKIT V1 - DOIT       | VCC - 3V3         |           |
|            |                        |                              | GND - GND         |           |
|            |                        |                              | SCL - D22         |           |
|            |                        |                              | SDA - D21         |           |
|            |                        |                              | INT - D33         |           |
| 1          | NRF24L01               | ESP32 DEVKIT V1 - DOIT       | VCC - 3V3         |           |
|            |                        |                              | CSN - D5          |           |
|            |                        |                              | MOSI - D23        |           |
|            |                        |                              | CE - D4           |           |
|            |                        |                              | SCK - D18         |           |
|            |                        |                              | MISO - D19        |           |
|            |                        | Capacitor Cerâmico 100nF     | VCC - Capacitor+  |           |
|            |                        | Capacitor Cerâmico 50pF      | VCC - Capacitor+  |           |
| 1          | ADNS-3050              | ESP32 DEVKIT V1 - DOIT       | MISO - D19        |           |
|            |                        |                              | NCS - D2          |           |
|            |                        |                              | MOSI - D23        |           |
|            |                        |                              | SCLK - D18 -      |           |
|            |                        |                              | VDD - 3V3         |           |
|            |                        |                              | GND - GND         |           |
|            |                        | Resistor 30 Ohms             | VDD - Resistor    |           |
| 1          | Regulador XL6009       | Switch Sistema               | IN+ - 3           |           |
|            |                        | Bateria 7.4V                 | IN+ - Terminal +  |           |
|            |                        |                              | IN- - Terminal -  |           |
|            |                        |                              | OUT- - Terminal - |           |
|            |                        | Switch Motor                 | OUT+ - 3          |           |
| 1          | Regulador LM7805       | Switch Sistema               | IN - 2            |           |
|            |                        | Capacitor Poliester 5uF      | IN - Capacitor+   |           |
|            |                        |                              | OUT - Capacitor+  |           |
|            |                        | Capacitor Cerâmico 100nF     | IN - Cpacitor+    |           |
|            |                        |                              | OUT - Capacitor+  |           |
|            |                        | Capacitor Eletrolítico 330uF | OUT - Capacitor+  |           |
|            |                        | Diodo Schottky 1A            | OUT - Anodo       |           |
| 1          | LED                    | ADNS-3050                    | Catodo - LED      |           |
|            |                        | Resistor 30 Ohms             | Anodo - Resistor  |           |
| 1          | Diodo Schottky 1A      | LM7805                       | Anodo - OUT       |           |
|            |                        | ESP32 DEVKIT V1 - DOIT       | Catodo - 5V       |           |
| 1          | Switch Sistema         | XL6009                       | 3 - IN+           |           |
|            |                        | LM7805                       | 2 - IN            |           |
| 1          | Switch Motor           | TB6612FNG                    | 2 - VM            |           |
|            |                        | XL6009                       | 3 - OUT+          |           |
| 2          | MicroMotor             | TB6612FNG                    | Motor1+ - AO1     |           |
|            |                        |                              | Motor1- - AO2     |           |
|            |                        |                              | Motor 2+ - BO2    |           |
|            |                        |                              | Motor 2- - BO1    |           |
