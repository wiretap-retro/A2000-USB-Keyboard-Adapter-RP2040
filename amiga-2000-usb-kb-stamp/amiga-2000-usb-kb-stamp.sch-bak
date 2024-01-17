EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "A2000 RP2040 Stamp Keyboard Adapter"
Date "2022-08-19"
Rev "1"
Comp "wiretap"
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L SamacSys_Parts:RP2040_Stamp U1
U 1 1 62C068E4
P 1850 3200
F 0 "U1" H 1850 5015 50  0000 C CNN
F 1 "RP2040_Stamp" H 1850 4924 50  0000 C CNN
F 2 "SamacSys_Parts:RP2040_Stamp_THT" H 3150 2550 50  0001 C CNN
F 3 "" H 3150 2550 50  0001 C CNN
	1    1850 3200
	1    0    0    -1  
$EndComp
$Comp
L SamacSys_Parts:USB3075-30-A J1
U 1 1 62C08D3F
P 7800 1700
F 0 "J1" H 8300 1965 50  0000 C CNN
F 1 "USB3075-30-A" H 8300 1874 50  0000 C CNN
F 2 "USB307530A" H 8650 1800 50  0001 L CNN
F 3 "https://componentsearchengine.com/Datasheets/2/USB3075-30-A.pdf" H 8650 1700 50  0001 L CNN
F 4 "GCT (GLOBAL CONNECTOR TECHNOLOGY) - USB3075-30-A - USB Connector, Micro USB Type B, USB 2.0, Receptacle, 5 Ways, Surface Mount, Right Angle" H 8650 1600 50  0001 L CNN "Description"
F 5 "2.7" H 8650 1500 50  0001 L CNN "Height"
F 6 "640-USB3075-30-A" H 8650 1400 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/GCT/USB3075-30-A?qs=KUoIvG%2F9IlbGMJplbp1ybA%3D%3D" H 8650 1300 50  0001 L CNN "Mouser Price/Stock"
F 8 "GCT (GLOBAL CONNECTOR TECHNOLOGY)" H 8650 1200 50  0001 L CNN "Manufacturer_Name"
F 9 "USB3075-30-A" H 8650 1100 50  0001 L CNN "Manufacturer_Part_Number"
	1    7800 1700
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR017
U 1 1 62C0EC1A
P 7600 2450
F 0 "#PWR017" H 7600 2200 50  0001 C CNN
F 1 "GND" H 7605 2277 50  0000 C CNN
F 2 "" H 7600 2450 50  0001 C CNN
F 3 "" H 7600 2450 50  0001 C CNN
	1    7600 2450
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR016
U 1 1 62C0F3AF
P 7600 1500
F 0 "#PWR016" H 7600 1350 50  0001 C CNN
F 1 "+5V" H 7615 1673 50  0000 C CNN
F 2 "" H 7600 1500 50  0001 C CNN
F 3 "" H 7600 1500 50  0001 C CNN
	1    7600 1500
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR02
U 1 1 62C0FB6E
P 1150 1450
F 0 "#PWR02" H 1150 1300 50  0001 C CNN
F 1 "+5V" H 1165 1623 50  0000 C CNN
F 2 "" H 1150 1450 50  0001 C CNN
F 3 "" H 1150 1450 50  0001 C CNN
	1    1150 1450
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR01
U 1 1 62C10093
P 900 1450
F 0 "#PWR01" H 900 1300 50  0001 C CNN
F 1 "+3.3V" H 915 1623 50  0000 C CNN
F 2 "" H 900 1450 50  0001 C CNN
F 3 "" H 900 1450 50  0001 C CNN
	1    900  1450
	1    0    0    -1  
$EndComp
Wire Wire Line
	1150 1450 1150 1650
Wire Wire Line
	1150 1650 1350 1650
Wire Wire Line
	900  1450 900  1750
Wire Wire Line
	900  1750 1350 1750
$Comp
L power:GND #PWR03
U 1 1 62C107DA
P 1150 4700
F 0 "#PWR03" H 1150 4450 50  0001 C CNN
F 1 "GND" H 1155 4527 50  0000 C CNN
F 2 "" H 1150 4700 50  0001 C CNN
F 3 "" H 1150 4700 50  0001 C CNN
	1    1150 4700
	1    0    0    -1  
$EndComp
Wire Wire Line
	1350 4550 1150 4550
