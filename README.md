# The project

The BESEN wallbox is one of the cheapest on the market. But it’s maybe the less supported one.
The wallbox is only manageable by an Android or iOS application. Witch is buggier than a first-year student project.
The goal of this project is to understand the protocol between the wallbox and the phone application to opensource the API.

# Status

#### Ok:
Understanding how the phone and the wallbox exchange data
Replay successfully of a past charging command, with an old timestamp without modify it
Stop charging command reversed

#### Progress:
Start charging command reserve on the go
CRC algorithm reversed and understood, but needs more checks
Reversing the only available firmware for ARM board (unknown model)

#### TODO:
Understanding the Bluetooth pairing process (UDP ports numbering)
What did the phone application sends to China ? (yes it does!)
Various broadcasted packet to finish to understand
Extract the current ESP32 firmware

# Contact us!
Feel free to reach us, we need you!
