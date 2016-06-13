## Style for Seahub

## Deployment

##### 1/ clone this repo in seahub-data/custom/ folder (create custom)
##### 2/ create a symbolic link in latest/seahub/media by ln -s ../../../seahub-data/custom custom
##### 2/ edit /conf/seahub_setting.py in order to add this lines


    LOGO_PATH = 'custom/SeahubStyleWeaos/style/mylogo.png'
    LOGO_WIDTH = 50
    LOGO_HEIGHT = 32
    BRANDING_CSS = 'custom/SeahubStyleWeaos/style/custom.css'

## Screens

![01](https://github.com/weareopensource/SeahubStyleWeaos/blob/master/screens/01.png)
![02](https://github.com/weareopensource/SeahubStyleWeaos/blob/master/screens/02.png)

## Author
* Pierre Brisorgueil
