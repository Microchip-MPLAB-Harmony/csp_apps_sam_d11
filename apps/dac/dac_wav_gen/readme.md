[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# DAC waveform generation

This example application shows how to use the DAC to generate a 1 KHz Sine or Sawtooth wave with a lookup table.

## Description

This example application shows how to use the DAC Peripheral library to generate a 1 KHz Sine or Sawtooth wave with lookup table. DAC starts conversion on a trigger from a timer period interrupt configured to occur at every 10 microseconds. In this application, the number of the DAC samples in a lookup table is 100.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_sam_d11) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/dac/dac_wav_gen/firmware** .

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

- Connect an oscilloscope to monitor DAC pin PA02 (Pin 3 of the EXT1 header)
- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE
2. Observe a sine wave of 1 KHz frequency on DAC output pins
3. Press switch to toggle the waveform shape from sine wave to sawtooth wave and back
4. Refer to the below table for dac output pin and switch details:

| Board      | DAC output pins | Switch Name |
| ----------------- |-----------|-------------|
| [SAM D11 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamd11-xpro) | PA02 (Pin 3 of the EXT1 header) | SW0 |
||||