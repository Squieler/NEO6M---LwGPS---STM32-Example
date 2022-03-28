# LwGPS Implementation for Ublox-NEO6M on STM32F4
This is an example file for the LwGPS NMEA sentence parser library developed by Tilen MAJERLE: https://github.com/MaJerle/lwgps

This example configured for Ublox-NEO6M to gather the information: Time, latitude, longtitude, altitude and speed.

* For more information about library, check the documentation: https://docs.majerle.eu/projects/lwgps/en/latest/

## Example Usage
In the example project, USART1 peripheral configured as:
1. Baud rate: 9600 bits/s
2. DMA settings: USART1_RX, peripheral to memory, circular mode with high priority
3. NVIC settings: USART1 global interrupt enabled
The rest is default. If you encounter with any problems please check the example project.

USART2 peripheral is configured to transmit messages to a computer.
