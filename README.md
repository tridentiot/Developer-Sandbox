# Developer-Sandbox
This repository contains files that can be used by TridentIoT ElCap users to get a quick start on controllers, Zniffers, Radio CLI, and more.

ElCap Download: https://tridentiot.com/technology/software/

ESP-IDF Download: https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/windows-setup.html

Z-Way ESP Flasher Webtool: https://tridentiot.github.io/z-way-esp-web-tools/development/development.html

Z-Way Documentation: https://tridentiot.github.io/z-way-developer-documentation/#HOW_TO_BUILD_AND_RUN_Z-WAY_FOR_ESP32


Steps:
1. Flash THIN_GW_DKNCZ20_Shield_zwave_serial_api_controller_1.0_us_lr_debug_signed_combined.hex to a DKNCZ20 development board
2. Flash z-way-esp32-prod-xiao.zip through the Z-Way ESP Flasher Webtool
3. Disconnect from ESP Flasher Webtool and switch to the terminal mode in Z-Way ESP Flasher Webtool.
4. On connection, when you are prompted to interact with the Z-Way CLI, enter "W" to see Access Point information.
5. Join the listed network and go to http://localhost:8083/
6. Follow Z-Way documentation from here!
