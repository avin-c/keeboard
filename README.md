# Keeboard
my custom 65% mechanical keyboard

## Journal
### August 2 
(1 hour)
Planned out my 65% keyboard using excalidraw. Decided to add a rotary encoder in the top left for volume, due to the lack of a function row. The Raspberry Pi Pico is located in the top right to allow for USB-C port on top right corner. 

![layout of 65% keyboard with rotary encoder in top left and pico in top right](journal-pics/65draft6.png)

(1 hour) Set up KiCad and installed [marbastlib](https://github.com/ebastler/marbastlib) library. Also created the below matrix for my keyboard to plan where my rows and columns will go, and where each switch will connect to. I ended up with a 16x5 matrix grid, which uses 21 pins and handles 80 keys of which my keyboard uses 70 of. 

![Keyboard matrix of my keyboard with 16 columns and 5 rows. Each of the 70 switches is highlighted with a red dot](image.png)