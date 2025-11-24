# 基于html的直播用sora水印

[EN](https://github.com/AomiRaku/live-sora-watermark) | 中文

一个基于html的直播用sora水印项目，使用OBS等推流软件的内置浏览器源即可添加进画面。

可自适应横屏、竖屏等各种比例。

水印大小、水印下方文字、不透明度、随机位置等可以自定义。

### 效果：

Bilibili预览视频：https://b23.tv/kvdB63l

<img  height="350" alt="预览" src="https://github.com/user-attachments/assets/8fce9c95-f7e5-4a31-b4cd-a6630a010d07" />





## 配置

可以用文本编辑器打开  `index.html`  来进行配置。

| 配置项                 | 默认值  | 描述                                          |
| ---------------------- | ------- | --------------------------------------------- |
| `text`                 | -       | 水印下方文字                                  |
| `enableRandomPosition` | `false` | false = 循环（左上->右中->左下），true = 随机 |
| `sizeVh`               | `11`    | 水印高度占页面高度比 (vh)                     |
| `safeMarginPercent`    | `0`     | 两侧边距 (%)                                  |
| `opacity`              | `0.9`   | 不透明度 (0.0 - 1.0）（1.0为不透明)           |

*不建议修改的项未列出






## 使用方法（以OBS为例）：

- [下载源码](https://github.com/AomiRaku/live-sora-watermark/releases)后整个解压到一个位置；

- 打开obs，点加号，添加一个浏览器源；

  <img  height="500" alt="1" src="https://github.com/user-attachments/assets/b62b37dc-dbda-43d4-b5cc-1c3d30aaea0e" />

- 添加后，弹出的窗口勾选本地文件，选择解压出的 ` index.html ` ，然后设置一个合适的大小（建议为画面尺寸的一半），点确定。

  <img height="500" alt="2" src="https://github.com/user-attachments/assets/c45b9fe6-0a43-4057-a58d-02effc022646" />

- 完成，根据需要调整位置。





## 其他

欢迎关注我的b站 [@羽梦千景](https://space.bilibili.com/18251508) 谢谢喵~

非常感谢b站用户 [@又在摸鱼啊啊啊](https://space.bilibili.com/226208473) 的优化和技术支持喵！
