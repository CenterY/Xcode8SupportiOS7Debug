# Xcode8SupportiOS7Debug
Xcode8Support Debug with iOS7 deveice
1. 安装低版本Xcode [下载地址](https://developer.apple.com/download/more/)
2. 前往 `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport` 拷贝 7.0 7.1 文件夹
3. 升级到Xcode8，再次前往 `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport` 将之前拷贝出来的文件夹放入 
4. 使用Xcode 编辑`/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/SDKSettings.plist`在`DefaultProperties` 下找到 `DEPLOYMENT_TARGET_SUGGESTED_VALUES` 增加 两项分别为`7.0` ，`7.1`
5. 重启 Xcode 

