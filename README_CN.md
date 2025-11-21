# 基于html的直播用sora水印
[EN](https://github.com/AomiRaku/live-sora-watermark) | 中文


一个基于html的直播用sora水印项目，使用obs等推流软件的内置浏览器源即可添加进画面。

本质上就是一个把图片在页面左上、右中、左下轮流显示的网页。可自适应横屏、竖屏等尺寸。


已预置了一个我做好的gif水印，长约4秒。

默认水印高度为页面高度的 12% ，透明度 90% ，4 秒一换。可以修改 `index.html` 的源码自定义。（有注释）

### 效果：
Bilibili视频：https://b23.tv/kvdB63l

<img  height="350" alt="预览" src="https://github.com/user-attachments/assets/8fce9c95-f7e5-4a31-b4cd-a6630a010d07" />


## 使用方法（以OBS为例）：
- 下载源码后整个解压到一个位置；
- 打开obs，点加号，添加一个浏览器源；
  
  <img  height="500" alt="1" src="https://github.com/user-attachments/assets/b62b37dc-dbda-43d4-b5cc-1c3d30aaea0e" />

- 添加后，弹出的窗口勾选本地文件，选择解压出的 ` index.html ` ，然后设置一个合适的大小（根据画布大小而定），点确定。
  
  <img height="500" alt="2" src="https://github.com/user-attachments/assets/c45b9fe6-0a43-4057-a58d-02effc022646" />

- 完成，根据需要调整位置。


## 其他

该项目使用了 Tailwind CSS：

https://github.com/tailwindlabs/tailwindcss

