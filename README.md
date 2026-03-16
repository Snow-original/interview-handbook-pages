# interview-handbook-pages

这个目录已经可以直接用于 GitHub Pages 发布。

## 本地已完成

- 页面入口文件：`index.html`
- 本地 Git 仓库：已初始化
- GitHub Pages 兼容：已准备

## 推送到 GitHub

先在 GitHub 上新建一个空仓库，例如：`interview-handbook-pages`

然后在这个目录执行：

```bash
git add .
git commit -m "init github pages site"
git branch -M main
git remote add origin 你的仓库地址
git push -u origin main
```

仓库地址示例：

- HTTPS: `https://github.com/你的用户名/interview-handbook-pages.git`
- SSH: `git@github.com:你的用户名/interview-handbook-pages.git`

## 开启 GitHub Pages

进入 GitHub 仓库页面：

1. Settings
2. Pages
3. Build and deployment -> Source 选择 `Deploy from a branch`
4. Branch 选择 `main`，目录选择 `/root`
5. 保存

几分钟后，页面通常会出现在：

`https://你的用户名.github.io/interview-handbook-pages/`
