# 4 Digit 7 Segment Display
### This project features a custom [ATmega328P microcontroller](https://www.microchip.com/en-us/product/atmega328p) board programmed in C. It drives a 4-digit 7-segment display to implement a simple counter application.
####
<p align="center">
  <img width="600" height="337" src="add photo">
</p>
</br>
Features:

*   Incremental Counter: Displays an incrementing value (0–9999) on the 4-digit 7-segment display.
*   Reset Control: Button resets the microcontroller and the counter to 0.
</br>
Hardware Design:

*   [KiCad](https://www.kicad.org/download/windows/) Schematic: Includes the schematic for easy replication.
*   Can be built on a breadboard, perfboard, or custom PCB.
</br>
<p align="center">
  <img width="666" height="645" src="photo">
</p>
</br>

Programming the Board:
*   For detailed instructions on how to program the ATmega328P microcontroller for this project (including fuse configuration and flashing the hex file), please refer to the programming guide in my other [repository](https://github.com/contispaulcristian/Custom_Board_LED_Patterns).
</br>
Software Details:

*   Multiplexing: The 4-digit 7-segment display is controlled using multiplexing for efficient pin usage.
*   Timer Interrupt: The counter increments every second using a timer interrupt.
</br>
This project demonstrates the use of multiplexed displays, timer interrupts, and basic button controls in embedded systems.






