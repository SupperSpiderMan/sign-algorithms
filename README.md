# 简介
##### 逆向一些简单的Android app的签名或加密算法。

### App列表

#### 美拍
##### 版本-7.9.5
##### url参数中sig和sigTime

#### 梨视频
##### 版本-6.7.2
##### headers里X-Client-Hash

#### 链家
##### 版本-9.12.0
##### headers的Authorization

#### 秒拍
##### 版本-7.2.68
##### 一些参数生成方式

#### 小红书
##### 版本-
##### url里的sign，听说sheild很难

#### 抖音
##### 版本-10.1.0
##### 只能解决gorgon和设备注册，xlog无法调用
##### https://github.com/heyaug/HttpSo