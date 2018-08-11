# GDTCrack
腾讯广点通sdk(iOS)破解版（支持自定义包名）

主要功能：可以自定义包名，绕过errorCode=5006的错误（包名校验非法）

## 使用场景
用于多个iOS应用使用同一个广告ID

用过腾讯广点通的开发者都知道从2016年开始腾讯开始启动包名校验功能，这让很多之前几个app公用一个id的开发者很苦恼，于是就有了这个广告sdk破解版的开发，造福广大开发者（虽然来得有点迟）


## 下载地址

#### v4.7.8

* 直接下载：[点击下载v4.7.8.zip](https://github.com/gdtcrack/GDTCrack/archive/v4.7.8.zip)

* 进入对应分支：[点击进入v4.7.8分支](https://github.com/gdtcrack/GDTCrack/tree/v4.7.8)

#### v4.7.4

* 直接下载：[点击下载v4.7.4.zip](https://github.com/gdtcrack/GDTCrack/archive/v4.7.4.zip)

* 进入对应分支：[点击进入v4.7.4分支](https://github.com/gdtcrack/GDTCrack/tree/v4.7.4)


## 使用方法
将本仓库中 对应版本分支下的 `lib目录` 整体拖入到工程，修改lib目录下 `GDTCustomBundleID.plist` 文件为自己想自定义的bundle id，其他配置按照下面说明，需要说明的是每个版本的sdk中 `GDTCustomBundleID.plist`中的key有可能不同，升级的时候请使用该版本中的key

