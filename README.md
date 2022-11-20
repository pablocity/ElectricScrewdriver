# Electric screwdriver project

## Parts

- Li-ion battery 3.7V
- Motor driver (any with low voltage drop so avoid L293D) good examples are DRV8833 or TB6612 
    (https://botland.store/drivers-for-dc-motors/6934-dfrobot-hr8833-two-channel-driver-for-dc-10v15a-motors-5904422361402.html)
- DC motor with at leas 0.150Nm of torque for example N20 motor 
    (https://botland.store/n20-micro-motors-mp-series-medium-power/12593-micro-motor-n20-bt34-298-1-45rpm-9v-5904422319724.html)
- Pushbuttons
- Resistors (actually you should check your motor driver documentation beacuse some of them has already pull-down resistors on the input so it might be unnecessary to use another one)
- Li-ion battery charger module
    (https://botland.store/charger-modules-for-li-po-batteries/16979-tp4056-type-c-usb-5v-1a-lithium-battery-charger-module-board-5904422326708.html)
- Step-up converter
    (https://botland.store/converters-step-up/17202-step-up-votage-regulator-tps61023-adafruit-4654-5904422327095.html)
    (https://pl.aliexpress.com/item/4000289253353.html)


## Schematic

image.png

Fritzing file with schematic is placed in the repository (ElectricScrewdriverSchematic.fzz)