# 米居（miju）安卓手表版开源代码
「米居」For Watch，便捷操控你的米家智能家居~

## 米居开源项目须知与声明
一. 本开源项目仅供个人学习交流使用，方便安卓手表端可以控制米家的智能家居。  
二. 本项目完全免费，可能存在较多漏洞，但本人能够正常使用。  
三. 本项目中所有适配的接口均来自小米公司（北京小米科技有限责任公司）旗下米家（MIJIA），本项目不对其控制的安全性负责。  
四. 本项目会将账户、密码、家庭信息等信息，缓存在软件本地，不含任何上传个人信息的接口。   
五. 真诚地希望小米官方能够推出 米家 For Watch，我也能用得上。   
六. 本项目仅供个人学习交流使用，切勿进行传播、任何形式的盈利，未涉及的问题请参见国家有关法律法规，以国家法律法规为准。

## 开发者测试使用设备：
- OPPO Watch2 42mm（方形表盘）

## 支持最低安卓版本（我并没有测试过）：
- Android 4.4

## v1.0 版本功能
#### 1. 我的米家：
- 家庭切换（对应的智能场景均会切换）
- 账户总设备在线数
- 家庭温湿度环境信息（需要在米家首页[环境模块]自行设置）

#### 2. 智能场景：
- 实现对智能场景的控制
- 在手机端米家首页即可增删改和排序智能场景

#### 3. 小爱指令：
- 需要家庭中至少有一个小爱音箱
- 发送指令，小爱音箱就会进行执行（包括红外指令，红外指令需要切换指定的小米音箱）
- 指令执行时，可以选择静默执行还是有回复执行（回复会由小爱音箱播放，默认静默执行，类似于小爱同学）
- 可以让小爱音箱朗读输入端文字

#### 4. 遥控器：
- 使用遥控器时，需要与要控制的小米电视/盒子在同一网络下
- 操控不同账户绑定的小米电视/盒子设备需要进行切换
- 支持按IP添加控制设备，控制IP需要在电视设置或路由器设备列表中找到（格式一般为192.168.X.X）

## TODO List
- 关于智能设备的获取、开关
- 特殊智能设备的多样化控制，如亮度、色温等
- 遥控器支持智能空调和红外线等设备
