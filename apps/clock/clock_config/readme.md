[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# Clock configuration

This example application shows how to configure the clock system to run the device at maximum frequency. It also outputs a prescaled clock signal on a GPIO pin for measurement and verification.

## Description

Clock system generates and distributes the clock for the processor and peripherals. This example application shows how to use the clock manager to configure the device to run at the max possible speed. A prescaled clock signal is routed to GPIO pin to measure the frequency and accuracy of the internal device clock.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_d11) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/clock/clock_config/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_d11_xpro.X | MPLABX project for [SAM D11 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamd11-xpro) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| sam_d11_xpro.X | [SAM D11 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamd11-xpro)
|||

### Setting up [SAM D11 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamd11-xpro)

- Connect an oscilloscope to monitor the PORT pin PA09 (Pin 17 on the EXT1)
- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE
2. Observe a clock of 4 MHz (approx.) on the clock output pin
3. LED should be blinking continuosly

Refer to the following table for clock output pin and LED name for different boards:

| Board      | Clock output pin | LED Name |
| ---------- | ---------------- |--------- |
| [SAM D11 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamd11-xpro)    | PA09 (Pin 17 on the EXT1)  | LED0 |
||||