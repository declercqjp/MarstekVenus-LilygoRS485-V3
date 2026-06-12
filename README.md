# MarstekVenus-LilygoRS485-V3
Marstek Venus-E V3 Modbus controls on Lilygo RS485 ESP32
THIS CONFIG IS ONLY FOR THE LILYGO T-CAN485, ITS NOT TESTET ON ANY OTHER DEVICE
Original V2 from: https://github.com/Superduper1969/MarstekVenus-LilygoRS485
added advanced sdkconfig_options from: https://github.com/whyisthisbroken/marstek-lilygo-rs485?hl=nl-NL 
V3 addings from: https://github.com/fonske/MarstekVenus-LilygoRS485
# The rest is added by JP :-)
rearranged sorting_groups in webserver
combined V2 (Superduper1969) with V3 (Fonske)
Due to limitations in V3: the Marstek RS485 control mode can only be disabled via a script on the web server --- Therefore, you
             see the original control only as info --- When you press the button, it takes some seconds for the script to run
             --- You can still see and use the control in Home Assistant and use it
            normally with your Automations. !!!
Added group: RS485 Control only for use in HA