Wire Wire Line
	1150 4550 1150 4700
Wire Wire Line
	7600 1500 7600 1700
Wire Wire Line
	7600 1700 7800 1700
Wire Wire Line
	7800 2200 7600 2200
Wire Wire Line
	7600 2200 7600 2350
Wire Wire Line
	7800 2100 7600 2100
Wire Wire Line
	7600 2100 7600 2200
Connection ~ 7600 2200
Wire Wire Line
	8800 1700 8850 1700
Wire Wire Line
	8850 1700 8850 1800
Wire Wire Line
	8850 2350 7600 2350
Connection ~ 7600 2350
Wire Wire Line
	7600 2350 7600 2450
Wire Wire Line
	8800 1800 8850 1800
Connection ~ 8850 1800
Wire Wire Line
	8850 1800 8850 1900
Wire Wire Line
	8800 1900 8850 1900
Connection ~ 8850 1900
Wire Wire Line
	8850 1900 8850 2000
Wire Wire Line
	8800 2000 8850 2000
Connection ~ 8850 2000
Wire Wire Line
	8850 2000 8850 2100
Wire Wire Line
	8800 2100 8850 2100
Connection ~ 8850 2100
Wire Wire Line
	8850 2100 8850 2350
NoConn ~ 7800 2000
Text GLabel 7800 1800 0    50   Input ~ 0
USB_DM
Text GLabel 7800 1900 0    50   Input ~ 0
USB_DP
Text GLabel 1350 2450 0    50   Input ~ 0
USB_DM
Text GLabel 1350 2550 0    50   Input ~ 0
USB_DP
Text GLabel 2350 1650 2    50   Input ~ 0
UART_TX
Text GLabel 2350 1750 2    50   Input ~ 0
UART_RX
Text GLabel 2350 1850 2    50   Input ~ 0
I2C_SDA
Text GLabel 2350 1950 2    50   Input ~ 0
I2C_SCL
Text GLabel 2350 2050 2    50   Input ~ 0
KB_RESET
Text GLabel 2350 2150 2    50   Input ~ 0
KB_DATA
Text GLabel 2350 2250 2    50   Input ~ 0
KB_CLK
$Comp
L SamacSys_Parts:TXS0104ED IC1
U 1 1 62C2140D
P 3950 4650
F 0 "IC1" H 4500 4915 50  0000 C CNN
F 1 "TXS0104ED" H 4500 4824 50  0000 C CNN
F 2 "SOIC127P600X175-14N" H 4900 4750 50  0001 L CNN
F 3 "https://datasheet.datasheetarchive.com/originals/distributors/Datasheets-SFU2/DSASFU100028676.pdf" H 4900 4650 50  0001 L CNN
F 4 "TXS0104ED, Voltage Level Translator, Open Drain 1.65 to 3.6, 2.3 to 5.5V 14-Pin SOIC" H 4900 4550 50  0001 L CNN "Description"
F 5 "1.75" H 4900 4450 50  0001 L CNN "Height"
F 6 "595-TXS0104ED" H 4900 4350 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/Texas-Instruments/TXS0104ED?qs=7kv20MEVUlg5V59AplM5UA%3D%3D" H 4900 4250 50  0001 L CNN "Mouser Price/Stock"
F 8 "Texas Instruments" H 4900 4150 50  0001 L CNN "Manufacturer_Name"
F 9 "TXS0104ED" H 4900 4050 50  0001 L CNN "Manufacturer_Part_Number"
	1    3950 4650
	1    0    0    -1  
$EndComp
NoConn ~ 3950 5150
NoConn ~ 5050 5150
$Comp
L Device:C_Small C1
U 1 1 62C231A2
P 3700 4650
F 0 "C1" V 3471 4650 50  0000 C CNN
F 1 "100nF" V 3562 4650 50  0000 C CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 3700 4650 50  0001 C CNN
F 3 "~" H 3700 4650 50  0001 C CNN
	1    3700 4650
	0    1    1    0   
$EndComp
$Comp
L Device:C_Small C2
U 1 1 62C24D05
P 5300 4650
F 0 "C2" V 5071 4650 50  0000 C CNN
F 1 "100nF" V 5162 4650 50  0000 C CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 5300 4650 50  0001 C CNN
F 3 "~" H 5300 4650 50  0001 C CNN
	1    5300 4650
	0    1    1    0   
