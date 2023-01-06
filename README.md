![test](https://github.com/koteitan00/mypkg/actions/workflows/test.yml/badge.svg)
# mypkg
  ロボットシステム学内で作成したROS2パッケージ
  
  ROS2を用いてtalkerとlistener同士が通信出来る

## 開発環境
* Ubuntu22.04
* ROS2 Humble
* Python 3.7~3.10 

## インストール方法
'''
1. $ git clone https://github.com/koteitan00/ros2_setup_scripts
2. $ cd ros2_setup_scripts
3. $ ./setup.bash
4. $ source ~/.bashrc
'''
### 概要
* トピック: countup
* メッセージの型: Int16
* 挙動: 数字をカウントしconutupにて送信、listener.pyにより表示

#### 機能

talker:数字をカウントし、それを送信する
listener:メッセージを受け取り、それを表示する

#### 実行方法

   端末1: $ros2 run mypkg talker
   
   端末2: $ros2 run mypkg listener

##### テスト環境
* Ubuntu22.04

* ROS2 Humble

* Python 3.7~3.10

###### ライセンス
* このソフトウェアパッケージは3条項BSDライセンスの下，再頒布および使用が許可されます．
* © 2022 Hoshi Kairi

