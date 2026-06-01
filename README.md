# 中国旅行 Level 地图

一个单文件静态网页，用参考图风格的省份块地图记录中国省级地区旅行经历。支持分级涂色、自动计分和 PNG 图片导出。

## 直接使用/分享

打开下面的链接即可直接使用，也可以复制给别人。默认打开时所有省级地区都是未标记状态，Level 为 0：

[https://frankdeng98.github.io/china-travel-level/?v=level0](https://frankdeng98.github.io/china-travel-level/?v=level0)

## 功能

- 点击等级后再点击省份，即可更新该省份颜色和分数。
- 支持 7 个等级：长居 5 分、停留 4 分、旅游过 3 分、中转 2 分、路过 1 分、想去 0 分、未去过 0 分。
- 自动统计总分、已标记地区数量和各等级数量。
- 可自定义地图标题。
- 可导出 PNG 图片用于分享。

## 本地使用

直接用浏览器打开 `index.html` 即可使用，不需要安装依赖。

## 项目结构

```text
.
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    └── README.md
```


## 说明

这是一张参考图风格的省份块地图，用于旅行记录和可视化，不是正式地理边界地图，也不代表精确行政区划边界。

## License

MIT
