# Ultrasonic Follow Carrier Transmitter PCB

#### 介绍
本项目为2021-2022学年第二学期电气工程学院2020级卓越班嵌入式系统与智能设计课程设计：超声波跟随载物平台之超声发送端PCB。<br>
根据设计，利用成品升压模块将```DC5V```供电抬升至```DC20V```左右，作为传感器的驱动电压；将输入的```Din```信号接入有```NMOS管```构成的非门电路产生```-Din```信号，并利用这两各信号分时导通单相全桥逆变电路，使```DC20V```逆变为```AC Vpp=40V f=fin```，而本设计中```fin=40kHz```。

#### 本项目其他仓库传送门
| Transmitter for Arduino UNO | Transmitter PCB | Receiver for Raspberry Pi | Receiver for STM32F103 | Receiver PCB |
| ---- | ---- | ---- | ---- | ---- |
| [Github](https://github.com/TantalumKevin/UltrasonicFollowCarrierTransmitter-for-ArduinoUNO) | [Github](https://github.com/TantalumKevin/UltrasonicFollowCarrierTransmitter-PCB) | [Github](https://github.com/TantalumKevin/UltrasonicFollowCarrierReceiver-for-RaspberryPi)  | [Github](https://github.com/TantalumKevin/UltrasonicFollowCarrierReceiver-for-STM32F103) | [Github](https://github.com/TantalumKevin/UltrasonicFollowCarrierReceiver-PCB) |
| [Gitee](https://gitee.com/kevin_ud/ultrasonic-follow-carrier-transmitter-for-arduino-uno)  | [Gitee](https://gitee.com/kevin_ud/ultrasonic-follow-carrier-transmitter-pcb) | [Gitee](https://gitee.com/kevin_ud/ultrasonic-follow-carrier)  | [Gitee](https://gitee.com/kevin_ud/ultrasonic-follow-carrier-receiver-for-stm32-f103) | [Gitee](https://gitee.com/kevin_ud/ultrasonic-follow-carrier-receiver-pcb) |