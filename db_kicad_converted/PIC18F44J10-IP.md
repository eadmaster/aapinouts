16K Flash, 1K SRAM, ADC, DIP40
Flash-Based 8-Bit Microcontroller
http://ww1.microchip.com/downloads/en/DeviceDoc/39682E.pdf


	                     +-----------+
	             ~{MCLR} |[ 1]   [40]| RB7/KBI3/PGD
	             RA0/AN0 |[ 2]   [39]| RB6/KBI2/PGC
	             RA1/AN1 |[ 3]   [38]| RB5/KBI1/T0CKI/C1OUT
	 RA2/AN2/VREF-/CVREF |[ 4]   [37]| RB4/KBI0/AN11
	       RA3/AN3/VREF+ |[ 5]   [36]| RB3/CCP2/AN9
	        VDDCORE/VCAP |[ 6]   [35]| RB2/INT2/AN8
	RA5/AN4/~{SS1}/C2OUT |[ 7]   [34]| RB1/INT1/AN10
	       ~{RD}/AN5/RE0 |[ 8]   [33]| RB0/INT0/FLT0/AN12
	       ~{WR}/AN6/RE1 |[ 9]   [32]| VDD
	       ~{CS}/AN7/RE2 |[10]   [31]| VSS
	                 VDD |[11]   [30]| PSP7/P1D/RD7
	                 VSS |[12]   [29]| PSP6/P1C/RD6
	           OSC1/CLKI |[13]   [28]| PSP5/P1B/RD5
	           OSC2/CLK0 |[14]   [27]| PSP4/RD4
	     T1OSO/T1CKI/RC0 |[15]   [26]| RX/DT/RC7
	      T1OSI/CCP2/RC1 |[16]   [25]| TX/CK/RC6
	        P1A/CCP1/RC2 |[17]   [24]| SDO1/RC5
	       SCK1/SCL1/RC3 |[18]   [23]| SDI1/SDA1/RC4
	  PSP0/SCK2/SCL2/RD0 |[19]   [22]| PSP3/~{SS2}/RD3
	  PSP1/SDI2/SDA2/RD1 |[20]   [21]| PSP2/SDO2/RD2
	                     +-----------+


generated by https://github.com/FBEZ/Pinout-AsciiArt from https://github.com/ask6483/kicad-symbols/blob/master/MCU_Microchip_PIC18.kicad_sym