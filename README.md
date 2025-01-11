# Project_UART

![image](https://github.com/user-attachments/assets/6886ca5f-f436-44a1-8982-7a9153c2eaeb)

#### UART stands for Universal Asynchronous Receiver-Transmitter, a hardware protocol that allows devices to exchange data serially.
#### How it works
UART uses two wires to transmit and receive data between devices. It sends data in frames, which are made up of a start bit, data bits, an optional parity bit, and stop bits. 
#### Communication modes
UART can operate in simplex, half-duplex, or full-duplex modes: 
Simplex: Data is sent in one direction only. 
Half-duplex: Each side can speak, but only one at a time. 
Full-duplex: Both sides can transmit simultaneously. 
#### Speed
UART uses an asynchronous protocol, meaning there is no shared clock signal between the sender and receiver. The speed at which data is transmitted is known as the baud rate, and is usually expressed in bits per second (bps). 
#### Parity bit
This optional bit is used to check for errors in data transmission. It can be set to "odd" or "even", and ensures that the number of bits set to logic "1" in a character is either even or odd. 
#### Application
UART is commonly used in microcontrollers, embedded systems, and computers. It's also used in computer peripherals, such as modems.

![image](https://github.com/user-attachments/assets/bdfed9b0-ad2a-4fb0-ad72-2f7a0d5c5bab)

#### Manually Generated Slower Clock
![man_gen_clk](https://github.com/user-attachments/assets/cd917707-1a58-4fd3-bc78-7a335433a665)



