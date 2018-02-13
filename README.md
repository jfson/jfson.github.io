
> 文章整理,未完待续...

![](https://github.com/jfson/ImgResource/blob/master/22.jpeg?raw=true)

### Android 源码
> 主要梳理Android Frameworke层源码

|  序号  | 文章名                                      | 概述                                |
| :--: | :--------------------------------------- | :-------------------------------- |
|  0   | [Android 源码编译](https://jfson.github.io/2017/05/16/08-Android-source/) | 编译 Android 6.0 源代码                |
|  1   | [Android Zygote](https://jfson.github.io/2017/05/23/04-Zygote/) | Zygote进程启动流程                      |
|  2   | [Android SystemServer](https://jfson.github.io/2017/05/23/03-SystemServer/) | SystemServer 进程启动流程               |
|  3   | [Android Launcher](https://jfson.github.io/2017/06/01/09-Android%E6%A1%8C%E9%9D%A2Launcher%E5%90%AF%E5%8A%A8/) | Launcher 启动流程                     |
|  4   | [Android Application](https://jfson.github.io/2017/06/01/01-Application%E5%90%AF%E5%8A%A8%E6%B5%81%E7%A8%8B/) | Application 启动流程                  |
|  5   | [Android Mainfest](https://jfson.github.io/2017/06/02/14-parse-mainfest/) | 系统 Mainfest 文件解析流程                |
|  6   | [Android Handler](https://jfson.github.io/2017/05/15/11-Handler-Looper/) | Handler、Looper、MessageQueue       |
|  7   | [Fragment 的生命周期来龙去脉](https://jfson.github.io/2017/10/06/37-Fragment-life/) | Fragment、FragmentManager、Activity |
|  8   | [LRUCache](https://jfson.github.io/2017/12/22/40-lru/) | LRU算法                             |
|  9   | [Android Window](https://jfson.github.io/2018/01/10/47-view-window/) | Window、ViewRootImpl               |
| ...  | 待续 ...                                   | 待续 ...                            |

### Binder Framework
* 梳理Android Binder的IPC机制,如何进行进程间通信

|  序号  | 文章名                                      | 概述                        |
| :--: | ---------------------------------------- | ------------------------- |
|  0   | [Binder(1) - IPC机制](https://jfson.github.io/2017/06/06/12-Linux%20IPC%E6%9C%BA%E5%88%B6/) | Linux IPC 机制 & 为何选 Binder |
|  1   | [Binder(2) - 序列化](https://jfson.github.io/2017/08/01/23-binder-a/) | Android 中的序列化             |
|  2   | [Binder(3) - AIDL使用](https://jfson.github.io/2017/08/03/24-binder-b/) | 使用AIDL进行进程间通讯             |
|  3   | [Binder(4) - ServiceManager](https://jfson.github.io/2017/08/05/25-binder-c/) | ServiceManager 启动流程       |
| ...  | 待续 ...                                   | 待续 ...                    |

### 开源库
* 常见开源库梳理

|  序号  | 文章名                                      | 概述                             |
| :--: | ---------------------------------------- | ------------------------------ |
|  0   | [Lottie(1) - 简介](https://jfson.github.io/2017/03/06/13-Lottie/) | Lottie 使用                      |
|  1   | [Lottie(2) - AE & Bodymovin 安装](https://jfson.github.io/2017/03/06/07-AE-Bodymovin-environment/) | Lottie的设计工具安装配置：AE & Bodymovin |
|  2   | [Lottie(3) - AE 简单使用 安装)](https://jfson.github.io/2017/03/07/06-ae-work/) | AE制作一个简单的Lottie动画              |
|  3   | [Glide(1)生命周期管理](https://jfson.github.io/2017/10/07/38-Glide-a/) | glide生命周期的绑定                   |
|  4   | [Glide(2)Request队列管理](https://jfson.github.io/2017/10/08/39-Glide-b/) | glide如何管理所有请求队列                |
|  5   | [Android 动画库对比](https://jfson.github.io/2018/01/08/41-anim/) | Lottie、SVGA                    |
|  6   | [maven上传](https://jfson.github.io/2018/01/22/42-%20maven-update/) | Android maven库上传               |
|  7   | [我的第一个开源库](https://jfson.github.io/2018/02/02/43-decoupling/) | Android 解耦框架(自定义View)          |
| ...  | 待续 ...                                   | 待续 ...                         |

### 算法练习

|  序号  | 文章名                                      | 概述                |
| :--: | ---------------------------------------- | ----------------- |
|  1   | [算法基础概念](https://jfson.github.io/2017/12/12/44-arithmetic-base/) | 时间复杂度、空间复杂度、O     |
|  2   | [Two Sum](https://jfson.github.io/2017/12/15/45-arithmetic-1/) | LeetCode-001-easy |
|  3   | [Reverse Integer](https://jfson.github.io/2017/12/18/46-arithmetic-2/) | LeetCode-007-easy |

 

### 设计模式

* 常用设计模式

|  序号  | 文章名                                      | 概述        |
| :--: | ---------------------------------------- | --------- |
|  0   | [设计模式简介](https://jfson.github.io/2017/07/08/17-design-pattern/) | 常用设计模式介绍  |
|  1   | [单例模式(Singleton Pattern)](https://jfson.github.io/2017/07/16/18-single-pattern/) | 最常用的单例模式  |
|  2   | [代理模式(Proxy Pattern)](https://jfson.github.io/2017/07/14/19-proxy-pattern/) | 静态代理和动态代理 |
|  3   | [工厂模式(Factory Pattern)](https://jfson.github.io/2017/07/20/20-factory-pattern/) | 简单工厂模式    |
|  4   | [抽象工厂模式(Abstract Factory Pattern))](https://jfson.github.io/2017/07/24/21-abstract-factory-pattern/) | 抽象工厂模式    |
|  5   | [构造者模式(Builder Pattern))](https://jfson.github.io/2017/07/28/22-builder-pattern/) | 如何进行链式调用  |
| ...  | 待续 ...                                   | 待续 ...    |

### 设计 & 产品
> TODO

### life
| 序号   |                   文章名                    | 概述           |
| :--- | :--------------------------------------: | ------------ |
| 0    | [惜取少年时](https://jfson.github.io/2017/09/08/02-master/) | about master |