$EndComp
$Comp
L Device:R_Small R1
U 1 1 62C250DB
P 5300 5250
F 0 "R1" V 5200 5250 50  0000 C CNN
F 1 "10k" V 5400 5250 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 5300 5250 50  0001 C CNN
F 3 "~" H 5300 5250 50  0001 C CNN
	1    5300 5250
	0    1    1    0   
$EndComp
Wire Wire Line
	5050 4650 5100 4650
Wire Wire Line
	3800 4650 3900 4650
Wire Wire Line
	5050 5250 5200 5250
$Comp
L power:GND #PWR04
U 1 1 62C271BD
P 3400 5550
F 0 "#PWR04" H 3400 5300 50  0001 C CNN
F 1 "GND" H 3405 5377 50  0000 C CNN
F 2 "" H 3400 5550 50  0001 C CNN
F 3 "" H 3400 5550 50  0001 C CNN
	1    3400 5550
	1    0    0    -1  
$EndComp
Wire Wire Line
	3600 4650 3400 4650
Wire Wire Line
	3400 4650 3400 5050
Wire Wire Line
	3950 5050 3400 5050
Connection ~ 3400 5050
$Comp
L power:+5V #PWR08
U 1 1 62C2AB1E
P 5100 4400
F 0 "#PWR08" H 5100 4250 50  0001 C CNN
F 1 "+5V" H 5115 4573 50  0000 C CNN
F 2 "" H 5100 4400 50  0001 C CNN
F 3 "" H 5100 4400 50  0001 C CNN
	1    5100 4400
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR05
U 1 1 62C2BF5A
P 3900 4400
F 0 "#PWR05" H 3900 4250 50  0001 C CNN
F 1 "+3.3V" H 3915 4573 50  0000 C CNN
F 2 "" H 3900 4400 50  0001 C CNN
F 3 "" H 3900 4400 50  0001 C CNN
	1    3900 4400
	1    0    0    -1  
$EndComp
Wire Wire Line
	5100 4400 5100 4650
Connection ~ 5100 4650
Wire Wire Line
	5100 4650 5200 4650
Wire Wire Line
	3900 4400 3900 4650
Connection ~ 3900 4650
Wire Wire Line
	3900 4650 3950 4650
Text GLabel 5050 4950 2    50   Input ~ 0
KB_RESET_RAW
Wire Wire Line
	3400 5050 3400 5500
Text GLabel 5050 4750 2    50   Input ~ 0
KB_DATA_RAW
Text GLabel 5050 4850 2    50   Input ~ 0
KB_CLK_RAW
Wire Wire Line
	3400 5500 5700 5500
Wire Wire Line
	5700 4650 5400 4650
Connection ~ 3400 5500
Wire Wire Line
	3400 5500 3400 5550
Wire Wire Line
	5050 5050 5700 5050
Connection ~ 5700 5050
Wire Wire Line
	5700 5050 5700 4650
Text GLabel 3950 4950 0    50   Input ~ 0
KB_RESET
Text GLabel 3950 4750 0    50   Input ~ 0
KB_DATA
Text GLabel 3950 4850 0    50   Input ~ 0
KB_CLK
Text GLabel 1350 2750 0    50   Input ~ 0
SWDIO
Text GLabel 1350 2850 0    50   Input ~ 0
SWCLK
NoConn ~ 2350 2350
NoConn ~ 2350 2450
NoConn ~ 2350 2550
NoConn ~ 2350 2650
NoConn ~ 2350 2750
NoConn ~ 2350 2850
NoConn ~ 2350 2950
NoConn ~ 2350 3050
NoConn ~ 2350 3150
NoConn ~ 2350 3250
NoConn ~ 2350 3350
NoConn ~ 2350 3450
NoConn ~ 2350 3550
NoConn ~ 2350 3650
NoConn ~ 2350 3750
NoConn ~ 2350 3850
NoConn ~ 2350 3950
NoConn ~ 2350 4050
NoConn ~ 2350 4150
NoConn ~ 2350 4250
NoConn ~ 2350 4350
NoConn ~ 2350 4450
NoConn ~ 2350 4550
Text GLabel 1350 2050 0    50   Input ~ 0
BOOTSEL
$Comp
L Connector_Generic:Conn_01x02 J9
U 1 1 62CD0067
P 7650 4300
F 0 "J9" H 7730 4292 50  0000 L CNN
F 1 "USB_BOOT" H 7730 4201 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 7650 4300 50  0001 C CNN
F 3 "~" H 7650 4300 50  0001 C CNN
	1    7650 4300
	1    0    0    -1  
