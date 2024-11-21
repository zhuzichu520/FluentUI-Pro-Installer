<div align=center>

# FluentUI Pro

基于[FluentUI](https://github.com/zhuzichu520/FluentUI)开源版本重新打造的项目,代码更加漂亮,API更加好用,界面更加细腻

</div>

![release-badge] ![download-badge] ![download-latest]

[release-badge]: https://img.shields.io/github/release/zhuzichu520/FluentUI-Pro-Installer.svg?style=flat-square "Release status"
[download-badge]: https://img.shields.io/github/downloads/zhuzichu520/FluentUI-Pro-Installer/total.svg "Download status"
[download-latest]: https://img.shields.io/github/downloads/zhuzichu520/FluentUI-Pro-Installer/latest/total.svg "latest status"

## 与[FluentUI](https://github.com/zhuzichu520/FluentUI)开源版本有啥不同?

1. 开源版本所有组件都有Flu前缀,Pro版本去掉Flu前缀,只需添加一行```qputenv("QT_QUICK_CONTROLS_STYLE", "FluentUI");```代码,就能将原有Button换成FluentUI样式
2. 项目整体架构不同,开源版本代码都写在一个模块下,Pro版本分为FluentUI,FluentUI.Controls,FluentUI.impl三个模块
3. 开源版本不支持热加载，Pro版本支持热加载，运行之后修改代码可实时关注QML界面变化，支持一键关闭开启
4. 开源版不支持wasm编译，Pro版本支持wasm编译
5. 开源版本过于臃肿，Pro版本做了减法，去其糟粕，取其精华，重新打造
6. 开源版默认动态库依赖，Pro版本默认静态库依赖
7. 开源版MIT协议免费，Pro版本付费，如有需要请联系作者wx购买：FluentUI

## 下载Pro版本
[下载地址](https://github.com/zhuzichu520/FluentUI-Pro-Installer/releases)
