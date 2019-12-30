# Robosys2019

## ライセンス
This repository is licensed under the GPLv3 license, see COPYING.

## 概要
本デバイスドライバはGPLのもと、アップロードされている。
<br>以下の操作方法1で、LEDを点滅させる。(点滅回数は10回)
<br>以下の操作方法2で、LEDを一定時間点灯させる。

## 操作方法
    $ make  
    $ sudo insmod myled.ko  
    $ sudo chmod 666 /dev/myled0  
    
    操作方法1
    $ echo 0 > /dev/myled0
    $ sudo rmmod myled.ko
  
    操作方法2
    $ echo 1 > /dev/myled0
    $ sudo rmmod myled.ko

## 動画URL
