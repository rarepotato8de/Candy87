# Candy87: A universal TKL PCB 💙
The Candy87 Hotswap PCB was exclusively made for and in cooperation with [Candykeys](https://candykeys.com/) and designed to fit the Geonworks F1-8X V2 and other TKL keyboards. It supports many layout options and has awesome features such as a breakable USB-C port or indicator LED's!

![Candy87_Top_View](https://github.com/user-attachments/assets/232b2038-8ebe-4651-b32d-1656d3a3d183)

## Features
- H87/H88 Compatible
- ISO and/or ANSI Support (See supported layout notes!)
- Standard and Tsangan Bottom Row
- O-Ring Cutouts
- Breakable USB-C Port (Daughterboard can be used with JST)
- Indicator LED's for Caps- and Scrolllock
- RP2040 Chip
- Broken-out GPIO Pins
- Physical BOOT and RESET Button (for flashing)
- QMK/VIAL Support

## Firmware & Flashing
Both QMK and VIAL firmwares are available in the official repositories. The ready-to-use VIAL firmware can be found here.

To flash the PCB the first time, you just have to plug it into your computer via. USB-C or Daughterboard and then in your explorer there should appear a new drive medium called "RPI-RP2" or similar. Just drag&drop the .UF2 file onto the drive and the window should automatically close and the PCB will now be flashed and functional.
For flashing it another time, plug in the PCB and hold down the "BOOT" button on the backside of the PCB, press the "RESET" button two times and then release the "BOOT" button again. After that the "RPI-RP2" medium should appear.

## Supported layouts
![image](https://github.com/user-attachments/assets/a59127cd-568c-4c5f-873d-6724742b469c)

> [!IMPORTANT]
> Due to hotswap sockets interfering with both ANSI and ISO support, only one of these options can be used at a time.
> Candykeys version comes with ISO by default, but by resoldering two hotswap sockets it can be ANSI. See picture below (it's resoldered to ANSI)

![image](https://github.com/user-attachments/assets/c20ca5b5-92b3-47e5-9656-a8bfeb09d2cf)

## Breakable USB-C Port
> [!CAUTION]
> Be careful when removing/ breaking-off the USB-C port. It should be done with caution and pliers.
> It's recommended to place the PCB on a flat surface (e.g. a table), with the USB-C port "hanging" off the side and then wiggling up and down with your pliers until it breaks off.

> [!CAUTION]
> Please do this step outside or somewhere but inside.
> You should wear glasses and a mask to prevent any health risks from the FR4 dust.

https://github.com/user-attachments/assets/5fa9985e-4570-457c-9966-bd2f55c6e134

## Open Source
This project will be open sourced in the future!

## Infos about this project
The project came up in the beginning of 2024 when Geonworks announced another groupbuy for his popular keyboard, the F1-8X V2. It's being offered by multiple international vendors like Candykeys. For european fellas, Candykeys wanted to offer an ISO hotswap PCB. So we talked, made plans and finally build this awesome project together!
There was so much demand for it, people were super interested and excited for it and me too! So I'm super honored to be part of this and will look forward for further projects.

Big shoutout and thanks to @zitres 🍋🍋 and @candykeys 💙
