# Full technical documentation

This repository contains the complete technical documentation for the project.
Each project component has a dedicated file, written in [Markdown](https://guides.github.com/features/mastering-markdown/).

## Slave bootloader

The bootloader is used to start the microcontroller firmware and also offers the option of updating the firmware via I2C communication.
It has been developed using the [Mbed](https://os.mbed.com/) framework.

Link to the full documentation: [slave-bootloader.md](slave-bootloader.md)

## Slave basic firmware

This is the basic firmware that allows you to use all the features of the ecosystem.
To develop more specific firmware, it is recommended that you create a fork.
This firmware is also developed using the [Mbed](https://os.mbed.com/) framework.

Link to the full documentation: [slave-basic-firmware.md](slave-basic-firmware.md)

## Master tools

This section contains the tools for the I2C master.
They allow you to communicate with the I2C slaves while taking full advantage of the ecosystem's features.
These tools are written in Python to be compatible with as many platforms as possible.

Link to the full documentation: [master-tools.md](master-tools.md)
