# HTML-based Sora Watermark for Live Streaming
EN | [中文](https://github.com/AomiRaku/live-sora-watermark/blob/main/README_CN.md)

[Download source code](https://github.com/AomiRaku/live-sora-watermark/releases)

An HTML-based Sora watermark project for live streaming, which can be added to the screen using the built-in browser source of streaming software like OBS.

Essentially, it is a webpage that displays images in rotation at the top-left, middle-right, and bottom-left of the page. It can adapt to horizontal, vertical, and other screen sizes.


A pre-made GIF watermark (about 4 seconds long) is included.

By default, the watermark height is 12% of the page height, with 90% opacity, and it switches every 4 seconds. You can customize it by modifying the source code of `index.html` (there are comments).

### Effect:
Bilibili video: https://b23.tv/kvdB63l

<img  height="350" alt="Preview" src="https://github.com/user-attachments/assets/8fce9c95-f7e5-4a31-b4cd-a6630a010d07" />


## Usage (taking OBS as an example):
- After downloading the source code, unzip the entire package to a location;
- Open OBS, click the plus sign, and add a Browser source;
  
  <img  height="500" alt="1" src="https://github.com/user-attachments/assets/b62b37dc-dbda-43d4-b5cc-1c3d30aaea0e" />

- After adding, in the pop-up window, check "Local file", select the extracted `index.html`, then set an appropriate size (depending on the canvas size), and click OK.
  
  <img height="500" alt="2" src="https://github.com/user-attachments/assets/c45b9fe6-0a43-4057-a58d-02effc022646" />

- Done. Adjust the position as needed.


## Others

This project uses Tailwind CSS:

https://github.com/tailwindlabs/tailwindcss
