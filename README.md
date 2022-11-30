# mypkg
ロボットシステム学の授業で作成

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．

## 概要
このソフトウェアパッケージは、ROS2の通信の様子を確認することができます。

## ROS2の環境構築
-ROS2のインストール
```
$ git clone https://github.com/ryuichiueda/ros2_setup_scripts
$ cd ros2_setup_scripts
$ ./setup.bash
$ source ~/.bashrc
```
-パッケージをビルド
```
$ cd ~/ros2_ws/ && colcon build
```
-~/.bashrcの末尾に2行追加
```
source ~/ros2_ws/install/setup.bash
source ~/ros2_ws/install/local_setup.bash
```
```
source ~/.bashrc
```

## 使用方法
-端末１
```
$ ros2 run mypkg talker
```
-端末２
```
$ ros2 run mypkg listener
```



© 2022 Yusaku Matsuyama
