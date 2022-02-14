# V0.16.7 & V0.16.8

## 🔨 Changes

- :hammer: Add "Create Backup Timeout" in addon settings #111 [`f7177db`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/f7177dbd70d057b51fdcf14d399e462e09878806) 

## ⬆️ Dependency updates

- :arrow_up: Bump @fortawesome/fontawesome-free [`109`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/109) `dependabot[bot]`
- :arrow_up: Bump follow-redirects [`112`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/112) `dependabot[bot]`
- :arrow_up: Bump winston in /nextcloud_backup/rootfs/opt/nextcloud_backup [`113`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/113) `dependabot[bot]`


# V0.16.6

## 🚑 Fixs

- :ambulance: Fix clean using wrong http method + url (#110) [`73165cd`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/73165cd764a0ae71aef46def046d3ce66edb4618) 

## ⬆️ Dependency updates

- :arrow_up: Bump winston in /nextcloud_backup/rootfs/opt/nextcloud_backup [`105`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/105) `dependabot[bot]`
- :arrow_up: Bump http-errors [`98`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/98) `dependabot[bot]`
- :arrow_up: Bump webdav in /nextcloud_backup/rootfs/opt/nextcloud_backup [`104`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/104) `dependabot[bot]`
- :arrow_up: Bump express in /nextcloud_backup/rootfs/opt/nextcloud_backup [`97`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/97) `dependabot[bot]`
- :arrow_up: Bump debug in /nextcloud_backup/rootfs/opt/nextcloud_backup [`95`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/95) `dependabot[bot]`
- :arrow_up: Bump cookie-parser [`93`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/93) `dependabot[bot]`


# V0.16.5

# ⚠️ BREAKING CHANGE / REGRESSION ⚠️ 
I have temporary disabled the home assistant sensors.
I suspect my implementation to cause home assistant api flooding. 

I also need feedback to try to fix an issue that some user experiment, if you have any error like `HTTPError: Response code 400 (Bad Request)`, please add your feedback / logs to this issue: [#102](https://github.com/Sebclem/hassio-nextcloud-backup/issues/102). 
At this time, I'm not able to reproduce this error on my setup, so any additional information is welcome.


## 🚑 Fixs

- :ambulance: Use new supervisor URL + new auth method #102 [`15ed577`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/15ed57768249b9ea4b270dc5e10f013d9f7fd576) 

## 🔨 Changes

- :hammer: Temporary disable home assistant sensor (suspected to create crash) #102 [`aa99b36`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/aa99b360d35876f6650c2991f878313649bae800)