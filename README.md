
# web-video-asciiify （视频字符化网页播放器）

### 注意事项

- 由于浏览器安全策略原因，index.html需要服务器（apache等）访问才能正常播放，也可以用vscode的live server插件。不能用浏览器直接打开index.html

- 不要使用太大的视频文件，使用fileReader是一次性读入文件内存消耗比较大，否则加载慢

- 开启彩色模式后，宽度不要设置过高，否则渲染卡顿