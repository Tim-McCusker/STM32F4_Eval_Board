EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 2 2
Title "Sensors"
Date "2020-11-09"
Rev "0.00"
Comp "TM.Tronics"
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Sensor_Motion:LSM6DS3 U4
U 1 1 5FAA53A7
P 2250 2650
F 0 "U4" H 2600 3150 50  0000 L CNN
F 1 "LSM6DS3" H 2450 2150 50  0000 L CNN
F 2 "Package_LGA:LGA-14_3x2.5mm_P0.5mm_LayoutBorder3x4y" H 1850 1950 50  0001 L CNN
F 3 "www.st.com/resource/en/datasheet/lsm6ds3.pdf" H 2350 2000 50  0001 C CNN
F 4 "C95231" H 2250 2650 50  0001 C CNN "LCSC Part #"
	1    2250 2650
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C17
U 1 1 5FAA654B
P 2300 1400
F 0 "C17" H 2208 1354 50  0000 R CNN
F 1 "100n" H 2208 1445 50  0000 R CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 2300 1400 50  0001 C CNN
F 3 "~" H 2300 1400 50  0001 C CNN
F 4 "C1525" H 2300 1400 50  0001 C CNN "LCSC Part #"
	1    2300 1400
	-1   0    0    1   
$EndComp
$Comp
L Device:C_Small C18
U 1 1 5FAA7708
P 2700 1400
F 0 "C18" H 2792 1446 50  0000 L CNN
F 1 "100n" H 2792 1355 50  0000 L CNN
F 2 "Capacitor_SMD:C_0402_1005Metric" H 2700 1400 50  0001 C CNN
F 3 "~" H 2700 1400 50  0001 C CNN
F 4 "C1525" H 2700 1400 50  0001 C CNN "LCSC Part #"
	1    2700 1400
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR04
U 1 1 5FAA9900
P 2300 1250
F 0 "#PWR04" H 2300 1100 50  0001 C CNN
F 1 "+3.3V" H 2315 1423 50  0000 C CNN
F 2 "" H 2300 1250 50  0001 C CNN
F 3 "" H 2300 1250 50  0001 C CNN
	1    2300 1250
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR05
U 1 1 5FAAA370
P 2300 1550
F 0 "#PWR05" H 2300 1300 50  0001 C CNN
F 1 "GND" H 2305 1377 50  0000 C CNN
F 2 "" H 2300 1550 50  0001 C CNN
F 3 "" H 2300 1550 50  0001 C CNN
	1    2300 1550
	1    0    0    -1  
$EndComp
Wire Wire Line
	2300 1550 2300 1500
Wire Wire Line
	2300 1300 2300 1250
Wire Wire Line
	2700 1300 2300 1300
Connection ~ 2300 1300
Wire Wire Line
	2700 1500 2300 1500
Connection ~ 2300 1500
$Comp
L power:+3.3V #PWR02
U 1 1 5FAAC29B
P 2250 2050
F 0 "#PWR02" H 2250 1900 50  0001 C CNN
F 1 "+3.3V" H 2150 2200 50  0000 C CNN
F 2 "" H 2250 2050 50  0001 C CNN
F 3 "" H 2250 2050 50  0001 C CNN
	1    2250 2050
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR06
U 1 1 5FAACA39
P 2350 2050
F 0 "#PWR06" H 2350 1900 50  0001 C CNN
F 1 "+3.3V" H 2400 2200 50  0000 C CNN
F 2 "" H 2350 2050 50  0001 C CNN
F 3 "" H 2350 2050 50  0001 C CNN
	1    2350 2050
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR03
U 1 1 5FAACF99
P 2250 3250
F 0 "#PWR03" H 2250 3000 50  0001 C CNN
F 1 "GND" H 2200 3100 50  0000 C CNN
F 2 "" H 2250 3250 50  0001 C CNN
F 3 "" H 2250 3250 50  0001 C CNN
	1    2250 3250
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR07
U 1 1 5FAAD515
P 2350 3250
F 0 "#PWR07" H 2350 3000 50  0001 C CNN
F 1 "GND" H 2400 3100 50  0000 C CNN
F 2 "" H 2350 3250 50  0001 C CNN
F 3 "" H 2350 3250 50  0001 C CNN
	1    2350 3250
	1    0    0    -1  
