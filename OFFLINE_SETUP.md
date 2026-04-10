# 离线运行说明

本项目地图数据已内嵌在 `index.html`，离线运行只缺一个文件：`echarts.min.js`。

## 你需要准备

1. 下载 `echarts@5.4.3` 的 `echarts.min.js`（任意可访问网络环境下下载）。
2. 把文件放到与 `index.html` 同一目录，文件名必须是：

```
echarts.min.js
```

## 启动方式

- 直接双击 `index.html`（`file://`）也可运行。
- 或本地静态服务器运行（推荐）：

```bash
python3 -m http.server 8000
```

然后打开 `http://localhost:8000`。
