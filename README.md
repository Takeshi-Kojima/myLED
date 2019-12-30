# myLED
# 2019年度　ロボットシステム学　課題
# 概要
　LEDが不規則に３回点滅するデバイスドライバ．
# 手法
##  デバイスドライバの作成
```
$ git clone https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
$ cd raspberry_pi_kernel_build_scripts
$ sudo ./karnel_build_and_install_for_pi2_pi3.bash
$ sudo reboot
```
## 使用方法
```
$ git clone https://github.com/komakou/robosyskadai1.git
$ cd robosyskadai1
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```

## 実行
```
$ echo 1 > /dev/myled0
```
## youtube
　https://www.youtube.com/watch?v=B-aJ3snYFmI
