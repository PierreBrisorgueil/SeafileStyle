## Weaos Style for Seahub

## Deployment

###### 1/ clone this repo in 'seahub-data/custom' folder (create custom folder)

    cd
    cd seahub-data
    mkdir custom
    sudo git clone https://github.com/weareopensource/SeahubStyleWeaos.git

###### 2/ create a symbolic link

    cd
    cd /seafile-server-latest/seahub/media
    ln -s ../../../seahub-data/custom custom

###### 2/ edit /conf/seahub_setting.py in order to add this lines

    LOGO_PATH = 'custom/SeahubStyleWeaos/style/mylogo.png'
    LOGO_WIDTH = 50
    LOGO_HEIGHT = 32
    BRANDING_CSS = 'custom/SeahubStyleWeaos/style/custom.css'

## Screen

![screen](https://raw.githubusercontent.com/weareopensource/SeafileStyle/master/screen.png)

## Author
* Pierre Brisorgueil
