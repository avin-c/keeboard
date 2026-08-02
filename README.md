# Keeboard
my custom 65% mechanical keyboard

## Journal
### August 2 
(1 hour)
Planned out my 65% keyboard using excalidraw. Decided to add a rotary encoder in the top left for volume, due to the lack of a function row. The Raspberry Pi Pico is located in the top right to allow for USB-C port on top right corner. 

![layout of 65% keyboard with rotary encoder in top left and pico in top right](journal-pics/65draft6.png)

(1 hour) Set up KiCad and installed [marbastlib](https://github.com/ebastler/marbastlib) library. Also created the below matrix for my keyboard to plan where my rows and columns will go, and where each switch will connect to. I ended up with a 16x5 matrix grid, which uses 21 pins and handles 80 keys of which my keyboard uses 70 of. 

![Keyboard matrix of my keyboard with 16 columns and 5 rows. Each of the 70 switches is highlighted with a red dot](image.png)

(1.5 hours) Designed schematic on KiCad, following my layout in the diagram above. Added the Pico, switches, diodes, stabilizers, and rotary encoder. Arranged each switch-diode set into a matrix following the layout of the matrix above. Then connected each row/column wire to the Pico using net labels. Also connected the Rotary Encoder to the Picousing net labels and GND symbols. Finally, annotated everything using the automatic annotation tool. Also checked that the connections were working with the highlight net label function and confirmed that everything was properly connected.

![Screenshot of my KiCad window with my schematic finished with my switches and diodes in proper positions within the matrix and the matrix rows/columns connected to the Raspberry Pico. Also have the stabilizers off to the side for the footprint and the rotary encorder connected as well to the Pico](image-2.png)

(0.5 hours) Assigned footprints to my components. Took a while because I had to find out what kind of footprint the rotary encoder uses, which I learned was a RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm footprint in KiCad. Also had to configure each stabilizer footprint to the correct size, but there were some that were a little smaller: 2.25u instead of my 2.5u so I will see how that works out later. 
![Screenshot of my footprint assignment popup](image-1.png)