$EndComp
Text GLabel 7450 4300 0    50   Input ~ 0
BOOTSEL
$Comp
L power:GND #PWR0101
U 1 1 62CD0A68
P 7250 4500
F 0 "#PWR0101" H 7250 4250 50  0001 C CNN
F 1 "GND" H 7255 4327 50  0000 C CNN
F 2 "" H 7250 4500 50  0001 C CNN
F 3 "" H 7250 4500 50  0001 C CNN
	1    7250 4500
	1    0    0    -1  
$EndComp
Wire Wire Line
	7450 4400 7250 4400
Wire Wire Line
	7250 4400 7250 4500
Text Notes 7000 4200 0    50   ~ 0
Jumper for USB Storage Mode
Wire Notes Line
	600  600  9100 600 
Wire Notes Line
	9100 600  9100 5850
Wire Notes Line
	9100 5850 600  5850
Wire Notes Line
	600  5850 600  600 
Wire Notes Line
	3050 600  3050 5850
Wire Notes Line
	6050 600  6050 5850
Text Notes 4100 4150 0    50   ~ 0
Logic Level Conversion
Text Notes 1500 1250 0    50   ~ 0
Raspberry Pi 2040
Text Notes 700  800  0    79   ~ 16
MCU
Text Notes 3150 800  0    79   ~ 16
Amiga I/O
Text Notes 6150 800  0    79   ~ 16
RP2040 I/O
Wire Wire Line
	5700 5050 5700 5500
$Comp
L power:+5V #PWR019
U 1 1 62E9B286
P 5450 5250
F 0 "#PWR019" H 5450 5100 50  0001 C CNN
F 1 "+5V" V 5400 5400 50  0000 C CNN
F 2 "" H 5450 5250 50  0001 C CNN
F 3 "" H 5450 5250 50  0001 C CNN
	1    5450 5250
	0    1    1    0   
$EndComp
Wire Wire Line
	5450 5250 5400 5250
$Comp
L Device:R_Small R4
U 1 1 62E9E441
P 1150 2250
F 0 "R4" V 1050 2250 50  0000 C CNN
F 1 "10k" V 1250 2250 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 1150 2250 50  0001 C CNN
F 3 "~" H 1150 2250 50  0001 C CNN
	1    1150 2250
	0    1    1    0   
$EndComp
Wire Wire Line
	1250 2250 1350 2250
NoConn ~ 1350 1850
Wire Wire Line
	1050 2250 900  2250
Wire Wire Line
	900  2250 900  1750
Connection ~ 900  1750
$Comp
L SamacSys_Parts:1-2199299-5 J3
U 1 1 6300DC2C
P 5450 1100
F 0 "J3" V 5854 1228 50  0000 L CNN
F 1 "CIA" V 5945 1228 50  0000 L CNN
F 2 "DIPS1544W70P254L5080H530Q40N" H 6200 1200 50  0001 L CNN
F 3 "https://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Customer+Drawing%7F2199299%7FA%7Fpdf%7FEnglish%7FENG_CD_2199299_A_baseFilename.pdf%7F1-2199299-5" H 6200 1100 50  0001 L CNN
F 4 "TE CONNECTIVITY - 1-2199299-5 - IC SOCKET, DIP, 40POS, TH" H 6200 1000 50  0001 L CNN "Description"
F 5 "5.3" H 6200 900 50  0001 L CNN "Height"
F 6 "571-1-2199299-5" H 6200 800 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/TE-Connectivity/1-2199299-5?qs=fK8dlpkaUMthXjoyadQV1Q%3D%3D" H 6200 700 50  0001 L CNN "Mouser Price/Stock"
F 8 "TE Connectivity" H 6200 600 50  0001 L CNN "Manufacturer_Name"
F 9 "1-2199299-5" H 6200 500 50  0001 L CNN "Manufacturer_Part_Number"
	1    5450 1100
	0    1    1    0   
