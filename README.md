# ESP32-S3_Dev_Board
This development board is based on ESP32-S3 chipset which is aimed to solve the problem having to carry multiple tools to debug and capture data on RS485 and CAN bus.

<strong> Front view (Rendering)</strong>
![plot](./Assets/front.png)


<strong> Back view (Rendering)</strong>
![plot](./Assets/back.png)

The board is capable of operating in multiple modes.
1. With Firmware support (Still in making):
    1. CAN bus Decoder
    2. RS485 Decoder 

2. Standalone Hardware support:
    1. RS485 to USB converter
    2. USB to UART converter

3. Normal Development baord for ESP32-S3 Development.

<strong>The Board supports a wide variety of features.</strong>

| Interface    | Controller | Driver/Component |
| -------- | ------- | ------- |
| UART | on-chip | serial port |
GPIO | on-chip | gpio |
PINMUX | on-chip | pinmux |
USB-JTAG | on-chip | hardware interface
SPI Master | on-chip | spi
TWAI/CAN controller | on-chip | can
ADC | on-chip | adc
Timers | on-chip | counter
Watchdog | on-chip | watchdog	
TRNG | on-chip | entropy
MCPWM | on-chip | pwm 
PCNT | on-chip | qdec
GDMA | on-chip | dma
LEDC | on-chip | pwm
CAN trasnceiver | on-board | can
RS485 transceiver | on-board | serial-port
UART-to-USB | on-board | Hardare based

<strong>Development enviroinment support </strong>
The board is designed keeping open-source support in mind.
The main motive is to provide support on multiple development environments to cater to different people ranging from begginers to professionls. 

The supported platforms are listed below

1. Arduino IDE
2. ESP-IDF
3. Zephyr-RTOS

The guide on getting started on each platform is still in making. Stay tuned for further updates. 

