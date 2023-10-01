# Controlador de Forno de Micro-ondas em Verilog (HDL)
Atividade desenvolvida para a disciplina de Sistemas Digitais - CIn-UFPE (2020.1)

Autores:
 - [Gabriela Maria Melo de Souza](https://github.com/GabrielaSouza2)
 - [João Marcos Alcantara Vanderley](https://github.com/jmarcossss)
 - [Juan Felipe Serafim dos Santos](https://github.com/JuanFelipeSerafim)
 - [Wellinne Welliankely Nascimento de Aquino](https://github.com/Wellinne)

Descrição do problema:
 - [Capítulo 10, seçao 5 do livro Sistemas Digitais - princípios e aplicações. Ronald J.Tocci](https://github.com/JuanFelipeSerafim/microwaveOven-HDL/blob/main/Capitulo_10.pdf)


Instalar o necessário:
 + Para Linux (Ubuntu):
 ```
 sudo apt install gtkwave
 ```

Rodando o projeto:
 ```
 iverilog -o microwaveOven microwaveOven.v bcd_7segmentos.v mag_on.v timerAndControlInput.v clkdiv100.v priorityEncoder.v delaydebouncing.v mux.v timerminseg.v contadormod10.v contadormod6.v microwaveOven_tb.v
 ```
Logo após:
 ```
 ./microwaveOven
 gtkwave microwaveOven_tb.vcd
 ```
