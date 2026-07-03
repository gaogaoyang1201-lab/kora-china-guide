# KORA 中文介绍页

这是一个静态单页网站，用中文说明：

- KORA 是什么
- 适合谁
- 怎么通过 `@Kora_china_bot` 开始体验
- 使用时的注意事项

## 本地打开

直接双击 `index.html` 即可，或在当前目录运行：

```powershell
python -m http.server 4173
```

然后访问 `http://127.0.0.1:4173/`。

## 部署

这是纯静态页面，`index.html` 和 `styles.css` 直接部署到任意静态托管即可。

### GitHub Pages

1. 新建仓库
2. 上传 `index.html` 和 `styles.css`
3. 在仓库 `Settings -> Pages` 中选择从默认分支发布

### Vercel

1. 新建项目
2. 导入当前目录
3. 识别为 Other / Static
4. 直接部署

## 打包文件

仓库中已包含 `kora-site.zip`，可直接上传到静态托管平台。
