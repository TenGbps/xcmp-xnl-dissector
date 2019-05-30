# Motorola XCMP/XNL Dissector for Wireshark

Simplifies analyzing the MOTOTRBO Extended Command and Management Protocol (XCMP) and its network layer (XNL).


## Getting Started

 * Copy `*.lua` to the Wireshark folder
 * Add on the end of init.lua 
 ```
 dofile(DATA_DIR.."xnl.lua")
 dofile(DATA_DIR.."xcmp.lua")
 ```
 * Happy analyzing!


## Disclaimer

This project is not produced, endorsed, or affiliated with Motorola Solutions.
