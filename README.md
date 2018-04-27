# 广点通(iOS)SDK自定义包名（Bundle ID）
版本号：v4.6.4

### 使用说明

#### 第一步：将整个lib目录拖入到工程中

本分支 lib 目录下 是修改过的广点通的sdk，请将整个lib目录拖入到工程中

#### 第二步：修改成自己想要自定义的包名（bundle id）
修改lib目录下的 GDTCustomBundleID.plist文件，修改成自己需要自定义的bundle id，比如com.tencent.wx

#### 第三步：加入-ObjC

在Xcode中选中TARGETS->Build Settings

找到Linking中的Other Linker Flags，添加-ObjC

```

更多使用说明请参考官方文档 Guide v4.6.4.pdf

需要特别说明的是v4.6.4支持bitcode，目前为止v4.7.0和v4.7.1均不支持bitcode


```



