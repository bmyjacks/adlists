# adhosts
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/bmyjacks/adhosts?label=commit&logo=github&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/bmyjacks/adhosts?logo=github&style=for-the-badge)
![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hw/bmyjacks/adhosts?color=green&label=downloads&logo=jsDelivr&style=for-the-badge)

This is a blocklist for PiHole
## Install
### Pi-hole
1. Open the terminal and enter:
```
bash
sudo nano /etc/pihole/adlists.list
```
2. At this point you should see the nano editor page and add the following commands to the end of the file
```
https://cdn.jsdelivr.net/gh/bmyjacks/adhosts/adhosts.txt
```
3. Run `pihole -g`
### AdGuard Home
1. Go to `filters`
2. Click `Add filter`
3. URL:"`https://cdn.jsdelivr.net/gh/bmyjacks/adhosts/adhosts.txt`"
4. Click `Check update`
## Problem feedback
If you find that some of your services are not working properly in use, please take a screenshot and submit it it to us. Use the Issues Page.
## LICENSE
MIT
###### Copyright (c) 2019-2020 bmyjacks
