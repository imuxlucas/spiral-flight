# 云间回旋 · Penguin Flight

一个 9:16 竖屏飞行小游戏，使用 Three.js 绘制企鹅飞机、螺旋障碍和体积云。

## 开始游戏

https://imuxlucas.github.io/spiral-flight/

- 点击或按住画面左侧 / 右侧控制飞行，也支持方向键与 A / D。
- 穿过螺旋障碍的分叉通道，坚持更久。
- 空格或右上角按钮暂停。
- 速度随时间增加，最高纪录保存在当前浏览器。

## 部署

当前内容对应本地游戏 V9。GitHub Pages 从 `main` 分支根目录发布。
`index.html` 包含游戏代码；`flight-assets/` 为运行所需的本地云层和大气纹理。
更新时保持这两部分的相对路径。

本地预览：`python3 -m http.server 8080`，然后打开 http://localhost:8080/。

## 技术与致谢

- Three.js
- postprocessing
- @takram/three-clouds、@takram/three-atmosphere、@takram/three-geospatial
- 云彩实现参考 [jeantimex/geospatial](https://github.com/jeantimex/geospatial)。资源许可见 `flight-assets/GEOSPATIAL-LICENSE.txt`。

第三方库的许可文本保存在 `licenses/`，并保留在打包代码的许可注释中。
