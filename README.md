> Note:
> This repo is not finished yet. Will fix up asap

# About
I am really into keybeards, especially switches and building keyboards from scratch.


# My keyboards
Rigt now, I have two daily drivers:

### Ergodox EZ
This keyboard is the keyboard I use at work, and the keyboard that really sparked my interest for keyboards, ahd espesially split and ortholinear ones.

When I boght the keyboard, they initially had cherry MX clear switches in it, but they were quickly swapped for Zeal Zilent v2 67g for the modifiers and 67g Zandas (Holy panda housing with Zilent stem).

The Holy pandas have later been switched out in favor of normal zilents, while the Holy pandas will have a better purpose to serve later.

More about this keyboard can be found [Here](ErgodoxEZ)


### Iris Rev 4
[tmp here](IrisRev4)
The keyboard I use at home is Iris Rev 4. 
Everything but keycaps and switches are from Keeb.io.
The keyboard has steel plates with an acryllic translusent middle-layer. 
The switches are Holy pandas, while keycaps are just a cheap clear set I got from amazon.

# Works in progress

### ReDox

The ReDox is a REduced ergoDOX. It removes some of the keys, while also making keys smaller (1,75u keys are now 1,25 etc)

I have ordered the ReDox from falba.tech. It will come with bamboo cases, aluminium top-plate and mill-max sockets. This build will then be almost completed upon arrival. All I have to do is insert the switches (spring-lubed 62g Aqua zilents) and keycaps (generic black DSA blanks)

### Lily58

I recieved some acrylic from my father, and a guy on the norwegian mechanical keyboard discord contacted me and wanted to collab on a build of lily58.

I will be supplying the acrylic and acryl cutting while he will supply the PCBs and electronics. This will be very fun, exciting and probably very complicated. It will be the first keyboard build where everything is made from scratch!

The PCBs were sent for manufacturing custom, the cases are laser cut by us, and every diode, switch, arduino is soldered on by us by hand.

Lily58 have the option to add OLED screens above the microcontroller, and since this is so cheap, of course I'll try to add that!

All parts are ordered except m2 screws and m2 standoffs.

# Projects

### 2x4 Macroboard
''Insert pictures here''

This was my first dabble in making keyboards, and I am really happy with how it turned out.
I started by buying an Arduino pro micro, a soldering iron and some wire.
Since the plate I printed only had 8 slots for switches, and the pro micro had 8 data-pins, I could solder each switch to their own data-pin.
This helps with the complexity of the wiring a lot, since you dont need to think about matrix-soldering or any resistors.
I programmed the pro micro to send the signals F13, F14, ..., F20, since these buttons rarely have a use in an operating system, and they are natively accepted. That is perfect when you are setting macros, since you can just add that keypress to any shortcut, but you can also write an AHK(Auto Hot Key) script to do something else.

The code for the arduino and the AHK script I wrote will be added later [here](projects)

This macroboard was a gift for secret santa for christmas 2019.

### 7x7 Switch tester

This was just a small project with just printing a plate that could hold multiple different switches which I could find out what switches I liked and not.
I ordered two of every different switch I could find on two different websites, and populated the switch tester.
This has seen more use than I anticipated, since people that have been introduced to this hobby after me has had a chance to both test different keyboard sizes (since I have many different types), but also figured out what switches they would like.

Pictures of the switch tester and the 3d-file will be poster [here](projects)


### 3x3 macroboard, BDN9

The [BDN9](small projects/BDN9) was a set from keeb.io. I have installed two rotary encoders instead of switches in two of the slots.
It has two steel plates as top- and bottom plate, and holy pandas are installed. I also soldered on a led-strip with three leds, but have had little success of programming these.