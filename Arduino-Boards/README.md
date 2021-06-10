<b>Arduino boards</b>

The Nano-BRK is the first public release board I have for the Arduino's. This board is very small and has several power options for the header-pins. I wanted a board that broke out all the pins in servo header style that could externally power things like servo motors or other higher current/voltage items.

The board can be powered with a 5v regulator on the PCB itself or without.  To use without, you will need to solder the jumper pads below the regulator between the two filter-caps.  For the headers, you can choose to power with the onboard regulator by soldering the jumper next to the Vin pin.  If you want to use external power for the headers, use the jumper pins near C1 and jumper top left to right. If power will be from an external regulator, that will also power the Nano, jumper from top to bottom on the right side of the header.<br><br>

New: The Pro Mini breakout board (3.3 or 5v).<br> 
Headers are included for all of the IO pins, including A4-A7. It has room for pullup resistors for SDA (A4) and SCL (A5). The regulator space is for the 1117 LDO type, 3.3v/1a or 5v/1a based on your "V" pin header power level choice. The regulator is optional and the VIN goes to the RAW pin of the Mini and lets the onboard regulator do the powering. You will have to solder the jumper pad to use a regulator.<br>
If a regulator is not used, then VIN EXT can be used for external "V" pin header powering. This will allow for more power/voltage for servos or other devices.<br> This board *should* work for the three most common pin configurations.
<br><br> 

<b>Getting PCBs manufactured:</b>

Just download the zip file from this site for the PCB you want and upload that file to the PCB makers site of your choice and enter the size info if needed included below for the board you want to have manufactured.<br><br>

Nano-BRK V2 board size: H:50mm X W:41mm<br>

<img src="https://github.com/jscottb/pcbs/blob/master/Arduino-Boards/IMG_20200717_075053.jpg" height="260" width="255"><br>
<img src="https://github.com/jscottb/pcbs/blob/master/Arduino-Boards/IMG_20200717_075845.jpg" height="255" width="272"><br>
<br><br>
The Pro Mini breakout: 40.64 x 56.77<br>
<img src="https://github.com/jscottb/pcbs/blob/master/Arduino-Boards/promini.png" height="285" width="215"><br>
<img src="https://github.com/jscottb/pcbs/blob/master/Arduino-Boards/promini2.png" height="300" width="232"><br>
<br><br>
New Nano-BRK (V3): 40.64 x 61.09<br>
<img src="https://github.com/jscottb/pcbs/blob/master/Arduino-Boards/nano_brk_v3.png" height="300" width="215"><br>
