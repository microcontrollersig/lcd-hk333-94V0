# lcd-hk333-94V0

This LCD has 14 pinouts.

From the PDF of the LCD display chip [here](https://github.com/microcontrollersig/lcd-hk333-94V0/blob/master/KS0065B-lcd-datasheet%20-%20Copy.pdf)


And the pinouts here:


```text
1: VSS Ground

2: Vdd power

3: VEE Contrast/backlight

4: RS register selection

5: R/W

6: Enable

7: D0

8: D1

9: D2

10: D3

11: LED+ Power A

12: LED- Power K
```

From Wikipedia


```text
    1. Ground
    2. VCC +3.3 to +5V (typical)
    3. Contrast adjustment (VO) This is an analog input, typically connected to a potentiometer. The user must be able to control this voltage independent of all other adjustments, in order to optimise visibility of the display that varies i.a. with temperature, and, in some cases height above the sea level. With a wrong adjustment the display will seem to malfunction.
    4.Register Select (RS). RS=0: Command, RS=1: Data
    5. Read/Write (R/W). R/W=0: Write, R/W=1: Read (In most applications reading from the HD44780 makes no sense. In that case this pin can be permanently connected to ground and no io pins need to be allocated to steer it.)
    6.Clock (Enable). Falling edge triggered
    7.Bit 0 (Not used in 4-bit operation)
    8.Bit 1 (Not used in 4-bit operation)
    9.Bit 2 (Not used in 4-bit operation)
    10.Bit 3 (Not used in 4-bit operation)
    11.Bit 4
    12.Bit 5
    13.Bit 6
    14.Bit 7
    15.Backlight Anode (+) (If applicable)
    16.Backlight Cathode (-) (If applicable)

```




