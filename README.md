# 中国旅行 Level 地图

一个单文件静态网页，用参考图风格的省份块地图记录中国省级地区旅行经历。支持分级涂色、自动计分和 PNG 图片导出。

## 功能

- 点击等级后再点击省份，即可更新该省份颜色和分数。
- 支持 7 个等级：长居 5 分、停留 4 分、旅游过 3 分、中转 2 分、路过 1 分、想去 0 分、未去过 0 分。
- 自动统计总分、已标记地区数量和各等级数量。
- 可自定义地图标题。
- 可导出 PNG 图片用于分享。

## 本地使用

直接用浏览器打开 `index.html` 即可使用，不需要安装依赖。

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库，例如 `china-travel-level`。
2. 把本项目文件提交到仓库根目录。
3. 进入仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 里选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/root`，保存。
6. 稍等部署完成后，访问：

```text
https://你的用户名.github.io/china-travel-level/
```

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

## 截图

可以在网页中点击“导出图片”，把生成的 PNG 保存到 `assets/preview.png`，然后取消下面这一行的注释或替换为自己的截图。

```md
![预览](assets/preview.png)
```

## 说明

这是一张参考图风格的省份块地图，用于旅行记录和可视化，不是正式地理边界地图，也不代表精确行政区划边界。

## License

MIT
