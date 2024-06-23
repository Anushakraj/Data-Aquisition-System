he project focuses on the implementation of various protocols such as UART, SPI, and I2C and A/D Converters to show various parameters of data collected from sensors onto a UART Terminal. The data acquisition system is built using the ARM-7 Based LPC2129 Microcontroller. The data is acquired from the microcontroller's onboard sensors using ADC and also from off-board sensors using external ADC through SPI protocol, and shows the data every second including the time of data acquisition using a RTC interfaced through I2C protocol, and all the data is displayed in the PC monitor through UART Serial terminal. The sensors used include the onboard temperature and potentiometer (used as a simulation for pressure) on the Rhydolabz LPC2129 Microcontroller development board, DS1307 RTC interfaced with I2C for printing the time of data acquisition, and the MCP3204 External ADC to connect LDR interfaced through SPI.
