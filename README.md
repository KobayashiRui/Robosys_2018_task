# Robosys2018
ロボットシステム学2018の課題1  
Raspberry pi3 を使用したデバイスドライバの作成
## 作成したドライバについて
### 使用方法
```
sudo make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
echo [コマンド] > /dev/myled0
```
### コマンドの種類及び動作
+ a : 0.3秒間隔で4つのLEDが同時に10回点滅後すべてののLEDが点灯する
+ b : 0.3秒の速度でLEDが赤→黄→緑→青→赤の順番で10回点灯後すべてののLEDが点灯する
+ c : 0.3秒の速度でLEDが青→緑→黄→赤→青の順番で10回点灯後すべてののLEDが点灯する
+ 0 : すべてのLEDを消す

## 動画URL
作成したデバイスドライバの動作動画  
https://youtu.be/7xPbnW0739Q
