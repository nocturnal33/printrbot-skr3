# Printrbot-skr3
* Printrbot Simple Metal
* Originally with REV F board

# PrintrBot Simple Metal with Heated bed

* Marlin 2.1.2
* BTT SKR MINI E3 V2
* BTT TFT24 v1.1
* BLtouch

## WIRING

### Red Green Yellow Blue
<p>X: RGYB</p>
<p>Y: RGYB</p>
<p>Z: BYGR</p>
<p>E: RGYB</p>

## SETTINGS 

### Linear Units:
G21 ; (mm)
### Temperature Units:
M149 C ; Units in Celsius
### Filament settings (Disabled):
M200 S0 D1.75
### Steps per unit:
M92 X77.66 Y314.50 Z4006.60 E95.45
### Max feedrates (units/s):
M203 X500.00 Y500.00 Z12.00 E120.00
### Max Acceleration (units/s2):
M201 X9000.00 Y9000.00 Z500.00 E10000.00
### Acceleration (units/s2) (P<print-accel> R<retract-accel> T<travel-accel>):
M204 P1500.00 R1500.00 T1500.00
### Advanced (B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_jerk> Y<max_jerk> Z<max_jerk> E<max_jerk>):
M205 B20000.00 S0.00 T0.00 X10.00 Y10.00 Z0.20 E2.50
### Home offset:
M206 X0.00 Y0.00 Z0.00
### Hotend PID:
M301 P20.08 I1.20 D77.88
### Bed PID:
M304 P49.54 I8.04 D203.46
### Z-Probe Offset:
M851 X26.00 Y3.00 Z-0.71 ; (mm)
### Stepper driver current:
* M906 X800 Y900 Z900
* M906 T0 E800
### Driver stepping mode:
* M569 S1 X Y Z
* M569 S1 T0 E




