# Materiais
Esse repositório PÚBLICO tem o objetivo de guardar datasheets importantes sobre os materiais que usamos.


# Lista de conexões dos componentes
Sujeita a mudanças:
|Quantidade|Componente|Conexão|Portas(n°)|Descrição|
|:----|:----|:----|:----|:----|
|1|ESP32 DEVKIT V1 - DOIT|Motor|IO 14/15/16/17| |
| | |Ponte H TB6612FNG|2 - VCC(20)| |
| | | |IO22 - PWMA(23)| |
| | | |IO23 - AIN1(21)| |
| | | |IO25 - AIN2(22)| |
| | | |IO26 - PWMB(15)| |
| | | |IO27 - BIN1(17)| |
| | | |IO32 - BIN2(16)| |
|1|Micro motor 6V 200 RPM Low Power|ESP32|IO 14/15/16/17| |
|2|Par de Encoders Magnéticos com entrada lateral|TB6612FNG|A01, A02, PGND1| |
| | | |B02, B01, PGND2| |
|1|Ponte H TB6612FNG|ESP32|VCC(20) - 2| |
| | | |PWMA(23) - IO22| |
| | | |AIN1(21) - IO23| |
| | | |AIN2(22) - IO25| |
| | | |PWMB(15) - IO26| |
| | | |BIN1(17) - IO27| |
| | | |BIN2(16) - IO32| |
| | |TB6612FNG|VM2 (13) / STBY(19) - VCC (20)| |
| | |Regulador 7805|VM2(13) / VM3(14) - VO(3)| |
|1|Regulador Boost XL6009|Regulador 7805|SW(3) - VI(1)| |
| | |Bateria|VIN(4) - Terminal Positivo| |
|1|Regulador 7805|XL6009|VI(1) - SW(3)| |
| | |TB6612FNG|VO(3) - VM2(13)| |
