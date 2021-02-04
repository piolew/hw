The board can be customised by chosing which componets will be assembled.


# Option 1 - Battery change detector
Without that option each time battery is replaced for Cricket, the board must be manualy wake-up either by IO1 or BIND button.
This option will do that automaticly.

Fit 
R6, R9, R8

Do Not Fit:
R7, R10

# Option 2 - IO2 edge to pulse detector on IO1
Currently the Cricket will wake-up on HI level on IO1.
Additionally while the HI level is present on IO1 the board will keep waking-up periodicly.
This will cause some problems in certain scenario e.g. door sensor.
This option will wake-up only once Cricket for each change of the level on IO1 pin.

Fit 
R7, R10

Do Not Fit:
R6, R9, R8

Also do not fit C6 - this is only to extend pusle width but is not neccesarly for Cricket.

If power via single battery both C1 and C5 should be fitted otherwise can be omitted.
