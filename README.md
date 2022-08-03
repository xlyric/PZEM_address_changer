/*
Original code from 2021 Jakub Mandula
upgraded by 2022 Cyril Poissonnier

PZEM modules address changer .
================================================================

Each PZEM modules has two addresses. A default general address (0xF8),
which every module will listen on by default. And a custom address.

The custom address can be used if multiple PZEM modules are to be used
on a single ModBUS.

This script will use the general address in order to set the custom 
address of the connected PZEM module.

Therefore make sure only one PZEM module is connected at a time! 
Otherwise all connected modules will receive the same custom address.

the address can be change by typing new address in serial monitor. 

you can after use multi pzem on the same board for your domotic project 