$EndComp
Text GLabel 2850 2350 2    50   Output ~ 0
IMU_INT1
Text GLabel 2850 2450 2    50   Output ~ 0
IMU_INT2
Text GLabel 1650 2950 0    50   Input ~ 0
IMU_CS
Text GLabel 1650 2850 0    50   Input ~ 0
IMU_I2C_SCL
Text GLabel 1650 2750 0    50   BiDi ~ 0
IMU_I2C_SDA
$Comp
L power:GND #PWR01
U 1 1 5FAAE5CC
P 1050 2650
F 0 "#PWR01" H 1050 2400 50  0001 C CNN
F 1 "GND" H 1055 2477 50  0000 C CNN
F 2 "" H 1050 2650 50  0001 C CNN
F 3 "" H 1050 2650 50  0001 C CNN
	1    1050 2650
	1    0    0    -1  
$EndComp
Wire Wire Line
	1050 2650 1050 2550
Wire Wire Line
	1050 2550 1650 2550
Wire Wire Line
	1650 2450 1050 2450
Wire Wire Line
	1050 2450 1050 2550
Connection ~ 1050 2550
Text Notes 600  800  0    157  ~ 0
Inertial Mesaurement Unit
Wire Notes Line
	3900 500  3900 3600
Wire Wire Line
	1650 2350 1050 2350
Wire Wire Line
	1050 2350 1050 2450
Connection ~ 1050 2450
Text Notes 1150 2150 0    50   ~ 0
I2C Addr: 01101010b
$Comp
L Device:R_Small R12
U 1 1 5FAC0CE9
P 5700 2550
F 0 "R12" V 5775 2550 50  0000 C CNN
F 1 "10k" V 5850 2550 50  0000 C CNN
F 2 "Resistor_SMD:R_0402_1005Metric" H 5700 2550 50  0001 C CNN
F 3 "~" H 5700 2550 50  0001 C CNN
F 4 "C25744" H 5700 2550 50  0001 C CNN "LCSC Part #"
	1    5700 2550
	0    1    1    0   
$EndComp
Wire Wire Line
	5400 2350 5400 2200
$Comp
L power:GND #PWR08
U 1 1 5FAC255B
P 5300 2550
F 0 "#PWR08" H 5300 2300 50  0001 C CNN
F 1 "GND" H 5305 2377 50  0000 C CNN
F 2 "" H 5300 2550 50  0001 C CNN
F 3 "" H 5300 2550 50  0001 C CNN
	1    5300 2550
	1    0    0    -1  
$EndComp
Text GLabel 6100 2350 2    50   Output ~ 0
SYS_TEMP
$Comp
L power:+3.3V #PWR09
U 1 1 5FAC3099
P 6100 1850
F 0 "#PWR09" H 6100 1700 50  0001 C CNN
F 1 "+3.3V" H 6115 2023 50  0000 C CNN
F 2 "" H 6100 1850 50  0001 C CNN
F 3 "" H 6100 1850 50  0001 C CNN
	1    6100 1850
	1    0    0    -1  
$EndComp
$Comp
L TM_Lib:LM335ADT U5
U 1 1 5FABDDC9
P 5650 1750
F 0 "U5" H 5675 1825 50  0000 C CNN
F 1 "LM335ADT" H 5675 1734 50  0000 C CNN
F 2 "Package_SO:SOIC-8_3.9x4.9mm_P1.27mm" H 5650 1750 50  0001 C CNN
F 3 "" H 5650 1750 50  0001 C CNN
F 4 "C361027" H 5650 1750 50  0001 C CNN "LCSC Part #"
	1    5650 1750
	1    0    0    -1  
$EndComp
Wire Wire Line
	6050 2350 6050 2550
Wire Wire Line
	6050 2550 5800 2550
Wire Wire Line
	5300 2550 5300 2350
Connection ~ 5300 2550
Wire Wire Line
	5300 2550 5600 2550
Wire Wire Line
	6100 2350 6050 2350
Connection ~ 6050 2350
Wire Wire Line
	6050 1900 6100 1900
Wire Wire Line
	6100 1900 6100 1850
NoConn ~ 5300 1900
NoConn ~ 5300 2050
NoConn ~ 5300 2200
NoConn ~ 6050 2050
NoConn ~ 6050 2200
Text Notes 4000 800  0    157  ~ 0
On-board Temperature Sensor
Wire Notes Line
	7800 3600 7800 500 
Wire Notes Line
	500  3600 7800 3600
Text Notes 4750 3000 0    79   ~ 0
Calibrated for 2.982V @ 25degC
Text Notes 5350 3150 0    79   ~ 0
10mV/degK
$EndSCHEMATC
