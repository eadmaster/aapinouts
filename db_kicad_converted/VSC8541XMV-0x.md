Single Port Gigabit Ethernet, GMII/RGMII/MII/RMII Interfaces, QFN-68
Gigabit Ethernet PHY GMII RGMII MII RMII
https://ethernet.microsemi.com/products/download.php?fid=7978&number=vsc8541


	             +-----------+
	    REF_REXT |[ 1]   [69]| VSS
	      VDD25A |[ 2]   [68]| VDD1A
	      P0_D3N |[ 3]   [67]| REF_FILT
	      P0_D3P |[ 4]   [66]| RESERVED_0
	       VDD1A |[ 5]   [65]| RESERVED_1
	      P0_D2N |[ 6]   [64]| XTAL2
	      P0_D2P |[ 7]   [63]| XTAL1
	      VDD25A |[ 8]   [62]| REFCLK_SEL_0
	      P0_D1N |[ 9]   [61]| REFCLK_SEL_1
	      P0_D1P |[10]   [60]| LED0
	      VDD25A |[11]   [59]| LED1
	      P0_D0N |[12]   [58]| VDDIO
	      P0_D0P |[13]   [57]| CLK_SQUELCH_IN
	       VDD1A |[14]   [56]| COMA_MODE
	     THERMDA |[15]   [55]| RCVRD_CLK
	 THERMDC_VSS |[16]   [54]| CLKOUT
	        VDD1 |[17]   [53]| NRESET
	         COL |[18]   [52]| FASTLINK_FAIL
	         CRS |[19]   [51]| MDINT
	        RXD7 |[20]   [50]| MDIO
	        RXD6 |[21]   [49]| VDDMDIO
	      VDDMAC |[22]   [48]| MDC
	        RXD5 |[23]   [47]| TXD7
	        RXD4 |[24]   [46]| TXD6
	        RXD3 |[25]   [45]| TXD5
	        RXD2 |[26]   [44]| VDDMAC
	        RXD1 |[27]   [43]| TXD4
	      VDDMAC |[28]   [42]| TXD3
	        RXD0 |[29]   [41]| TXD2
	RX_DV/RX_CTL |[30]   [40]| TXD1
	       RX_ER |[31]   [39]| VDDMAC
	      RX_CLK |[32]   [38]| TXD0
	TX_EN/TX_CTL |[33]   [37]| GTX_CLK
	        VDD1 |[34]   [36]| MII_TXCLK
	             +-----------+


generated by https://github.com/FBEZ/Pinout-AsciiArt from https://github.com/ask6483/kicad-symbols/blob/master/Interface_Ethernet.kicad_sym