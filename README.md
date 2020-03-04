# adhosts
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
https://bmyjacks.oss-cn-shenzhen.aliyuncs.com/adlist/adhosts.txt
```
3. Run `pihole -g`
### AdGuard Home
1. Go filters
2. Add filter
3. URL:"`https://bmyjacks.oss-cn-shenzhen.aliyuncs.com/adlist/adhosts.txt`"
4. Click `Check update`
## Problem feedback
If you find that some of your services are not working properly in use, please take a screenshot and submit it it to us. Use the Issues Page.
## LICENSE
MIT
###### Copyright (c) 2019-2020 bmyjacks
