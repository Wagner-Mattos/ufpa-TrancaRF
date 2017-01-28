# ufpa-TrancaRF
Projeto final de laboratório referente a matéria de circuitos elétricos.

A proposta do projeto se encontra no arquivo : TrabalhoFinalLab_4P_2016 v3.pdf

A solução aqui proposta é um par microcontrolado de Módulo de Acesso e Tranca.

No Módulo de Acesso .
Módulo microcontrolado que verifica uma senha inserida e caso correta abre a tranca.

Componentes:

* Placa de prototipagem Arduino (Uno/Nano)
* Lcd 1602
* Teclado Matricial 4 x 4 16 Teclas
* Módulo Serial I2C para Display LCD
* Módulo RF Transmissor 433Mhz AM
* Buzzer
* Leds

Esquemático:

Referências:


Na tranca.
Tranca microcontrolada que responde aos comandos do Módulo de Acesso (Abre/Fecha).

Componentes:

* Microcontrolador Pic 16f628a
* CI L293D Ponte H 
* Módulo RF Receptor 433Mhz AM
* Buzzer
* Leds
* Botões
* Motor Dc

Esquemático:

Referências:
