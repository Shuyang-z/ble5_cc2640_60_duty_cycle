# ble5_cc2640_60_duty_cycle

To generate 60% duty cycle for fixed frequency test

Use HCI_EXT_EnhancedModemTestTxCmd() and HCI_EXT_EndModemTestCmd() with delay after register ICall

The delay parameter is manually tuned

Based on simplelink_cc2640r2_sdk_4_20_00_04 BLE5-stack simple_peripheral

Tested result as follow

![Test result](https://github.com/Shuyang-z/ble5_cc2640_60_duty_cycle/raw/main/Test%20Result.jpg)
