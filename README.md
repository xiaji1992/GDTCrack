# 广点通(iOS)SDK自定义包名（Bundle ID）
版本号：v4.7.8

### 使用说明

#### 第一步：将整个lib目录拖入到工程中

本分支 lib 目录下 是修改过的广点通sdk，请将整个lib目录拖入到工程中

#### 第二步：修改成自己想要自定义的包名（bundle id）
修改lib目录下的 GDTCustomBundleID.plist文件，修改成自己需要自定义的bundle id，比如com.tencent.xin
请注意，v4.7.8版本跟之前版本的plist的key值是不一样的，本次的key值是 FFBundleIdentifier
#### 第三步：加入-ObjC

在Xcode中选中TARGETS->Build Settings

找到Linking中的Other Linker Flags，添加-ObjC

```

更多使用说明请参考官方文档


```
请由此打开 [官方文档](https://imgcache.qq.com/qzone/biz/gdt/dev/sdk/ios/release/Guide.pdf)


