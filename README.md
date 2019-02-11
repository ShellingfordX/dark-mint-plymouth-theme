## Saber theme

*Saber theme* is a theme for Plymouth, the boot splash tool for Linux. 

[![Screenshot](https://i.imgur.com/XV5aJtF.png)](https://i.imgur.com/XV5aJtF.png)

## How to install the theme
From the terminal, run the install script:

    sudo ./install.sh

## How to uninstall the theme
From the terminal, run this command:

    sudo /usr/share/plymouth/themes/saber-plymouth/uninstall.sh

## How to preview the theme
After installing, you can preview the theme without having to reboot. Just run this command from the terminal:

    wget https://raw.githubusercontent.com/ShellingfordX/221BBakerStreet/master/Plymouth/preview.sh
    chmod +x ./preview.sh
    sudo ./preview.sh

It runs for 2 seconds by default. You can optionally specify the number of seconds to run the preview:

    sudo ./preview.sh 10

#### Note: previewing the theme requires *plymouth-x11*. To install the package:

    sudo apt-get install plymouth-x11


## Credit

Josep Sayol
    https://github.com/jsayol/dark-mint-plymouth-theme
amirovic
    https://www.deviantart.com/amirovic/art/Saber-Bootscreen-502496484
