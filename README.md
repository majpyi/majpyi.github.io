# majpyi.github.io

我的个人网站源码，纯 HTML/CSS，通过 GitHub Pages 部署。

- 线上地址：https://majpyi.github.io
- 技术：无构建工具，直接 `index.html` + `style.css`

## 本地预览

直接用浏览器打开 `index.html`，或起一个静态服务器：

```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 部署

推送到 GitHub 上名为 `majpyi.github.io` 的仓库后，在
Settings → Pages 中把 Source 设为 `main` 分支根目录即可，
几分钟后访问 https://majpyi.github.io 生效。

## 待替换内容

- `your-email@example.com` → 真实邮箱
- 作品集 / 博客中的占位项目和文章
