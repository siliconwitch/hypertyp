![Hypertyp Logo](images/logo.png)

![Image of the keyboard](images/07-finished-keyboard.jpg)

# A DIY Bluetooth Split Mechanical Keyboard

### Contents
- [Lets build it](#lets-build-it)
- [Firmware (ZMK config)](#firmware-zmk-config)
- [License](#license)


## Lets build it

You will need the following materials:

- 

## Firmware (ZMK config)

The following files/directories are related to the ZMK keyboard configuration:

- `config/`
- `zephyr/`
- `build.yaml`

For details on how the firmware is built, check out the documentation [here](https://zmk.dev/docs/development/hardware-integration/new-shield). This [video](https://youtu.be/7UXsD7nSfDY?si=tjk9EybX-g2Ae1Hp&t=1012) was also helpful.

Whenever changes to this repo are pushed, a github actions script will regenerate the firmware files. Download the build artifacts from the GitHub Actions tab, and copy them to the keyboards using a USB cable. They simply show up as external drives when plugged into a computer.

Once uploaded, the keyboard will reset and should be now running the ZMK firmware. In order to re-upload a new `.uf2` file. Enable the bootloader again by **double-clicking** the reset button. 

## Pairing

To pair the keyboard and connect it to your computer. Click the reset button on both halves at the same time, and check your Bluetooth settings. The keyboard should show up and be ready to use.

## License

