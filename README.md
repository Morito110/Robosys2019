# Robosys2019

## ライセンス
This repository is licensed under the GPLv3 license, see COPYING.

## 概要
本デバイスドライバはGPLのもと、アップロードされている。
<br>以下の操作方法1で、LEDを点滅させる。
<br>以下の操作方法2で、LEDを点灯させる。

## 操作方法1
    $ make  
    $ sudo insmod myled.ko  
    $ sudo chmod 666 /dev/myled0  
    $ echo 0 > /dev/myled0
    $ sudo rmmod myled.ko
  
## 動画URL
