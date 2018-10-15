[![Blog](https://badges.weareopensource.me/badge/Read-On%20our%20Blog-1abc9c.svg?style=flat-square)](https://weareopensource.me) [![Slack](https://badges.weareopensource.me/badge/Chat-On%20Slack-d0355b.svg?style=flat-square)](mailto:weareopensource.me@gmail.com?subject=Join%20Slack&body=Hi,%20I%20found%20your%20community%20We%20Are%20Open%20Source.%20I%20would%20be%20interested%20to%20join%20the%20Slack%20to%20share%20and%20discuss,%20Thanks) [![Mail](https://badges.weareopensource.me/badge/Contact-By%20Mail-3498db.svg?style=flat-square)](mailto:weareopensource.me@gmail.com?subject=Contact)

[![Packagist](https://badges.weareopensource.me/packagist/l/doctrine/orm.svg?style=flat-square)](/LICENSE.md)


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


[![Help](https://badges.weareopensource.me/badge/Help-On%20Patreon-052d49.svg?style=flat-square)](https://www.patreon.com/pbrisorgueil) [![Cofee](https://badges.weareopensource.me/badge/Buy-Me%20a%20Coffee-FF813F.svg?style=flat-square)](https://www.buymeacoffee.com/JrSa9tZGO)


[![Youtube](https://badges.weareopensource.me/badge/Watch-me%20on%20Youtube-e74c3c.svg?style=flat-square)](https://www.youtube.com/channel/UCIIjHtrZL5-rFFupn7c3OtA) [![Twitter](https://badges.weareopensource.me/badge/Follow-me%20on%20Twitter-3498db.svg?style=flat-square)](https://www.youtube.com/channel/UCIIjHtrZL5-rFFupn7c3OtA) 
