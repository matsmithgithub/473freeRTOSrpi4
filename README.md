# 473freeRTOS
This is a simple single task example for EECS473.
EECS473 is an embedded systems class that uses the RPI4 running free RTOS to control a simple 2 wheel robot.
This is a starting example running one task every 1ms to toggle GPIO pin 21.
See the main.c in the RP4drivers/application/src directory.
The freeRTOSrpi4 port was developed by Timida at https://github.com/TImada/raspi4_freertos.
The GPIO and interrupt libraries are taken from Francisco Marques at https://github.com/D3boker1/Neneco-FreeRTOS-On-RPI4B.
If you want instructions on how to compile this example see the lab draft at https://docs.google.com/document/d/10oXdHwRclKeVJgA8NU2OM0aE9q8v3xgw/edit?usp=sharing&ouid=106568666511841334504&rtpof=true&sd=true
