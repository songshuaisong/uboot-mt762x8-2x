[![Build
Status](https://travis-ci.com/songshuaisong/uboot-mt762x8-2x.svg?branch=master)](https://travis-ci.com/songshuaisong/uboot-mt762x8-2x)

# uboot-mt76x8-mt762x

After actual testing, the current version supports

  Mt7620: wooya -- mt7628 core board
  MT7628 : Hi-link -- HLK-7688
  MT7688 : Hi-link -- HLK-7628

# How to use
* 1.make menuconfig
![image](https://github.com/songshuaisong/uboot-mt762x8-2x/blob/master/images/make-menuconfig.png)

* 2.select MT7628 board
* 3.make clean
* 4.make
![image](https://github.com/songshuaisong/uboot-mt762x8-2x/blob/master/images/make.png)

# Note
* note:compile need java such as 1.7.0_79

# update list
* change bps to 115200, fix gpio39,40,41,42 low when startup
* add all gpio test,just press 'WPS' button with more than 7 seconds at power on
* web failsafe update mode,just press 'WPS' button with 2 to 7 seconds at power on
* web failsafe IP is 192.168.1.111
* DDR2 can be 64MB or 128MB, just select 512Mbit or 1024Mbit in menuconfig

* QQ : 1109252300
* mail: 1109252300@qq.com
