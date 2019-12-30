# Robosys2019

##ライセンス
This repository is licensed under the GPLv3 license, see COPYING.

## 概要
本デバイスドライバはGPLのもと、アップロードされている。
<br>LEDを点灯させる

## ファイル位置
Robosys2019/myled.c

## 操作方法
    $ make  
    $ sudo insmod myled.ko  
    $ sudo chmod 666 /dev/myled0  
    $ echo 0 > /dev/myled0 
    
## 動画URL
