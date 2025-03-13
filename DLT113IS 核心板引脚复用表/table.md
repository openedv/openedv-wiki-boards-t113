---
title: '核心板接口数据手册'
sidebar_position: 1
---

## ATK-CLT113IS核心板接口数据手册

| 邮票孔引脚号 | 芯片引脚号 | 出厂系统默认配置 | 参考电平 | 可复用功能(需结合具体需求分析)                               |
| ------------ | ---------- | ---------------- | -------- | ------------------------------------------------------------ |
| 1            | \          | VCC3V3_CORE      |          |                                                              |
| 2            | \          | VCC3V3_CORE      |          |                                                              |
| 3            | \          | VCC3V3_CORE      |          |                                                              |
| 4            | \          | GND              |          |                                                              |
| 5            | \          | GND              |          |                                                              |
| 6            | D17        | MICIN3_P         |          |                                                              |
| 7            | D16        | MICIN3_N         |          |                                                              |
| 8            | \          | GND              |          |                                                              |
| 9            | A17        | MIC-DET          |          |                                                              |
| 10           | E17        | HBIAS            |          |                                                              |
| 11           | \          | GND              |          |                                                              |
| 12           | F13        | HPOUTL           |          |                                                              |
| 13           | E13        | HPOUTFB          |          |                                                              |
| 14           | D13        | HPOUTR           |          |                                                              |
| 15           | \          | GND              |          |                                                              |
| 16           | A13        | HP-DET           |          |                                                              |
| 17           | A18        | FEL              |          |                                                              |
| 18           | N3         | NMI              |          |                                                              |
| 19           | M2         | RESET            |          |                                                              |
| 20           | \          | PWR_ON           |          |                                                              |
| 21           | \          | GND              |          |                                                              |
| 22           | F1         | UART2_RX         | 3V3      | PC1/UART2-RX/TWI2-SDA/PC-EINT1                               |
| 23           | F2         | UART2_TX         | 3V3      | PC0/UART2-TX/TWI2-SCK/LEDC-DO/PC-EINT0                       |
| 24           | \          | GND              |          |                                                              |
| 25           | D3         | SDC0-DET         | 3V3      | PF6/SPDIF-OUT/IR-RX/I2S2-MCLK/PWM5/PF-EINT6                  |
| 26           | C2         | SDC0-D1          | 3V3      | PF0/SDC0-D1/JTAG-MS/R-JTAG-MS/I2S2-DOUT1/I2S2-DIN0/PF-EINT0  |
| 27           | C1         | SDC0-D0          | 3V3      | PF1/SDC0-D0/JTAG-DI/R-JTAG-DI/I2S2-DOUT0/I2S2-DIN1/PF-EINT1  |
| 28           | D2         | SDC0-CLK         | 3V3      | PF2/SDC0-CLK/UART0-TX/TWI0-SCK/LEDC-DO/SPDIF-IN/PF-EINT2     |
| 29           | D1         | SDC0-CMD         | 3V3      | PF3/SDC0-CMD/JTAG-DO/R-JTAG-DO/I2S2-BCLK/PF-EINT3            |
| 30           | E3         | SDC0-D3          | 3V3      | PF4/SDC0-D3/UART0-RX/TWI0-SDA/PWM6/IR-TX/PF-EINT4            |
| 31           | E2         | SDC0-D2          | 3V3      | PF5/SDC0-D2/JTAG-CK/R-JTAG-CK/I2S2-LRCK/PF-EINT5             |
| 32           | \          | GND              |          |                                                              |
| 33           | D7         | UART0_RX         | 3V3      | PG18/UART2-RX/TWI3-SDA/PWM6/CLK-FANOUT1/SPDIF-OUT/UART0-RX/PG-EINT18 |
| 34           | E7         | UART0_TX         | 3V3      | PG17/UART2-TX/TWI3-SCK/PWM7/CLK-FANOUT0/IR-TX/UART0-TX/PG-EINT17 |
| 35           | F7         | USB_ID           | 3V3      | PG16/IR-RX/TCON-TRIG/PWM5/CLK-FANOUT2/SPDIF-IN/LEDC-DO/PG-EINT16 |
| 36           | F6         | SPK_CTRL         | 3V3      | PG15/I2S1-DOUT0/TWI2-SDA/MDIO/I2S1-DIN1/SPI0-HOLD/UART1-CTS/PG-EINT15 |
| 37           | E6         | GMAC_RSTn_L      | 3V3      | PG14/I2S1-DIN0/TWI2-SCK/MDC/I2S1-DOUT1/SPI0-WP/UART1-RTS/PG-EINT14 |
| 38           | D6         | I2C0-SDA         | 3V3      | PG13/I2S1-BCLK/TWI0-SDA/RGMII-CLKIN/RMII-RXER/PWM2/LEDC-DO/UART1-RX/PG-EINT13 |
| 39           | D5         | I2C0-SCL         | 3V3      | PG12/I2S1-LRCK/TWI0-SCK/RGMII-TXCTRL/RMII-TXEN/CLK-FANOUT2/PWM0/UART1-TX/PG-EINT12 |
| 40           | D4         | LCD_RST          | 3V3      | PG11/I2S1-MCLK/TWI3-SDA/EPHY-25M/CLK-FANOUT1/TCON-TRIG/PG-EINT11 |
| 41           | C6         | PWM3             | 3V3      | PG10/PWM3/TWI3-SCK/RGMII-RXCK/CLK-FANOUT0/IR-RX/PG-EINT10    |
| 42           | B6         | I2C1-SDA         | 3V3      | PG9/UART1-CTS/TWI1-SDA/RGMII-RXD3/UART3-RX/PG-EINT9          |
| 43           | A6         | I2C1-SCL         | 3V3      | PG8/UART1-RTS/TWI1-SCK/RGMII-RXD2/UART3-TX/PG-EINT8          |
| 44           | C5         | UART1_RX         | 3V3      | PG7/UART1-RX/TWI2-SDA/RGMII-TXD3/SPDIF-IN/PG-EINT7           |
| 45           | B5         | UART1_TX         | 3V3      | PG6/UART1-TX/TWI2-SCK/RGMII-TXD2/PWM1/PG-EINT6               |
| 46           | B4         | UART5_RX         | 3V3      | PG5/SDC1-D3/UART5-RX/RGMII-TXD1/RMII-TXD1/PWM4/PG-EINT5      |
| 47           | A4         | UART5_TX         | 3V3      | PG4/SDC1-D2/UART5-TX/RGMII-TXD0/RMII-TXD0/PWM5/PG-EINT4      |
| 48           | C3         | UART4_RX         | 3V3      | PG3/SDC1-D1/UART3-CTS/RGMII-TXCK/RMII-TXCK/UART4-RX/PG-EINT3 |
| 49           | A3         | UART4_TX         | 3V3      | PG2/SDC1-D0/UART3-RTS/RGMII-RXD1/RMII-RXD1/UART4-TX/PG-EINT2 |
| 50           | B3         | CT_RST           | 3V3      | PG1/SDC1-CMD/UART3-RX/RGMII-RXD0/RMII-RXD0/PWM6/PG-EINT1     |
| 51           | B2         | CT_INT           | 3V3      | PG0/SDC1-CLK/UART3-TX/RGMII-RXCTRL/RMII-CRS-DV/PWM7/PG-EINT0 |
| 52           | \          | GND              |          |                                                              |
| 53           | M6         | I2C3-SDA         | 3V3      | PE17/TWI3-SDA/D-JTAG-CK/IR-TX/I2S0-MCLK/DMIC-CLK/PE-EINT17   |
| 54           | N6         | I2C-SCL          | 3V3      | PE16/TWI3-SCK/D-JTAG-DO/PWM7/I2S0-BCLK/DMIC-DATA0/PE-EINT16  |
| 55           | N5         | GMAC_RXCLK       | 3V3      | PE15/TWI1-SDA/D-JTAG-DI/PWM6/I2S0-LRCK/DMIC-DATA1/RGMII-RXCK/PE-EINT15 |
| 56           | N4         | GMAC_RXD3        | 3V3      | PE14/TWI1-SCK/D-JTAG-MS/I2S0-DOUT1/I2S0-DIN0/DMIC-DATA2/RGMII-RXD3/PE-EINT14 |
| 57           | R4         | GMAC_RXD2        | 3V3      | PE13/TWI2-SDA/PWM5/I2S0-DOUT0/I2S0-DIN1/DMIC-DATA3/RGMII-RXD2/PE-EINT13 |
| 58           | R5         | GMAC_TXD3        | 3V3      | PE12/TWI2-SCK/NCSI0-FIELD/I2S0-DOUT2/I2S0-DIN2/RGMII-TXD3/PE-EINT12 |
| 59           | N1         | GMAC_TXD2        | 3V3      | PE11/NCSI0-D7/UART1-RX/I2S0-DOUT3/I2S0-DIN3/JTAG-CK/RGMII-TXD2/PE-EINT11 |
| 60           | P3         | GMAC_INT         | 3V3      | PE10/NCSI0-D6/UART1-TX/PWM4/IR-RX/JTAG-DO/EPHY-25M/PE-EINT10 |
| 61           | P2         | GMAC_MDIO        | 3V3      | PE9/NCSI0-D5/UART1-CTS/PWM3/UART3-RX/JTAG-DI/MDIO/PE-EINT9   |
| 62           | R3         | GMAC_MDC         | 3V3      | PE8/NCSI0-D4/UART1-RTS/PWM2/UART3-TX/JTAG-MS/MDC/PE-EINT8    |
| 63           | R2         | GMAC_MCLK        | 3V3      | PE7/NCSI0-D3/UART5-RX/TWI3-SDA/SPDIF-OUT/D-JTAG-CK/R-JTAG-CK/RGMII-CLKIN/RMII-RXER/PE-EINT7 |
| 64           | R1         | GMAC_TXEN        | 3V3      | PE6/NCSI0-D2/UART5-TX/TWI3-SCK/SPDIF-IN/D-JTAG-DO/R-JTAG-DO/RGMII-TXCTRL/RMII-TXEN/PE-EINT6 |
| 65           | T3         | GMAC_TXD1        | 3V3      | PE5/NCSI0-D1/UART4-RX/TWI2-SDA/LEDC-DO/JTAG-DI/R-JTAG-DI/RGMII-TXD1/RMII-TXD1/PE-EINT5 |
| 66           | T2         | GMAC_TXD0        | 3V3      | PE4/NCSI0-D0/UART4-TX/TWI2-SCK/CLK-FANOUT2/D-JTAG-MS/R-JTAG-MS/RGMII-TXD0/RMII-TXD0/PE-EINT4 |
| 67           | U3         | GMAC_TXCLK       | 3V3      | PE3/NCSI0-MCLK/UART2-RX/TWI0-SDA/CLK-FANOUT1/UART0-RX/RGMII-TXCK/RMII-TXCK/PE-EINT3 |
| 68           | U2         | GMAC_RXD1        | 3V3      | PE2/NCSI0-PCLK/UART2-TX/TWI0-SCK/CLK-FANOUT0/UART0-TX/RGMII-RXD1/RMII-RXD1/PE-EINT2 |
| 69           | U1         | GMAC_RXD0        | 3V3      | PE1/NCSI0-VSYNC/UART2-CTS/TWI1-SDA/LCD0-VSYNC/RGMII-RXD0/RMII-RXD0/PE-EINT1 |
| 70           | V1         | GMAC_RXEN        | 3V3      | PE0/NCSI0-HSYNC/UART2-RTS/TWI1-SCK/LCD0-HSYNC/RGMII-RXCTRL/RMII-CRS-DV/PE-EINT0 |
| 71           | Y18        | PD22             | 3V3      | PD22/SPDIF-OUT/IR-RX/UART1-RX/PWM7/PD-EINT22                 |
| 72           | V18        | LCD-VSYNC        | 3V3      | PD21/LCD0-VSYNC/TWI2-SDA/UART1-TX/PWM5/PD-EINT21             |
| 73           | W18        | LCD-HSYNC        | 3V3      | PD20/LCD0-HSYNC/TWI2-SCK/DMIC-CLK/PWM4/PD-EINT20             |
| 74           | \          | GND              |          |                                                              |
| 75           | W19        | LCD-DATA2        | 3V3      | PD0/LCD0-D2/LVDS0-V0P/DSI-D0P/TWI0-SCK/PD-EINT0              |
| 76           | V20        | LCD-DATA3        | 3V3      | PD1/LCD0-D3/LVDS0-V0N/DSI-D0N/UART2-TX/PD-EINT1              |
| 77           | V19        | LCD-DATA4        | 3V3      | PD2/LCD0-D4/LVDS0-V1P/DSI-D1P/UART2-RX/PD-EINT2              |
| 78           | U20        | LCD-DATA5        | 3V3      | PD3/LCD0-D5/LVDS0-V1N/DSI-D1N/UART2-RTS/PD-EINT3             |
| 79           | U19        | LCD-DATA6        | 3V3      | PD4/LCD0-D6/LVDS0-V2P/DSI-CKP/UART2-CTS/PD-EINT4             |
| 80           | U18        | LCD-DATA7        | 3V3      | PD5/LCD0-D7/LVDS0-V2N/DSI-CKN/UART5-TX/PD-EINT5              |
| 81           | T19        | LCD-DATA10       | 3V3      | PD6/LCD0-D10/LVDS0-CKP/DSI-D2P/UART5-RX/PD-EINT6             |
| 82           | T18        | LCD-DATA11       | 3V3      | PD7/LCD0-D11/LVDS0-CKN/DSI-D2N/UART4-TX/PD-EINT7             |
| 83           | R20        | LCD-DATA12       | 3V3      | PD8/LCD0-D12/LVDS0-V3P/DSI-D3P/UART4-RX/PD-EINT8             |
| 84           | R19        | LCD-DATA13       | 3V3      | PD9/LCD0-D13/LVDS0-V3N/DSI-D3N/PWM6/PD-EINT9                 |
| 85           | \          | GND              |          |                                                              |
| 86           | T17        | LCD-DATA14       | 3V3      | PD10/LCD0-D14/LVDS1-V0P/SPI1-CS/DBI-CSX/UART3-TX/PD-EINT10   |
| 87           | R17        | LCD-DATA15       | 3V3      | PD11/LCD0-D15/LVDS1-V0N/SPI1-CLK/DBI-SCLK/UART3-RX/PD-EINT11 |
| 88           | P19        | LCD-DATA18       | 3V3      | PD12/LCD0-D18/LVDS1-V1P/SPI1-MOSI/DBI-SDO/TWI0-SDA/PD-EINT12 |
| 89           | P18        | LCD-DATA19       | 3V3      | PD13/LCD0-D19/LVDS1-V1N/SPI1-MISO/DBI-SDI/DBI-TE/DBI-DCX/UART3-RTS/PD-EINT13 |
| 90           | N17        | LCD-DATA20       | 3V3      | PD14/LCD0-D20/LVDS1-V2P/SPI1-HOLD/DBI-DCX/DBI-WRX/UART3-CTS/PD-EINT14 |
| 91           | N16        | LCD-DATA21       | 3V3      | PD15/LCD0-D21/LVDS1-V2N/SPI1-WP/DBI-TE/IR-RX/PD-EINT15       |
| 92           | N20        | LCD-DATA22       | 3V3      | PD16/LCD0-D22/LVDS1-CKP/DMIC-DATA3/PWM0/PD-EINT16            |
| 93           | N19        | LCD-DATA23       | 3V3      | PD17/LCD0-D23/LVDS1-CKN/DMIC-DATA2/PWM1/PD-EINT17            |
| 94           | M19        | LCD-CLK          | 3V3      | PD18/LCD0-CLK/LVDS1-V3P/DMIC-DATA1/PWM2/PD-EINT18            |
| 95           | M18        | LCD-DE           | 3V3      | PD19/LCD0-DE/LVDS1-V3N/DMIC-DATA0/PWM3/PD-EINT19             |
| 96           | \          | GND              |          |                                                              |
| 97           | M16        | CAN0_TX          | 3V3      | PB2/LCD0-D0/I2S2-DOUT2/TWI0-SDA/I2S2-DIN2/LCD0-D18/UART4-TX/CAN0-TX0/PB-EINT2 |
| 98           | M15        | CAN0_RX          | 3V3      | PB3/LCD0-D1/I2S2-DOUT1/TWI0-SCK/I2S2-DIN0/LCD0-D19/UART4-RX/CAN0-RX0/PB-EINT3 |
| 99           | K16        | CAN1_TX          | 3V3      | PB4/LCD0-D8/I2S2-DOUT0/TWI1-SCK/I2S2-DIN1/LCD0-D20/UART5-TX/CAN1-TX0/PB-EINT4 |
| 100          | K15        | CAN1_RX          | 3V3      | PB5/LCD0-D9/I2S2-BCLK/TWI1-SDA/PWM0/LCD0-D21/UART5-RX/CAN1-RX0/PB-EINT5 |
| 101          | K17        | UART3_TX         | 3V3      | PB6/LCD0-D16/I2S2-LRCK/TWI3-SCK/PWM1/LCD0-D22/UART3-TX/CPUBIST0/PB-EINT6 |
| 102          | J15        | UART3_RX         | 3V3      | PB7/LCD0-D17/I2S2-MCLK/TWI3-SDA/IR-RX/LCD0-D23/UART3-RX/CPUBIST1/PB-EINT7 |
| 103          | \          | GND              |          |                                                              |
| 104          | J16        | I2C2-SCL         | 3V3      | PB0/PWM3/IR-TX/TWI2-SCK/SPI1-WP/DBI-TE/UART0-TX/UART2-TX/SPDIF-OUT/PB-EINT0 |
| 105          | J17        | I2C2-SDA         | 3V3      | PB1/PWM4/I2S2-DOUT3/TWI2-SDA/I2S2-DIN3/UART0-RX/UART2-RX/IR-RX/PB-EINT1 |
| 106          | G15        | SPI1-HOLD        | 3V3      | PB8/DMIC-DATA3/PWM5/TWI2-SCK/SPI1-HOLD/DBI-DCX/DBI-WRX/UART0-TX/UART1-TX/PB-EINT8 |
| 107          | G16        | SPI1-MISO        | 3V3      | PB9/DMIC-DATA2/PWM6/TWI2-SDA/SPI1-MISO/DBI-SDI/DBI-TE/DBI-DCX/UART0-RX/UART1-RX/PB-EINT9 |
| 108          | F17        | SPI1-MOSI        | 3V3      | PB10/DMIC-DATA1/PWM7/TWI0-SCK/SPI1-MOSI/DBI-SDO/CLK-FANOUT0/UART1-RTS/PB-EINT10 |
| 109          | F15        | SPI1-CLK         | 3V3      | PB11/DMIC-DATA0/PWM2/TWI0-SDA/SPI1-CLK/DBI-SCLK/CLK-FANOUT1/UART1-CTS/PB-EINT11 |
| 110          | F16        | SPI1-CS          | 3V3      | PB12/DMIC-CLK/PWM0/SPDIF-IN/SPI1-CS/DBI-CSX/CLK-FANOUT2/IR-RX/PB-EINT12 |
| 111          | C12        | TP-X1            |          |                                                              |
| 112          | A11        | TP-X2            |          |                                                              |
| 113          | B11        | TP-Y1            |          |                                                              |
| 114          | C11        | TP-Y2            |          |                                                              |
| 115          | E19        | TVOUT            |          |                                                              |
| 116          | B9         | TVIN0            |          |                                                              |
| 117          | C9         | TVIN1            |          |                                                              |
| 118          | \          | GND              |          |                                                              |
| 119          | B8         | USB1_N           |          |                                                              |
| 120          | A8         | USB1_P           |          |                                                              |
| 121          | C7         | USB0_N           |          |                                                              |
| 122          | B7         | USB0_P           |          |                                                              |
| 123          | \          | GND              |          |                                                              |
| 124          | B12        | LRADC            |          |                                                              |
| 125          | C13        | GPADC0           |          |                                                              |
| 126          | B13        | GPADC1           |          |                                                              |
| 127          | \          | GND              |          |                                                              |
| 128          | B17        | FMINL            |          |                                                              |
| 129          | C17        | FMINR            |          |                                                              |
| 130          | B16        | LINEINL          |          |                                                              |
| 131          | C16        | LINEINR          |          |                                                              |
| 132          | B15        | LINEOUTL_P       |          |                                                              |
| 133          | C15        | LINEOUTL_N       |          |                                                              |
| 134          | B14        | LINEOUTR_P       |          |                                                              |
| 135          | C14        | LINEOUTR_N       |          |                                                              |
| 136          | E16        | MBIAS            |          |                                                              |
| 137          | D20        | MICIN1_P         |          |                                                              |
| 138          | D19        | MICIN1_N         |          |                                                              |
| 139          | E15        | MICIN2_P         |          |                                                              |
| 140          | D15        | MICIN2_N         |          |                                                              |