$EndComp
$Comp
L SamacSys_Parts:1-2199299-5 J4
U 1 1 63012771
P 5450 2800
F 0 "J4" V 5854 2928 50  0000 L CNN
F 1 "CIA-board" V 5945 2928 50  0000 L CNN
F 2 "DIPS1544W70P254L5080H530Q40N" H 6200 2900 50  0001 L CNN
F 3 "https://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Customer+Drawing%7F2199299%7FA%7Fpdf%7FEnglish%7FENG_CD_2199299_A_baseFilename.pdf%7F1-2199299-5" H 6200 2800 50  0001 L CNN
F 4 "TE CONNECTIVITY - 1-2199299-5 - IC SOCKET, DIP, 40POS, TH" H 6200 2700 50  0001 L CNN "Description"
F 5 "5.3" H 6200 2600 50  0001 L CNN "Height"
F 6 "571-1-2199299-5" H 6200 2500 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/TE-Connectivity/1-2199299-5?qs=fK8dlpkaUMthXjoyadQV1Q%3D%3D" H 6200 2400 50  0001 L CNN "Mouser Price/Stock"
F 8 "TE Connectivity" H 6200 2300 50  0001 L CNN "Manufacturer_Name"
F 9 "1-2199299-5" H 6200 2200 50  0001 L CNN "Manufacturer_Part_Number"
	1    5450 2800
	0    1    1    0   
$EndComp
$Comp
L power:+5V #PWR06
U 1 1 63016D0D
P 3550 1100
F 0 "#PWR06" H 3550 950 50  0001 C CNN
F 1 "+5V" H 3565 1273 50  0000 C CNN
F 2 "" H 3550 1100 50  0001 C CNN
F 3 "" H 3550 1100 50  0001 C CNN
	1    3550 1100
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR07
U 1 1 6301ACDD
P 3550 2800
F 0 "#PWR07" H 3550 2650 50  0001 C CNN
F 1 "+5V" H 3565 2973 50  0000 C CNN
F 2 "" H 3550 2800 50  0001 C CNN
F 3 "" H 3550 2800 50  0001 C CNN
	1    3550 2800
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR09
U 1 1 6301D850
P 5450 1100
F 0 "#PWR09" H 5450 850 50  0001 C CNN
F 1 "GND" H 5455 927 50  0000 C CNN
F 2 "" H 5450 1100 50  0001 C CNN
F 3 "" H 5450 1100 50  0001 C CNN
	1    5450 1100
	-1   0    0    1   
$EndComp
$Comp
L power:GND #PWR010
U 1 1 6301EE2D
P 5450 2800
F 0 "#PWR010" H 5450 2550 50  0001 C CNN
F 1 "GND" H 5455 2627 50  0000 C CNN
F 2 "" H 5450 2800 50  0001 C CNN
F 3 "" H 5450 2800 50  0001 C CNN
	1    5450 2800
	-1   0    0    1   
