# UART Controller in VHDL

A simple UART Controller made using VHDL.
It includes a Baud Generator, UART Transmitter, UART Receiver and a top-level Controller.
The design uses a 50 MHz clock, 9600 baud rate and 8N1 format.
Data is transmitted LSB first.
The testbench checks the design using a loopback connection (TX connected to RX).
I tested it in Vivado simulation by sending `A5` and checking the received data.
The simulation passed and the received data matched the transmitted data.
