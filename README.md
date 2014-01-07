# Remote control using GSM Modem and PIC18F2620. 

Firmware is able to read the first ten user in SIM and use as enabled user to sen command.
Relay can be activated by call or SMS , reply SMS with status can be request and Call on external interrupt can be confederate.
Modem connected to PIc by UART, PIC config as follow:
 * MCLR    -> Disable.
 * CLK     -> Internal 8MHz
 * OUT     -> PORTA A
 * FREE    -> PORT C.3
 * RELAY1  -> PORT C.4
 * RELAY2  -> PORT C.5
 * UART    -> PORT C.6 : TX
 *            PORT C.7 : RX
 * LED     -> PORT A.0
 * LED     -> PORT A.1
 * LED     -> PORT A.2
 * LED     -> PORT A.3
 * LED     -> PORT A.4
 * LED     -> PORT A.5
 * LED     -> PORT A.6
 * LED     -> PORT A.7
 * IN1     -> PORT B.0  -> Input 
 * IN2     -> PORT B.1  -> Input 
 * IN3     -> PORT B.2  -> read setup switch
 * INSETUP1-> PORT B.3  -> On -Off Modem GSM
 * INSETUP2-> PORT B.4

 
Scheda con PIC18F2620 connessa a modem GSM MC35i per comandare due relay con SMS o squillo e essere chiamati in caso di evento esterno, es. apertura porta o qualsivoglia allarme. 


Francesco Uggetti ( ugge75 )

*This library is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.*

*This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Lesser General Public License for more details.*