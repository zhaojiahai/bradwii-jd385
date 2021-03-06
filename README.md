Bradwii for JXD JD385, WLToys V202, Hubsan H107L and clones
=======

This is a port of bradwii to another ARM architecture, Nuvoton Mini51 which is represented
by commercial microhelis WL-Toys V202, V252, and JXD JD-385. For hardware description
details see https://github.com/hackocopter/JD385_Documentation .

Briefly, it uses MINI54ZAN ARM MCU with 16KB ROM and 2KB RAM, combined gyro/accelerometer
InvenSense MPU-6050, and nRF24L01+ clone Beken BK2423.

Hopefully it also will allow us to port it to similar ARM platform, Nuvoton M051,
which is represented by HiSky HMX120 (former FF120) and its rebadge HobbyKing Q-BOT micro.

It uses M058ZBN ARM MCU with 32KB ROM and 4KB RAM, gyro InvenSense MPU-3050, supposedly
accelerometer Freescale MMA8452Q (maybe ST LIS3DH), and nRF24L01 clone Si24R1.

Datasheets for HMX120 are at http://www.rcgroups.com/forums/showthread.php?t=1826018&page=51#post24710038

Credits
======

 * Bradwii was originally coded by Brad Quick for AVR: https://github.com/bradquick/bradwii
 * Trollcop forked and ported to ARM STM32, untested: https://github.com/trollcop/bradwii
 * The Mini54ZAN ARM port to V202/JD385 was done by Victor: https://github.com/victzh/bradwii
 * The Hubsan X4 H107L port was done by Goebish: https://github.com/goebish/bradwii-X4
