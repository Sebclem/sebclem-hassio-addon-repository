# ⚠️ BREAKING CHANGE / REGRESSION ⚠️ 
I have temporary disabled the home assistant sensors.
I suspect my implementation to cause home assistant api flooding. 

I also need feedback to try to fix an issue that some user experiment, if you have any error like `HTTPError: Response code 400 (Bad Request)`, please add your feedback / logs to this issue: [#102](https://github.com/Sebclem/hassio-nextcloud-backup/issues/102). 
At this time, I'm not able to reproduce this error on my setup, so any additional information is welcome.


## 🚑 Fixs

- :ambulance: Use new supervisor URL + new auth method #102 [`15ed577`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/15ed57768249b9ea4b270dc5e10f013d9f7fd576) 

## 🔨 Changes

- :hammer: Temporary disable home assistant sensor (suspected to create crash) #102 [`aa99b36`](https://github.com/Sebclem/hassio-nextcloud-backup/commit/aa99b360d35876f6650c2991f878313649bae800)