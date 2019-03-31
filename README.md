# OV5640_PMOD
this section considers only the OV5640 Configuration using PMOD as GPIO with SCCB

## 1 AXI GPIO SETTING
the *gpio_tri* value 0 represent that this port is used as output
the *gpio_tri* value 1 represent that this port is used as input

### 1.1 axi_gpio_1 : hardware reset and pwdn

1. axi_gpio_1 channel 1: used as the OV5640_PWDN, default value --- 1
2. axi_gpio_1 channel 2: used as the OV5640_RSTB, default value --- 0

### 1.2 axi_gpio_0: sccb_siod and sccb_sioc
dont care the default value, dont care which channel represent which signal

