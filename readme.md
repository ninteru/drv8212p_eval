# DRV8212P Evaluation Breakout Board

This board was created to evaluate the operation of the [TI DRV8212P](https://www.ti.com/product/DRV8212P) in driving common N20 geared DC motors.

Certain considerations are required dependent on the selected motor and sensing features. By default, the VM (V_motor) and VCC (V_io) are tied together via the bridged pad. This is for operation of the motor at the same voltage of the controller mcu. If independent nets are to be used, the bridge must be cut and VM and VCC must be independently provided via the input header pins. 

Additionally, DRV8212P provides load sensing capability via a sense resistor between the ICs ground and the board ground. The value of R_SENSE is dependent on the requirements of your application and is left to the user to calculate. 

## Calculating R_SENSE

## Schematic

## PCB Layout
