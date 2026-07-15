# 长沙历史步道 AI 智能体 GitHub Pages 部署包

这是可直接放入 GitHub 仓库根目录并通过 GitHub Pages 发布的网站文件。

## 文件结构

```text
index.html
404.html
.nojekyll
assets/
data/
```

## 最快发布步骤

1. 在 GitHub 新建一个仓库，例如 `changsha-historic-trail-ai`。
2. 把本压缩包解压后的所有文件上传到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 里选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. 保存后等待 1-3 分钟。
6. 网站地址通常是：

```text
https://你的GitHub用户名.github.io/changsha-historic-trail-ai/
```

如果仓库名是 `你的GitHub用户名.github.io`，则网站地址通常是：

```text
https://你的GitHub用户名.github.io/
```

## 注意

- GitHub Pages 在国内访问不保证稳定，但可作为免费备用入口。
- 本包使用相对路径，适合 GitHub Pages 的项目站点路径。
- `404.html` 已复制为首页内容，刷新子页面时也能回到应用界面。
