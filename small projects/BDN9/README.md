# BDN9 keyboard from keeb.io

BDN9 is a set you can buy from keeb.io [here](https://keeb.io/collections/frontpage/products/bdn9-3x3-9-key-macropad-rotary-encoder-support?variant=15959960944734)

It has support for up to two rotary encoders, which I wanted.

## Parts list

| Part name | Quantity | Remarks |
|--------|---------|----------- |
| BDN9 PCB | 1 piece ||
| switch plate | 1 piece ||
| Bottom plate | 1 piece ||
| 6mm M2 screw | 8 pieces ||
| 12mm M2 standoff | 4 pieces ||
| Reset switch | 1 piece ||
| 470Ω resistor | 10 pieces ||
| MOSFET | 1 piece |Optional: For LED support. AO3416 |
| Switches | 7-9 pieces |9 if no rotary encoders, 7 if 2|
| Microcontroller | 1 piece |Pro micro/Elite-c/Proton C|
| LED | 1-9 pieces |Optional: if you want LEDs|
| Rotary encoder w/knob | 1-2 pieces | Optional: EC11 is preferred, EC12 can work |
| RGB LED strip or loose RGB LEDs | 1-4 | WS2812B LED strip or loose |

## Build guide

### Build summary

1. Prepare components
2. Solder components 
  1. Solder resistores (for LEDS, optional)
  2. Solder MOSFET (for LEDs, optional)
  3. Solder puch button
  4. Solder Microcontroller header pins
3. Solder rotary encoders (optional)
4. Solder switches
5. Solder LEDs (optional)
6. Flash Microcontroller
7. Solder Pro Micro
8. Solder RGB underglow LEDs or strip (optional)
9. Assemble case