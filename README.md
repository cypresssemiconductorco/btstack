# BTSTACK Library
BTSTACK is Cypress's Bluetooth Host Protocol Stack implementation. The stack is optimized to work with Cypress Bluetooth controllers.
The BTSTACK supports Bluetooth BR/EDR and BLE core protocols.
The stack is available as libraries built for CM3 and CM4 ARM (TM) cores using ARM, GCC and IAR tool-chains. Further there are two build variants of stack libraries, LE only and Dual-mode. Applications that need only the LE protocols can take advantage of reduced size of LE only library and build LE peripheral or central applications. Dual-mode library supports both LE and BR/EDER protocols.

BTSTACK library is used in conjuction with a porting layer such as the [one available for FreeRTOS on PSOC](https://github.com/cypresssemiconductorco/bluetooth-freertos) that sets up memory, threads and other OS constructs required by stack library. Porting layer also provides integration with a Bluetooth Controller.


## Features
Protocols supported include (but not limited to)
 - ATT/GATT
 - Secure Connections
 - Multi-Advertisements
 - LE 2M
 - LECOC
 - SDP
 - AVDT/AVRC
 - RFCOMM/SPP
Please note that some of these features depend on the BT controller as well.

## Additional Information

For BLE APIs, refer to the [BLE API reference manual](https://cypresssemiconductorco.github.io/btstack/ble/api_reference_manual/html/index.html).

For BLE and BR/EDR APIs, refer to the [DUAL MODE API reference manual](https://cypresssemiconductorco.github.io/btstack/dual_mode/api_reference_manual/html/index.html).

[Release Notes](https://github.com/cypresssemiconductorco/btstack/releases/tag/release-v2.0.0)