$EndComp
Text GLabel 3650 1100 1    50   Input ~ 0
19
Text GLabel 3750 1100 1    50   Input ~ 0
18
Text GLabel 3850 1100 1    50   Input ~ 0
17
Text GLabel 3950 1100 1    50   Input ~ 0
16
Text GLabel 4050 1100 1    50   Input ~ 0
15
Text GLabel 4150 1100 1    50   Input ~ 0
14
Text GLabel 4250 1100 1    50   Input ~ 0
13
Text GLabel 4350 1100 1    50   Input ~ 0
12
Text GLabel 4450 1100 1    50   Input ~ 0
11
Text GLabel 4550 1100 1    50   Input ~ 0
10
Text GLabel 4650 1100 1    50   Input ~ 0
9
Text GLabel 4750 1100 1    50   Input ~ 0
8
Text GLabel 4850 1100 1    50   Input ~ 0
7
Text GLabel 4950 1100 1    50   Input ~ 0
6
Text GLabel 5050 1100 1    50   Input ~ 0
5
Text GLabel 5150 1100 1    50   Input ~ 0
4
Text GLabel 5250 1100 1    50   Input ~ 0
3
Text GLabel 5350 1100 1    50   Input ~ 0
2
Text GLabel 3750 2800 1    50   Input ~ 0
18
Text GLabel 3850 2800 1    50   Input ~ 0
17
Text GLabel 3950 2800 1    50   Input ~ 0
16
Text GLabel 4050 2800 1    50   Input ~ 0
15
Text GLabel 4150 2800 1    50   Input ~ 0
14
Text GLabel 4250 2800 1    50   Input ~ 0
13
Text GLabel 4350 2800 1    50   Input ~ 0
12
Text GLabel 4450 2800 1    50   Input ~ 0
11
Text GLabel 4550 2800 1    50   Input ~ 0
10
Text GLabel 4650 2800 1    50   Input ~ 0
9
Text GLabel 4750 2800 1    50   Input ~ 0
8
Text GLabel 4850 2800 1    50   Input ~ 0
7
Text GLabel 4950 2800 1    50   Input ~ 0
6
Text GLabel 5050 2800 1    50   Input ~ 0
5
Text GLabel 5150 2800 1    50   Input ~ 0
4
Text GLabel 5250 2800 1    50   Input ~ 0
3
Text GLabel 5350 2800 1    50   Input ~ 0
2
Text GLabel 3650 2800 1    50   Input ~ 0
19
Text GLabel 3550 2000 3    50   Input ~ 0
21
Text GLabel 3650 2000 3    50   Input ~ 0
22
Text GLabel 3750 2000 3    50   Input ~ 0
23
Text GLabel 3850 2000 3    50   Input ~ 0
24
Text GLabel 3950 2000 3    50   Input ~ 0
25
Text GLabel 4050 2000 3    50   Input ~ 0
26
Text GLabel 4150 2000 3    50   Input ~ 0
27
Text GLabel 4250 2000 3    50   Input ~ 0
28
Text GLabel 4350 2000 3    50   Input ~ 0
29
Text GLabel 4450 2000 3    50   Input ~ 0
30
Text GLabel 4550 2000 3    50   Input ~ 0
31
Text GLabel 4650 2000 3    50   Input ~ 0
32
Text GLabel 4750 2000 3    50   Input ~ 0
33
Text GLabel 4850 2000 3    50   Input ~ 0
34
Text GLabel 4950 2000 3    50   Input ~ 0
35
Text GLabel 5050 2000 3    50   Input ~ 0
36
Text GLabel 5150 2000 3    50   Input ~ 0
37
Text GLabel 5250 2000 3    50   Input ~ 0
38
Text GLabel 3550 3700 3    50   Input ~ 0
21
Text GLabel 3650 3700 3    50   Input ~ 0
22
Text GLabel 3750 3700 3    50   Input ~ 0
23
Text GLabel 3850 3700 3    50   Input ~ 0
24
Text GLabel 3950 3700 3    50   Input ~ 0
25
Text GLabel 4050 3700 3    50   Input ~ 0
26
Text GLabel 4150 3700 3    50   Input ~ 0
27
Text GLabel 4250 3700 3    50   Input ~ 0
28
Text GLabel 4350 3700 3    50   Input ~ 0
29
Text GLabel 4450 3700 3    50   Input ~ 0
30
Text GLabel 4550 3700 3    50   Input ~ 0
31
Text GLabel 4650 3700 3    50   Input ~ 0
32
Text GLabel 4750 3700 3    50   Input ~ 0
33
Text GLabel 4850 3700 3    50   Input ~ 0
34
Text GLabel 4950 3700 3    50   Input ~ 0
35
Text GLabel 5050 3700 3    50   Input ~ 0
36
Text GLabel 5150 3700 3    50   Input ~ 0
37
Text GLabel 5250 3700 3    50   Input ~ 0
38
Text GLabel 5350 2000 3    50   Input ~ 0
KB_DATA_RAW
Text GLabel 5450 2000 3    50   Input ~ 0
KB_CLK_RAW
Text GLabel 5350 3700 3    50   Input ~ 0
KB_DATA_RAW
Text GLabel 5450 3700 3    50   Input ~ 0
KB_CLK_RAW
$Comp
L Connector:Conn_01x01_Female J7
U 1 1 6303F1D3
P 4800 5700
F 0 "J7" H 4828 5726 50  0000 L CNN
F 1 "Amiga_Reset" H 4828 5635 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical" H 4800 5700 50  0001 C CNN
F 3 "~" H 4800 5700 50  0001 C CNN
	1    4800 5700
	1    0    0    -1  
