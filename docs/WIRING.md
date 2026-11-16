## Power

Line|Pin
-|-
VSYS (battery in)|39
3V3 out|36
GND|38

## Debug

Line (JST color)|Pico pin|Probe pin
-|-|-
TX (white)|1|6
RX (grey)|2|7
SWCLK (purple)|SWCLK|4
GND (blue)|GND|3
SWDIO (green)|SWDIO|5

# TODO: format the rest properly

-- KEYPAD

wiersze - 19(14),20(15),21(16),22(17)
kolumny - 24(18),25(19),26(20),27(21),29(22)

-- EKRAN

(ekran - pi)
DC   - 11
CS   - 12
CLK  - 14
DIN  - 15
RST  - 16
BUSY - 17

VCC  - VSYS 3.3V
GND  - GND

-- SD

MISO - 6
MOSI - 10
SCLK - 9
CS   - 7

VCC  - VSYS 3.3V
GND  - GND

-- BATERIA (ADC)

BAT+ -> dzielnik 100k/100k -> 34 (ADC2)
BAT- -> 33 (AGND)

-- WOLNE

4, 5, 32, 31
