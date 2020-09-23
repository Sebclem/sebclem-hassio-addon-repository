# Hass.io Add-ons: Nextcloud Backup

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

[![Community Forum][forum-shield]][forum]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

Hass.io snapshot backup to Nextcloud

## About

Easily backup your Hass.io snapshots to Nextcloud.
Auto backup can be configure via the Home Assistant web interface.
### Features
- Auto Backup : Configure this add-on to automaticaly backup your HassIO instance.
- Auto Clean : You can specify the maximum number of local snapshots and (__ONLY__) auto backup snapshots.
- ~~Restore backups.~~ (Coming Soon)
> __Info:__
> Auto Clean is executed after every upload and every day at 00h30


## NextCloud config

First, you need to configure all your Nextcloud information.

To do this:
1. Open the add-on Web UI
1. Open NextCloud config menu (Top right gear, and Nexcloud)
1. If your NextCloud instance use `HTTPS`, enable the `SSL` lever
1. Enter the `hostname` of the NextCloud instance. You can specify a custom port by adding `:[port]` at the end of the hostname (`exemple.com:8080`)
1. Now enter the Nextcloud username that you want this addon to use.
1. For password, we highly recommend using an `App Password`.

    >To generate an `App Password`, go into your personal settings in the Nextcloud Security page. You can generate one via the `Devices & sessions` section. Simply enter a name and hit `Create new app password`

[Click here for the full documentation][docs]

![screenshot][image]

[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/seb6596
[docs]: https://github.com/Sebclem/hassio-nextcloud-backup/blob/master/README.md
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-beta-red.svg
[release-shield]: https://img.shields.io/badge/version-v0.9.1-blue.svg
[release]:  https://img.shields.io/badge/version-v0.9.1-blue.svg
[image]: https://github.com/Sebclem/hassio-nextcloud-backup/raw/master/images/screenshot.png
