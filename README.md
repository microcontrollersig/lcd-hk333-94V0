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

11: D4

12: D5

13: D6

14: D7

```

Arduino LiquidCrystal library can be used in both 4-bit and 8-bit mode.

LiquidCrystal lcd(rs, en, d4, d5, d6, d7);

In 4-bit mode

```text
d4: 11
d5: 12
d6: 13
d7: 14
```

In 8-bit mode

```text
d0: 7
d1: 8
d2: 9
d3: 10
d4: 11
d5: 12
d6: 13
d7: 14
```





