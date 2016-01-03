# Botnana A2

#### An Industrial Ethernet and IoT Platform (工業以太網物聯網開發平台)

Botnana A2 is an industrial Ethernet development platform. Designed and developed by Mapacode Inc., targeting specifically towards industrial education and automation development. Mapacode Inc. uses it as for it’s own CNC products.

Botnana A2's a variation of BeagleBone Black, but with both Mii ports on the CPU supported instead one. It incorporates 2 sets of RJ45 connectors in order to fulfill the requirements of EtherCAT master/slave. It's 40-pin connector is compatible with Raspberry Pi Model B+ , another 30 pin connector provides 24V and analog inputs. Inbuilt basic essential industrial Ethernet and IoT (Internet of Things) software, well suited for R & D personnel or students to experiment on various innovative ideas in the era of industrial Ethernet and IoT.

針對工業教育以及工業自動化開發，由動程科技設計的工業以太網開發平台 BotBone，和樹莓派 Model B+ 的腳位相容，方便運用現在樹莓派子板。具有 2 組 RJ45， 內建基本工業以太網／工業物聯網軟體，方便研發人員或學生實驗各種工業以太網／物聯網的構想。

## Revisions (修改記錄及版本號碼)
* Revision 0.2.0
removed HDMI, for sample run 2

* Revision 0.1.0
    For sample run 1

## Specifications (規格)
### Processor
* AM3357 800MHz ARM Cortex A8
* 512MB DDR3L@400MHz RAM
* 4GB 8-bit eMMC on-board flash storage
* 1x microSD
* NEON floating-point accelerator
* 2x PRU 32-bit microcontrollers

### Software

#### As Master
* Debian Linux
* with Real-time extenstion (Xenomai)
* EtherCAT master
* M2M Server

#### As Slave
* TI SYS/BIOS
* support EtherCAT slave, Powerlink, Ethernet/IP, ProfiNET

### Connectivity
* USB 2.0 client for power and communication (USB0), microUSB
* USB 2.0 host (USB1), TYPE A socket
* 2x Ethernet 10/100MHz
* 40-pin connector comaptible with Raspberry Pi Model B+’s 40-pin connector
* Another 26-pin connector to supply daugtherboard with 12/24 volts power
* 2 x SPI, 3 x I2C, 2 x CAN, 4 x Timers, 2 x eQEP, PWMs, 2 x eCAP, 4 x UARTs, 7 Analog inputs, 29 GPIOs

### Power
* 5V through micro USB
* 5.5V-36V through 3.96 connector
