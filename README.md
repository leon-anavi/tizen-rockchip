tizen-rockchip
==============

Porting Tizen to devices with Rockchip SoC such the open source hardware board Radxa Rock


Downloads
===========
Tizen:Common image for Radxa Rock is available for download at:
http://pc.cd/eKx

Replace X with the letter corresponding to the micro SD card and execute the following commands to copy the image on micro SD card using a personal computer with Ubuntu (another Unix-like OS or Linux distribution):

```
umount /dev/sdX*
tar -jxvf radxa-rock-tizen-common-20141116.tar.bz2
sudo dd if=radxa-rock-tizen-common-20141116.img of=/dev/sdX
sync
```
