# Serial DFU Host Application (By using C programming language)

This demo is to implement the DFU host application by using C code instead of using nRFutil.

It is based on the nRFUtil 3.5.0 protocol to port on corresponding C code.

* Secure DFU UART transport is supported.
* UART bit rate is 115200bps with 8-N-1 data format. RTS/CTS flow control is enabled. It is the same as nRF5 SDK DFU bootloader.
* The program takes the DFU package ZIP file generated by Python nrfutil.
* nrfutil v3.5.0 is referred to.

## Example Package

For the detail testing procedures, you can refer to the blog as

https://jimmywongbluetooth.wordpress.com/2019/03/06/serial-uart-dfu-on-nrf5-sdk-by-using-host-tool-instead-of-nrfutil-in-c-code-application/

## Requirement

Nordic nRF5 SDK 15.2
NRF52832 DK Board
nrfutil 3.5 / 4.0

To compile it, clone the repository in the \nRF5_SDK_15.2.0_9412b96\ folder. If you download the zip, place each of the project folders of this repository into the \nRF5_SDK_15.2.0_9412b96\ folder.

This example is tested and worked with Nordic SDK 15.2.

