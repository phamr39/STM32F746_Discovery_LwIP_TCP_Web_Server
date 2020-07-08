# STM32F76_Discovery_iwIP_TCP_Web_Server
This repo has features below:
-Create a demo web server (DCHP Server)
-Create a TCP Server.
-If the data is sent from one TCP client (like PC,..), STM32F7 will send them back and display it into the screen.
------------------------------------------------------------------------------------------
To use this code, please follow these steps:
1, Get full libraries and examples, templates:
- Clone this repo: https://github.com/STMicroelectronics/STM32CubeF7 and follow their setup guide.
=> This repo is the official source code for this line of microcontroller, provided by ST.
2, Go to ~\Projects\STM32746G-Discovery\Applications\LwIP\LwIP_HTTP_Server_Netconn_RTOS
and replace Src and Inc folders. 
3, Launch Project.uvprojx at MDK-ARM file to open the Keil C Project
------------------------------------------------------------------------------------------
More Information:
DevKit: STM32F746NGH6U Discovery
Keil C version 5.31
Contact: hieu.phamnt39@gmail.com
