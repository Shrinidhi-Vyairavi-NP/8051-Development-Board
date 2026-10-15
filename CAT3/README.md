# TIMER-BASED LED PATTERN GENERATOR AND BUTTON INTERRUPT CONTROLLER 

Design and implement a register-level GPIO controller for a microcontroller development board. Configure four LEDs as digital outputs and a push-button as a digital input. Each valid button press must advance the system to the next operating mode: running LED, binary counter, alternating pattern, and all LEDs flashing. 

Implement switch debouncing and ensure that one physical button press produces exactly one transition. 

| MODE 1 : RUNNING LED | MODE 2 : BINARY COUNTER | MODE 3 : ALTERNATING PATTERN | MODE 4 : ALL LEDs FLASH | 
|---|---|---|---| 
| LED1 → LED2 → LED3 → LED4 → LED1 |0000 → 0001 → 0010 → 0100 → .... → 1111 → 0000 | 1010 → 0101 → 1010 → 0101 | 1111 → 0000 → 1111 → 0000 | 



