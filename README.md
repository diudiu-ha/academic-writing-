# IEEE TPE 投稿格式自查清单

依据 IEEE 官方 Word 模板《Preparation of Articles for IEEE TRANSACTIONS and JOURNALS (2022)》整理的投稿前格式自查清单，适用于 IEEE Transactions on Power Electronics (TPE) 等 IEEE 汇刊。

- 9 大模块，80+ 条检查项
- 含实测字号速查表（Title 24pt / 正文 10pt / 图题表题 8pt …）
- 可勾选，进度保存在浏览器 localStorage
- 纯静态单文件，无需构建，可直接双击打开或部署到任意静态托管

## 在线访问

GitHub Pages 地址：把本仓库 push 后，在 **Settings → Pages** 里选择 `Deploy from a branch` → 分支 `main` → 目录 `/ (root)`，即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 本地查看

直接双击 `index.html`，或：

```bash
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 自行部署到 GitHub Pages

```bash
git init
git add index.html README.md
git commit -m "Add IEEE TPE submission checklist"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
```

然后在仓库 Settings → Pages 开启即可。

## 检查项来源

字号与版式数据取自模板 `styles.xml` / `document.xml` 实测值；图片分辨率、色彩空间、图题表题位置等规则取自模板正文的 Graphics Preparation 章节。表格内字号（8 pt）为 IEEE 汇刊通行做法，非模板硬性规定；若目标期刊的 Information for Authors 有特别条款，以期刊主页为准。
