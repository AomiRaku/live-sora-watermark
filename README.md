# HTML-Based Sora Watermark for Live Streaming

EN |  [中文](https://github.com/AomiRaku/live-sora-watermark/blob/main/README_CN.md)

An HTML-based Sora watermark project for live streaming. Add it to your stream using the built-in Browser Source in streaming software like OBS.

Adapts to horizontal, vertical, and other aspect ratios automatically.

Customizable options include watermark size, text below the watermark, opacity, random position, and more.

 [Download](https://github.com/AomiRaku/live-sora-watermark/releases)

### Demo:

Bilibili Preview Video: [https://b23.tv/kvdB63l](https://b23.tv/kvdB63l)



![Preview](https://github.com/user-attachments/assets/8fce9c95-f7e5-4a31-b4cd-a6630a010d07)

## Configuration

Open `index.html` with a text editor to configure the settings.

| Configuration Item     | Default Value | Description                                                  |
| ---------------------- | ------------- | ------------------------------------------------------------ |
| `text`                 | -             | Watermark username text                                      |
| `enableRandomPosition` | `false`       | false = Cycle (Top-left → Middle-right → Bottom-left), true = Random |
| `sizeVh`               | `11`          | Watermark height ratio relative to the page height (vh)      |
| `safeMarginPercent`    | `0`           | Side margin (%)                                              |
| `opacity`              | `0.9`         | Opacity (0.0 - 1.0) (1.0 = fully opaque)                     |

\*Items not recommended for modification are not listed.

## Usage (OBS as Example):

- [Download the source code](https://github.com/AomiRaku/live-sora-watermark/releases) and extract the entire package to a location of your choice.

- Open OBS, click the "+" button, and add a Browser Source.

![Step 1](https://github.com/user-attachments/assets/b62b37dc-dbda-43d4-b5cc-1c3d30aaea0e)

- After adding, check "Local file" in the pop-up window, select the extracted `index.html`, set an appropriate size (Recommended to be half of the canvas size), and click "OK".

![Step 2](https://github.com/user-attachments/assets/c45b9fe6-0a43-4057-a58d-02effc022646)

- Done! Adjust the position as needed.

## Others

Feel free to follow my Bilibili account [@Raku Inkyetta](https://space.bilibili.com/18251508) – Thank you ~

A huge thank you to Bilibili user [@又在摸鱼啊啊啊](https://space.bilibili.com/226208473) for optimization and technical support !
