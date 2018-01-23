This repository is a partial fork from Wi5/odin-wi5. You will find detailed information in this wiki: https://github.com/Wi5/odin-wi5/wiki

The modification to the code here is done to fit odin-wi5 into TL-WR1043 v2 with 8MB of flash memory. 
Steps to take:
- Run `./config.sh` to conifgure OpenWRT firmware with Click software router and driver pactches for TL-WR1043ND
- Edit `openwrt/target/linux/ar71xx/image/Makefile` by changing WR1043V2 flash from `8M` to `16M`.
- Then run `make -j 4`
