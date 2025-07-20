# 九号出行



## 单版本

通过 `Altstore` `全能签` 等任意签名软件任意签名方式安装





## 多版本

### 注意事项

`Bundle Identifier`是应用程序的唯一标识符,多开的核心是修改它的值



1.必须保证 `Bundle Identifier` 的值不为 

```text
cn.ninebot.segway
```



2.`Bundle Identifier` 的值建议填写为

```text
cn.ninebot.segway.old
```



3.签名的过程中需要将文件 `HookBundle.dylib`注入为动态库



4.如果不打算安装建议值填写`Bundle Identifier` 则需自行编译动态库以便实现修改`Bundle Identifier`后仍能正常与九号服务器通信

