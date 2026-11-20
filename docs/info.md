## How it works

It is a basic D Latch built with 4 NAND gates that takes 2 inputs (`D` and `En`) and outputs `Q` and `Q_not`[cite: 1, 3]. When `En` is high, `Q` follows `D`; when `En` goes low, the latch holds its previous state[cite: 1, 3].

## How to test

Utilize the `D` (`ui[0]`) and `En` (`ui[1]`) signals to observe the values of `Q` (`uo[0]`) and `Q_not` (`uo[1]`), and verify that the last output state holds when `En` is off[cite: 1, 3].

## External hardware

LEDs and DIP switches[cite: 1, 3]
