# V0.17.0

This release introduce a big migration to ESM node-js module.
All have tested everything on test instance but some bug can still be present.

This migration will normally fix #100  and #128 has i have change how the "state" of the app is stored.


### ⚠️ Please check your backup
This app is still in beta state, so please check that your backup hare correctly generated/uploaded. Some people has reported that their backup are listed as "password protected" despite this setting being disabled in the addon config. So please check that your backup are not password protected if not desired (This bug seam to append only at the first startup of the addon, and never append again).

If you find any bug, feel free to [open an issue on Github](https://github.com/Sebclem/hassio-nextcloud-backup/issues)


## 🔨 Changes
- 🔨 Migrate all code to ESM [`124`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/124) `Sébastien Clément`
- 🔨 Migrate to yarn [`8809965`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/88099659335ca65797e6b29a301509aaea32f109) 
- 🔨 Fix CI/CD [`dee239c`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/dee239c0aa26cb3206bf4e7eaabff64ba5bbc54d) [`0d2698b`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/0d2698bcc6818099824dc73bf767a704481aa5c2) 

## ✏ Enhancements

- ✏ Add yarn script for release [`e368873`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/e368873df937be089db7de54e097a111fbf4a34f) 

## ⬆️ Dependency updates

- ⬆️Bump url-parse [`116`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/116) `dependabot[bot]`
- ⬆️ Bump ejs in /nextcloud_backup/rootfs/opt/nextcloud_backup [`131`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/131) `dependabot[bot]`
- ⬆️ Bump debug in /nextcloud_backup/rootfs/opt/nextcloud_backup [`119`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/119) `dependabot[bot]`
- ⬆️ Bump @fortawesome/fontawesome-free [`120`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/120) `dependabot[bot]`
- ⬆️ Bump moment from 2.29.1 to 2.29.3 in /nextcloud_backup/rootfs/opt/nextcloud_backup [`126`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/126) `dependabot[bot]`
- ⬆️ Bump got from 11.8.2 to 12.0.4 in /nextcloud_backup/rootfs/opt/nextcloud_backup [`129`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/129) `dependabot[bot]`
- ⬆️ Bump express from 4.17.2 to 4.18.1 in /nextcloud_backup/rootfs/opt/nextcloud_backup [`132`](https://github.com/Sebclem/hassio-nextcloud-backup/pull/132) `dependabot[bot]`
