## PCB and Schematic


### Schematic
![Schematic](..\Photos\Schematic.png)

The schematic follows a 15x5 matrix grid design and each row and column is connected to the microcontroller. This way, it is possible to determine which key is clicked without using too many pins. The EC11 Rotary Encoder is also connected to the microcontroller for both rotation and click. 

### PCB 

![PCB](..\Photos\PCB.png)

The PCB connects everything together from the schematic but physically in the keyboard layout format. I used the grid tool to make sure everything component fit properly, and added chamfers on the corners to fit in screws for the case. I used a mixture of front and back route traces in order to accomodate all the connections while keeping the wires organized and without enlarging the PCB border too much. 
