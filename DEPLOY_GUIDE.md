# 🚀 部署到 GitHub Pages 指南

## 第一步：创建 GitHub 仓库

1. 访问 https://github.com/new
2. 填写仓库信息：
   - **Repository name**: `fantasy-species-quiz`（或任何你喜欢的名字）
   - **Description**: `🔮 奇幻物种测定仪 - 发现你的神秘物种`
   - **Public**（必须是公开的，才能使用 GitHub Pages）
   - **不要**勾选 "Initialize this repository with a README"
3. 点击 **Create repository**

## 第二步：推送代码到 GitHub

复制 GitHub 上显示的仓库 URL，然后在终端运行以下命令：

```bash
# 添加远程仓库（替换为你的实际仓库地址）
git remote add origin https://github.com/ajkdfe2e2e/fantasy-species-quiz.git

# 推送代码
git push -u origin main
```

## 第三步：启用 GitHub Pages

1. 在 GitHub 仓库页面，点击 **Settings**（设置）
2. 在左侧菜单找到 **Pages**
3. 在 **Source** 下选择：
   - Branch: `main`
   - Folder: `/ (root)`
4. 点击 **Save**
5. 等待 1-2 分钟，页面会显示：
   ```
   Your site is published at https://ajkdfe2e2e.github.io/fantasy-species-quiz/
   ```

## 🎉 完成！

访问你的网站：**https://ajkdfe2e2e.github.io/[你的仓库名]/**

## 📝 快速命令（一键复制）

创建仓库后，运行以下命令（记得替换仓库名）：

```bash
git remote add origin https://github.com/ajkdfe2e2e/fantasy-species-quiz.git
git push -u origin main
```

## 🔄 后续更新

如果你修改了代码，使用以下命令更新：

```bash
git add .
git commit -m "更新描述"
git push
```

稍等片刻，GitHub Pages 会自动更新。

---

💡 **提示**: 如果推送失败，可能需要配置 Git 身份验证。建议使用 Personal Access Token。


