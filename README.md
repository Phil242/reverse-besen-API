# The project

The BESEN wallbox is one of the cheapest on the market. But it’s maybe the less supported one.      
The wallbox is only manageable by an application which is available for IOS and Android. it is buggier than a first-year student project.       
The goal of this project is to reverse engineer wallbox to understand the protocol that is being used between the wallbox and the phone application in order to create an opensource API.

Being able to automatise start, stop charging and changing max current will allow to be integrated into domestic automation systems. 
It will allow to implement nice features like curtailment (when domestic max power is limited) and/or photovoltaic production optimal usage.
For example allowing several charging modes (minimise grid usage, allow grid usage, max booost,...)
For the last two feature this would be done with the help of specialised software, like Home Assistant. 
See for example https://community.home-assistant.io/t/wallbox-pulsar-plus-integration/200339   

# Status

#### Finished:
- Understanding how the phone and the wallbox exchange data    
- Replay successfully a past charging command, with an old timestamp without modifying it        
- Stop charging command has been reversed engineered  
- CRC algorithm reversed, understood and implemented
- Analysed SAE J1772 max control pilot usage for max current

#### In Progress:
- Start charging command reserve on the go      
- Reversing the only available firmware for ARM board (unknown model)       

#### TODO:
- Understanding the Bluetooth pairing process (UDP ports numbering)     
- What did the phone application sends to China ? (yes it does!) 
- Trying to understand various broadcast packets
- Extract the current ESP32 firmware    

# Contact us!
Feel free to reach us, we need you!       
