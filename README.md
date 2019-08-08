# Square Player

一个简洁到极致的单曲播放器，基于 ES6 标准开发的试水之作。

## 使用方法

1. `Star` 本项目
2. 从这里 [下载](https://github.com/Dreamer-Paul/Square-Player/archive/master.zip) 源码
3. 可使用本地、网易云音乐两种方式食用，参照下面的快速食用手册即可快速部署完成

## 开源协议

本项目采用 MIT 开源协议进行授权，须保留原作者的版权注释（CSS、JS 文件）

原创不易！如果喜欢本项目，请 `Star` 它以示对我的支持~

同时欢迎前往 [保罗的小窝](https://paul.ren/donate) 为我提供赞助，谢谢您！

## 感谢

感谢来自开源社区提供的解决方案，如果没有它们，Square Player 可能还无法如此完善 ヽ(*≧ω≦)ﾉ

 - [Meting](https://github.com/metowolf/Meting)

### 快速食用指南

在网页 `head` 标签引用项目的 CSS 文件 `SQPlayer.css`：

```html
<head>
...
<link href="SQPlayer.css" rel="stylesheet" type="text/css"/>
...
</head>
```

在网页 `body` 标签内的最后一行引用项目的 JS 文件 `SQPlayer.js`：

```html
<body>
...
<script src="SQPlayer.js"></script>
</body>
```

在网页 `body` 标签内插入一个 `sqplayer` 标签：

```html
<body>
...
<sqplayer></sqplayer>
...
</body>
```

Square Player 支持以下属性，他们分别的意义是：

属性名|用途
:-:|:-:
right|至右显示
data-title|歌曲名
data-artist|艺术家
data-cover|专辑封面图片链接
data-link|歌曲地址
data-163|网易云音乐的 ID 或歌名

如果使用 `data-163` 属性引用播放器，就写成这样，其中 `23682511` 就是一首歌的 ID。

```html
<sqplayer data-163="23682511"></sqplayer>
```

如果使用静态方法引用播放器，就需要同时编写四个属性。

```html
<sqplayer right data-title="Crimson & Clover" data-artist="Tommy James" data-cover="封面链接" data-link="歌曲链接"></sqplayer>
```


# Pio
一个支持更换 Live2D 模型的 Typecho 插件。

本插件不存在任何依赖的样式和库，在后续版本当中我会逐渐实现一些有趣的功能。

## 使用方法
1. Star 本项目
2. 从这里 [下载](https://github.com/Dreamer-Paul/Pio/archive/master.zip) 本插件
3. 将插件文件夹重命名为 `Pio`
4. 上传本插件，并放置在 `usr/plugins/` 目录下
5. 登录你的 Typecho 后台，找到 `Pio` 选择启用插件
6. 你可以通过 [选择](https://docs.paul.ren/pio/#/?id=选择模型) 或 [外链](https://docs.paul.ren/pio/#/?id=选择外链模型) 的方式引用你获得的模型资源

奇趣保罗自己搭建的 [梦象资源站](https://mx-model.ga) 上提供了较多可用于本插件的模型资源，如果你也想在这里提交自己的原创作品，不妨现在就和我 [取得联系](https://paul.ren)吧！

想了解更多的玩法，欢迎阅读 [插件文档](https://docs.paul.ren/pio)。如果对本项目有任何的建议和想法，欢迎随时提出~

## 项目故事
详见我的博文：[给你的博客增加动态看板娘](https://paugram.com/coding/add-poster-girl-with-plugin.html)，帮助文档及常见问题均在这里即时更新。

## 开源协议
由于原项目使用 GPL 2.0 协议，故本项目也采用相同的开源协议进行授权。

原创不易！如果喜欢本项目，请 Star 它以示对我的支持~

同时欢迎前往 [保罗的小窝](https://paul.ren/donate) 为我提供赞助，谢谢您！

## 使用的开源项目
 - [Live2D-SRC](https://github.com/journey-ad/live2d_src)

## 感谢
 - [Live2D](https://www.live2d.com)