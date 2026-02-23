# 上传到 GitHub 并在手机使用

## 第一步：创建 GitHub 仓库

1. 打开 [GitHub](https://github.com)，登录你的账号
2. 点击右上角 **+** → **New repository**
3. 填写：
   - **Repository name**：`kaleidoscope`（或任意名称）
   - **Description**：可选
   - 选择 **Public**
   - **不要**勾选 "Add a README file"
4. 点击 **Create repository**

## 第二步：推送代码到 GitHub

在终端中执行（把 `你的用户名` 和 `kaleidoscope` 换成你的）：

```bash
cd "d:\2025\Unit 4\cursor"

git remote add origin https://github.com/你的用户名/kaleidoscope.git
git branch -M main
git push -u origin main
```

如果首次使用，GitHub 会提示你登录或使用 Personal Access Token。

## 第三步：启用 GitHub Pages

1. 在 GitHub 打开你的仓库
2. 点击 **Settings** → 左侧 **Pages**
3. **Source** 选择 **Deploy from a branch**
4. **Branch** 选择 `main`，文件夹选择 `/ (root)`
5. 点击 **Save**

等待 1–2 分钟，Pages 部署完成后会显示：
`https://你的用户名.github.io/kaleidoscope/`

## 第四步：在手机上使用

1. 用手机浏览器（Chrome / Safari）打开上述地址
2. 点击进入「三棱镜万花筒」或「三角形镜片」
3. 点击「启动摄像头」
4. 允许摄像头权限
5. 将眼睛对准摄像头即可看到万花筒效果

> **说明**：摄像头需在 HTTPS 环境下使用，GitHub Pages 自动提供 HTTPS。
