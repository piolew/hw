# The board can be customised by chosing which componets will be assembled.

## Option 1 - Battery change detector
This option alows Cricket to wake-up automaticly each time battery is replaced.

Files:\
pick & place  - 1AAABED_C1_pp_option1.txt

## Option 2 - IO2 edge to pulse detector on IO1
Currently the Cricket will wake-up on HI level on IO1 only.
Additionall,y during presence of HI level on IO1 the board will keep waking-up periodicly.
This will cause some problems in certain scenario e.g. door sensor.
This option will wake-up only once Cricket for each change of the level on IO1 pin.

Files:\
pick & place  - 1AAABED_C1_pp_option2.txt

# Common files
gerbers       - 1AAABED_C1-20210201T081651Z-001.zip\
schematics    - 1AAABED_C1_schematics.pdf\
BOM           - 1AAABED_C1_BOM.xlsx\