$EndComp
Text GLabel 4600 5700 0    50   Input ~ 0
KB_RESET_RAW
$Comp
L SamacSys_Parts:USB1046-GF-0190-L-B-A J8
U 1 1 63043B80
P 7050 3200
F 0 "J8" H 7500 3465 50  0000 C CNN
F 1 "USB1046-GF-0190-L-B-A" H 7500 3374 50  0000 C CNN
F 2 "USB1046GF0190LBA" H 7800 3300 50  0001 L CNN
F 3 "https://gct.co/files/drawings/usb1046.pdf?v=ccb5d20d-0631-4297-aa3c-9c34fccf9fbc" H 7800 3200 50  0001 L CNN
F 4 "USB Connectors USB A Skt, Top Mount, SMT, R/A, GF, Black, With 1.9mm shell stake, T&R" H 7800 3100 50  0001 L CNN "Description"
F 5 "7.2" H 7800 3000 50  0001 L CNN "Height"
F 6 "640-USB1046GF0190LBA" H 7800 2900 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/GCT/USB1046-GF-0190-L-B-A?qs=KUoIvG%2F9IlbZOJtEsn1unA%3D%3D" H 7800 2800 50  0001 L CNN "Mouser Price/Stock"
F 8 "GCT (GLOBAL CONNECTOR TECHNOLOGY)" H 7800 2700 50  0001 L CNN "Manufacturer_Name"
F 9 "USB1046-GF-0190-L-B-A" H 7800 2600 50  0001 L CNN "Manufacturer_Part_Number"
	1    7050 3200
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR011
U 1 1 63044D26
P 6950 3350
F 0 "#PWR011" H 6950 3100 50  0001 C CNN
F 1 "GND" H 6955 3177 50  0000 C CNN
F 2 "" H 6950 3350 50  0001 C CNN
F 3 "" H 6950 3350 50  0001 C CNN
	1    6950 3350
	1    0    0    -1  
$EndComp
Wire Wire Line
	7050 3200 6950 3200
Wire Wire Line
	6950 3200 6950 3300
Wire Wire Line
	7050 3300 6950 3300
Connection ~ 6950 3300
Wire Wire Line
	6950 3300 6950 3350
$Comp
L power:+5V #PWR020
U 1 1 63049437
P 8200 3200
F 0 "#PWR020" H 8200 3050 50  0001 C CNN
F 1 "+5V" H 8215 3373 50  0000 C CNN
F 2 "" H 8200 3200 50  0001 C CNN
F 3 "" H 8200 3200 50  0001 C CNN
	1    8200 3200
	1    0    0    -1  
$EndComp
Text GLabel 7950 3300 2    50   Input ~ 0
USB_DM
Text GLabel 7950 3400 2    50   Input ~ 0
USB_DP
$Comp
L power:GND #PWR021
U 1 1 6304D6DD
P 8200 3500
F 0 "#PWR021" H 8200 3250 50  0001 C CNN
F 1 "GND" H 8205 3327 50  0000 C CNN
F 2 "" H 8200 3500 50  0001 C CNN
F 3 "" H 8200 3500 50  0001 C CNN
	1    8200 3500
	1    0    0    -1  
$EndComp
Wire Wire Line
	7950 3200 8200 3200
Wire Wire Line
	7950 3500 8200 3500
Text Notes 7100 1250 0    50   ~ 0
USB Connections
Text GLabel 6650 2050 0    50   Input ~ 0
USB_DP
Text GLabel 6650 1950 0    50   Input ~ 0
USB_DM
Wire Wire Line
	6500 2150 6650 2150
Wire Wire Line
	6500 2250 6500 2150
Wire Wire Line
	6500 1850 6500 1750
Wire Wire Line
	6650 1850 6500 1850
$Comp
L power:GND #PWR015
U 1 1 62C3238D
P 6500 2250
F 0 "#PWR015" H 6500 2000 50  0001 C CNN
F 1 "GND" H 6505 2077 50  0000 C CNN
F 2 "" H 6500 2250 50  0001 C CNN
F 3 "" H 6500 2250 50  0001 C CNN
	1    6500 2250
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR014
U 1 1 62C31A74
P 6500 1750
F 0 "#PWR014" H 6500 1600 50  0001 C CNN
F 1 "+5V" H 6515 1923 50  0000 C CNN
F 2 "" H 6500 1750 50  0001 C CNN
F 3 "" H 6500 1750 50  0001 C CNN
	1    6500 1750
	1    0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_01x04 J2
U 1 1 62C3121F
P 6850 1950
F 0 "J2" H 6930 1942 50  0000 L CNN
F 1 "USB_HEADER" H 6930 1851 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Horizontal" H 6850 1950 50  0001 C CNN
F 3 "~" H 6850 1950 50  0001 C CNN
	1    6850 1950
	1    0    0    -1  
$EndComp
$EndSCHEMATC
