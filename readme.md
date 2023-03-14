# 100W RGB LED Constant Current Driver
A constant current driver made to to drive 100W RGB COB LEDs. The driver has 3x 1A outputs at up to 36V in order to drive R,G, and B LEDs. The board is powered with 24V, and the driver is controlled by an ESP8266 running WLED. 

[Interactive BOM](https://htmlpreview.github.io/?https://raw.githubusercontent.com/wszeto9/LED-Control-Board-V2/main/breakout_boards/ibom.html)
<h2> Features:</h2>
<ul>

<li>Costs under $10 per Control board </li>
<li>USB-C PD/QC input (12V) for analog RGB strips</li>
<li>USB-C input (5V) for addressible RGB strips</li>
<li>Intended to be used with 12V/1.5A (18W) USB-C` power banks for portability</li>
<li>Panelized in a 4x2 panel of 100x100mm for minimal fabrication costs at JLCPCB</li>
<li>Individual PCBs are designed to be small and not noticible in deployment</li>
<li>Auto-reset circuit for ESP8266 reduces the equipment needed to program boards</li>
<li>Exposed breakout headers allows customization of voltages that are used</li>
<li>LEDs to debug circuits </li>
<li>Programming side (Right) can be cut off and seperated from controller side (Left) to reduce the chips needed to program boards to further reduce cost</li>
</ul>

![Pinout](breakout_boards/Documentation/pinout_config-01.jpg)
Pinout

![LED Inducators](breakout_boards/Documentation/pinout_config-02.jpg)
LED Indicators

![Top_unpopulated](breakout_boards/Documentation/ISO_board.png)
Populated Board
