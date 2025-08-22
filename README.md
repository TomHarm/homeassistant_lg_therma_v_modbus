## Description
This package is for connecting and controlling an LG Therma V heat pump with Homeassistant via Modbus RTU.  

You will find all information [here](https://github.com/basti242/homeassistant_lg_therma_v_modbus/wiki).
 
This Repo is a fork of Basti242 who should gain the main credits for his amazing work.
As User of the Waveshare ETH RS485 brige, I want a more stable system, so I made the ETH to a MQTT client, which pushes the data from the LG to a MQTT broker, writing back to the ETH is also possible, so you´re able to get set your heat pump to the right settings.
Currently the modbus is read each second, it looks like the number of registers is exhausted, so adding other registers may lead to an unstable behaviour. 

I will add some insights how to setup the waveshare in the waveshare folder later on.

