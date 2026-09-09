# 助手2号 · Platformer 3D

[开始游戏](https://H4S2O8.github.io/platformer-3d/)

灯博士的三维实验室：依次完成弹性校准、磁力调度、双槽试验场三关平台解谜。通关对白结束后自动进入下一关。

使用电脑浏览器、键盘和鼠标游玩。点击「进入 / 继续测试」后开始。
WASD 移动，鼠标环绕，Space 跳跃，左键 / Z 传递特性，
Enter 继续对白，Tab 收起通讯器，R 返回检查点，Esc 暂停。

此仓库包含已构建的 Godot 4.7.1 Web 发布文件。
采用单线程 WebGL 2 Compatibility 渲染；首次下载约 54 MB（未压缩）。
网页使用 3D 专用立绘；2D 游戏独立保留自己的像素立绘。

## 发布

更新导出的 index 文件并推送 main 后，GitHub Actions 自动部署 Pages。
请保留 HTML、JS、WASM、PCK 和音频 worklet 的同名配套文件。
