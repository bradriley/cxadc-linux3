Tony Anderson 2022
tandersn@uw.edu

Convenient scripts to manipulate cx card parameters.

# To install: (Requires sudo to install)

sudo ./inst_scripts

inst_scripts = create simlinks to these scripts in /usr/bin.

## Command Arguments

cx8fsc = set 8fsc sample rate mode.  1x crystal speed.

cx10fsc = set 10fsc sample rate mode. 1.25x crystal speed (only recommended when also using 16bit mode).

cx16bit = set cxadc to return unsigned 16 bit samples.

cx6off = set sixdb to off. This is a 6db gain setting for the AFE. Kind of like a "loud" button on your stereo.

cx6on = set sixdb to on.  (see above).

cx8bit = set cxadc to return unsigned 8 bit samples.

cxvx0 = set cxadc to work off vmux0

cxvx1 = set cxadc to work off vmux1

cxvx2 = set cxadc to work off vmux2

cxfreq = set cx card desired frequency, (same as echo 'somenumber' > tenxfsc. See main wiki for tenxfsc parameter).

cxlevel = set cx card level 0-31.

cxlvlcavdd = A capture script to use that adjusts the gain automatically.

cxvalues = display current values of cx card module parameters.


