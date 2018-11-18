给[MonkeyDev](https://github.com/AloneMonkey/MonkeyDev)使用的私有Pod仓库。

**注意: 自己开发Pod的时候，文件命名都带上前缀，防止多个pod出现同一个头文件的情况！**

Podfile文件内容:

```
source 'https://github.com/CocoMonkeyDevSpecs.gitaPods/Specs.git' 
source 'https://github.com/lixianshen/ReverseSpec.git'  #不可少

use_frameworks!						#不可少

target 'MonkeyAppDylib' do			#target选动态库
     pod 'WechatPod'     			#pod的名字
end
```

如果出现找不到pod，`open ~/.cocoapods` 删除`repos`下面的`ReverseSpec` repo 重新install。

## Pods

- [ZhuiShuPod](https://github.com/lixianshen/ZhuiShuPod)
功能介绍:追书神器免费换源,去除广告,去除首页多余弹窗
