# iOS版Shadowrocket 完美重签 无需付费 无需越狱~ (理论上支持越狱手机所有已购App)
# 越狱手机砸壳ipa 详见<https://github.com/AloneMonkey/frida-ios-dump>
# 查看应用的bundleID ```Python3 dump.py -l```
# 砸壳 ```Python3 dump.py bundleID```


## 使用

#### 1、安装MonkeyDev(如已安装，跳过)

- 安装最新的theos

```
sudo git clone --recursive https://github.com/theos/theos.git /opt/theos
```

- 安装ldid(如安装theos过程安装了ldid，跳过)

```
brew install ldid
```

- 指定的Xcode

```
sudo xcode-select -s /Applications/Xcode.app
```

- 执行安装命令

```
sudo /bin/sh -c "$(curl -fsSL https://raw.githubusercontent.com/AloneMonkey/MonkeyDev/master/bin/md-install)"
```

#### 2、运行工程

- 打开工程 WCShadowrocket.xcodeproj 
- 选择证书：自动配置证书即可（相信大家都是没有问题的）。
- 选择设备(不可选择模拟器，且仅支持64位设备)运行。
- 本次测试机iphone6s 10.3.3 xcode 9.3（其他机型应该也没问题）。


## 版权及免责声明

- iOS逆向实践，不可使用于商业和个人其他意图。一切问题均由个人承担，与本人无关。
- 感谢MonkeyDev的作者庆总<https://github.com/AloneMonkey/MonkeyDev>。
- 如内容对您的权利造成了影响，请[issues](https://github.com/we11cheng/WCShadowrocket/issues), 我会在第一时间进行删除。



## 效果截图

![](http://p2bzzkn05.bkt.clouddn.com/18-4-10/70735207.jpg)


## 华丽的分割线

点右上角的 Star 可以领红包，不信你试试。重签付费应用就是这么容易，感谢MonkeyDev作者。

## 最近更新

酷我音乐无损音质去壳ipa 路径：其他砸壳ipa目录下。拖入项目target运行即可（应用我都会先测试一下,放心使用）     
提供免费付费软件砸壳，低调使用。应用列表：Shu Thor Detour Kitsunebi Pythonista HyperApp JSBOx Surge Quantumult PPHub Tik Tok Mume Mume Red ...


