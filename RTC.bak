EESchema Schematic File Version 2
LIBS:power
LIBS:device
LIBS:transistors
LIBS:conn
LIBS:linear
LIBS:regul
LIBS:74xx
LIBS:cmos4000
LIBS:adc-dac
LIBS:memory
LIBS:xilinx
LIBS:microcontrollers
LIBS:dsp
LIBS:microchip
LIBS:analog_switches
LIBS:motorola
LIBS:texas
LIBS:intel
LIBS:audio
LIBS:interface
LIBS:digital-audio
LIBS:philips
LIBS:display
LIBS:cypress
LIBS:siliconi
LIBS:opto
LIBS:atmel
LIBS:contrib
LIBS:valves
LIBS:flame-detect-pcb-cache
LIBS:rpi-power-supply-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 3 3
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L RTC_(DS3231) IC3
U 1 1 5AD56859
P 5850 3650
F 0 "IC3" H 5550 4150 50  0000 C CNN
F 1 "RTC_(DS3231)" H 5850 3150 50  0000 C CNN
F 2 "Housings_SOIC:SOIC-16W_7.5x12.8mm_Pitch1.27mm" H 5850 3050 50  0001 C CIN
F 3 "" H 5850 3850 50  0000 C CNN
	1    5850 3650
	1    0    0    -1  
$EndComp
$Comp
L R R15
U 1 1 5AD568D5
P 6550 3000
F 0 "R15" V 6630 3000 50  0000 C CNN
F 1 "10K" V 6450 3000 50  0000 C CNN
F 2 "Resistors_SMD:R_0805" V 6480 3000 50  0001 C CNN
F 3 "" H 6550 3000 50  0001 C CNN
	1    6550 3000
	1    0    0    -1  
$EndComp
$Comp
L R R16
U 1 1 5AD56945
P 6850 3000
F 0 "R16" V 6930 3000 50  0000 C CNN
F 1 "10K" V 6750 3000 50  0000 C CNN
F 2 "Resistors_SMD:R_0805" V 6780 3000 50  0001 C CNN
F 3 "" H 6850 3000 50  0001 C CNN
	1    6850 3000
	1    0    0    -1  
$EndComp
Wire Wire Line
	6350 3300 7100 3300
Wire Wire Line
	6550 3300 6550 3150
Wire Wire Line
	6350 3400 7100 3400
Wire Wire Line
	6850 3400 6850 3150
Text GLabel 6550 2650 1    60   Input ~ 0
PI_3.3V
Wire Wire Line
	6550 2650 6550 2850
Wire Wire Line
	6850 2850 6850 2750
Wire Wire Line
	6850 2750 6550 2750
Connection ~ 6550 2750
$Comp
L GND #PWR012
U 1 1 5AD56D06
P 6550 4200
F 0 "#PWR012" H 6550 3950 50  0001 C CNN
F 1 "GND" H 6550 4050 50  0000 C CNN
F 2 "" H 6550 4200 50  0001 C CNN
F 3 "" H 6550 4200 50  0001 C CNN
	1    6550 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	6350 3600 6550 3600
Wire Wire Line
	6550 3600 6550 4200
Text GLabel 7100 3500 2    60   Input ~ 0
3.3V
Wire Wire Line
	6350 3500 7100 3500
Text GLabel 4650 3400 0    60   Input ~ 0
PI_3.3V
Wire Wire Line
	4650 3400 5350 3400
$Comp
L C C12
U 1 1 5AD56DCD
P 4850 3700
F 0 "C12" H 4875 3800 50  0000 L CNN
F 1 "1uF" H 4875 3600 50  0000 L CNN
F 2 "Capacitors_SMD:C_0805" H 4888 3550 50  0001 C CNN
F 3 "" H 4850 3700 50  0001 C CNN
	1    4850 3700
	1    0    0    -1  
$EndComp
Wire Wire Line
	4850 3550 4850 3400
Connection ~ 4850 3400
$Comp
L GND #PWR013
U 1 1 5AD56E1A
P 4850 4200
F 0 "#PWR013" H 4850 3950 50  0001 C CNN
F 1 "GND" H 4850 4050 50  0000 C CNN
F 2 "" H 4850 4200 50  0001 C CNN
F 3 "" H 4850 4200 50  0001 C CNN
	1    4850 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	4850 3850 4850 4200
NoConn ~ 5350 3300
NoConn ~ 5350 3500
NoConn ~ 5350 3600
NoConn ~ 5350 3700
NoConn ~ 5350 3800
NoConn ~ 5350 3900
NoConn ~ 5350 4000
NoConn ~ 6350 4000
NoConn ~ 6350 3900
NoConn ~ 6350 3800
NoConn ~ 6350 3700
Text GLabel 7100 3300 2    60   Input ~ 0
PI_SCL
Text GLabel 7100 3400 2    60   Input ~ 0
PI_SDA
Connection ~ 6550 3300
Connection ~ 6850 3400
$EndSCHEMATC
