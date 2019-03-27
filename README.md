# OV5640_PMOD
this section considers only the OV5640 Configuration using PMOD as GPIO with SCCB

## AXI GPIO SETTING

### axi_gpio_1 : hardware reset and pwdn

1. axi_gpio_1 channel 1: used as the OV5640_PWDN, default value --- 1
2. axi_gpio_1 channel 2: used as the OV5640_RSTB, default value --- 0

### axi_gpio_2: sccb_siod and sccb_sioc
dont care the default value, dont care which channel represent which signal

