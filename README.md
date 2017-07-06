# wifichecker - checks ip connectivity over wifi
A bash script checks the ip connectivity over wifi every second.  Using ip and iwconfig commands, displays SSID, wifi channel, AP mac, Signal level and RoundTrip time to the guessed default gateway.

# Example 
output when switching SSID Acme to Anothercme:
```
"Acme" 5.18 GHz 9C:5D:12:EC:03:66 Link Quality=56/70 Signal level=-54 dBm 10.23.255.15/16 time=1.29 6 Mb/s 15 dBm   
"Acme" 5.18 GHz 9C:5D:12:EC:03:66 Link Quality=56/70 Signal level=-54 dBm 10.23.255.15/16 time=3.81 6 Mb/s 15 dBm   
"Acme" 5.18 GHz 9C:5D:12:EC:03:66 Link Quality=56/70 Signal level=-54 dBm 10.23.255.15/16 time=4.56 6 Mb/s 15 dBm   
"Acme" 5.18 GHz 9C:5D:12:EC:03:66 Link Quality=56/70 Signal level=-54 dBm 10.23.255.15/16 time=1.28 6 Mb/s 15 dBm   
off/any******
off/any******
off/any******
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=44/70 Signal level=-66 dBm ******
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=45/70 Signal level=-65 dBm ******
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=45/70 Signal level=-65 dBm ******
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=41/70 Signal level=-69 dBm ******
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=46/70 Signal level=-64 dBm 10.37.3.171/16 time=2.99 6 Mb/s 15 dBm   
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=46/70 Signal level=-64 dBm 10.37.3.171/16 time=3.13 6 Mb/s 15 dBm   
"Anothercme" 5.22 GHz 9C:5D:12:1E:5E:25 Link Quality=45/70 Signal level=-65 dBm 10.37.3.171/16 time=3.74 6 Mb/s 15 dBm  
```
# Todo
- bring ESSID mac address to the base value for easier recognising the AP on the wifi admin tool.
