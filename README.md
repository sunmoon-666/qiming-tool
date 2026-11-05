# 起名工坊

新生儿中文起名工具 · 纯前端单页应用，零依赖，可直接在 Vercel 静态部署。

## 功能

- 输入姓氏，按性别 / 名长 / 五行偏好筛选
- 随机生成 6 个名字建议，展示每个字的拼音、五行与字义
- 收藏心仪的名字（本地保存），支持一键复制

## 部署到 Vercel

1. 将本仓库导入 Vercel（Import Git Repository）
2. 框架选择 **Other**，构建命令留空，输出目录留空
3. 由于 `index.html` 位于仓库根目录，Vercel 会自动将其作为首页部署

部署完成后，访问 `https://<project>.vercel.app` 即可使用。

## 本地运行

直接双击 `index.html` 或用任意静态服务器打开即可：

```bash
python3 -m http.server 8080
```

然后访问 `http://localhost:8080`。
