# Requirements for Implementing wiper control system

**1. Packages Needed**

The below tools and packages are needed to work with STM32 Controllers with Qemu Support

Installable

- GNU Toolchain
- STM Cube IDE
- Downloadable
- Xpack Packages
- Windows Build Tools
- Open OCD
- Qemu
Make sure you download all the above packages and save it in an appropriate directory, by default it would be saved in Download directory

**2. Package Installation**

Assuming you have downloaded all the required packages mentioned in the previous page, its time to install them in to the host system, it is recommended to follow the below given order to have an easy and smooth setup

- Install GNU Toolchain
- Double click on gcc-arm-none-eabi executable and follow the installer instructions
- Keep all the options default
- Make sure to Tick the Set to PATH variable option
- Extract xpack Packages
- Create a directory named "xpack" in C drive
- Move all 3 (Windows Build Tools, Open OCD and Qemu packages) into the "xpack" directory
- Unzip all 3 zip files
