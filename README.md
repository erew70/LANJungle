# LANJungle
A script to help you forward your LAN to the internet, allowing LAN play over the internet with your friends.

## Advantages ocer traditonal software like xlink kai

user friendly and easy to setup, compared to xlink kai

supports literally any console/pc that has wifi adapter (client and host must have wifi hardware)

any console used does not to be modded or hacked


## disadvantages

no emulator support, unless the emulator supports real true lan play (can connect to other real nearby consoles)

requires port forwarding for the host (script attempts to automate it)

client may need new hardware, this means that the client has to be able to connect to the host network and broadcast a hotspot for the console to connect to simultaneously

security issues, publicly sharing this means anybody can use YOUR ip, and possibly hijack any devices on your network

(share your config file with only people you trust)

both client and host requires a working interner connection that can connect to the internet

this script will most likely **only** suport linux


## how this works


HOST (with a vpn server the client can connect to) --> ROUTER/GATEWAY --> INTERNET

CLIENT --> INTERNET --> HOST VPN --> ROUTER/GATEWAY

then the client creates a hotspot that allows you to use the vpn on the console that tunnels all the way back to the host lan network, allowing lan play over the internet

