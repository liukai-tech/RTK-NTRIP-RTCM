# Portable Real Time Kinematic with NTRIP
Contains program to Send RTCM3 data to Hosted NTRIP server and fetch NTRIP data and display on another rover. Real time kinematic supported base and rover (Ublox-M8P) GPS units are required.

[![ublox](https://www.u-blox.com/sites/default/files/styles/product_full/public/products/NEO-M8P.png?itok=_Bhf3FzS)](https://www.u-blox.com/en/product/neo-m8p-series)

Real time kinematic need RTCM3 supported GNNS recivers. Host a NTRIP server and assign a Dynamic DNS server to the server. [rtcm3TCP.py](https://github.com/Archfx/RTK-NTRIP-RTCM/blob/master/rtcm3TCP.py) and [rtcm3UDP.py](https://github.com/Archfx/RTK-NTRIP-RTCM/blob/master/rtcm3UDP.py) can be used to send the base station data to the NTRIP server. [Ntrip_Display.py](https://github.com/Archfx/RTK-NTRIP-RTCM/blob/master/Ntrip_Display.py)	and [ntrip.py](https://github.com/Archfx/RTK-NTRIP-RTCM/blob/master/ntrip.py) can be used to recive at the rover side.
