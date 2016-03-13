# iChrome
[![Build Status](https://api.travis-ci.org/AMKohn/iChrome.svg)](https://travis-ci.org/AMKohn/iChrome) [![Codacy Badge](https://api.codacy.com/project/badge/grade/971d2d380b1143a89c9416af32721f17)](https://www.codacy.com/app/AMKohn/iChrome) [![Crowdin](https://d322cqt584bo4o.cloudfront.net/ichrome/localized.png)](https://crowdin.com/project/ichrome) [![devDependency Status](https://david-dm.org/AMKohn/iChrome/dev-status.svg?style=flat)](https://david-dm.org/AMKohn/iChrome#info=devDependencies) [![twitter](http://img.shields.io/badge/twitter-@iChromeHQ-blue.svg?style=flat)](http://twitter.com/iChromeHQ)

iChrome是一个高度可定制的，iGoogle主页更换扩展由谷歌现在的影响。它包括近100 HD主题，30多个小部件，多标签支持，“OK谷歌”启动指令检测和语音搜索，国际化支持，几乎完全自定义。.

这是完整的源ichrome除了API的秘密已被替换占位符。

## Jump to Section

* [Setup](#setup)
* [Road Map](#road-map)
* [Contributing](#contributing)
* [Style Guide](#style-guide)
* [License](#license)

## 安装程序
[[Back To Top]](#jump-to-section)

按照这些步骤来运行ichrome谷歌浏览器作为开发商。

- 打开URL chrome://extensions/ 在谷歌或360极速浏览器.
- 单击以启用 *Developer mode* 让你看到开发者选项。
- 点击 "加载已解压的扩展程序..."
- 浏览到该位置ichrome回购安装，并选择子目录 `iChrome/app` as the扩展源.

> 如果您已经从谷歌Play商店安装iChrome，然后做以上之前删除扩展.

## 路线图
[[Back To Top]](#jump-to-section)

#### V2.x

 - 一个真实的网站

### V2.2

这些都是在不断变化非常多，其中任何一个可以推迟或跳过。

##### iChrome Pro:

   - 优先级的支持和建议
   - 2完全同步每个标签的主题。
   - 要创建在iChrome服务器上托管的动态自定义主题（视频，幻灯片显示，时间和日期而定）的能力
   - 30 在线备份
   - “上级”与远程黑名单部件和锁配置的能力控制
   - 可能最大化部件
   - 各个部件的功能，包括使用图表实时库存，实时分析，更准确的天气等等。

## 贡献
[[Back To Top]](#jump-to-section)

如果你愿意捐款，请用叉子叉正回购，并提交一份请求。

## 样式指南
[[Back To Top]](#jump-to-section)

 - 代码缩进4空间的标签，没有空间
 - 双引号总是除非字符串包含双引号的使用，如HTML
 - 尾分号总是
 - 当多个变量被定义为一个函数的顶部时，它们通常被合并为一个无功的语句
 - 三元运算符很好尤其是字符串连接
 - 性能要优于小片段的可读性。即
 - `$(body).append($('<div></div>').attr("data-id", id.split("-")[1]))` instead of `var elm = $('<div></div>'), id = id.split("-")[1]; elm.attr("data-id", id)....`

## License
[[Back To Top]](#jump-to-section)

ichrome授权下 [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/deed.en_US).

基本上，只要你给信用证，你只要你想要的代码可以自由使用。如果你不介意的话，请告诉我。
