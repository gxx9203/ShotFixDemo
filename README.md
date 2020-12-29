# ShotFixDemo
android热更新框架ShotFix

# defult url
```
https://www.jianshu.com/p/3901c074220b
```

# 生成class_fix.jar
```
Android/Sdk/build-tools/28.0.2/dx --dex --output=ShotFixDemo/classes_fix.dex /ShotFixDemo/dex
```
# 推送 
```
adb push classes_fix.dex /storage/self/primary/Android/data/com.sarlmoclen.demo/files/dex_directory
```

# 重启
```
adb shell am force-stop com.sarlmoclen.demo
```

# TODO

1.多个热更新的迭代？
2.热更新的版本管理？

