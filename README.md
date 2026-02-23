# 万花筒 Kaleidoscope

使用摄像头实现的万花筒交互效果，支持手机浏览器访问。

## 在线体验

在 GitHub 启用 Pages 后，访问：
`https://你的用户名.github.io/仓库名/`

## 本地运行

```bash
# 使用 Python
python -m http.server 8080

# 或使用 Node.js
npx serve .
```

然后访问 `http://localhost:8080`（需 HTTPS 或 localhost 才能使用摄像头）

## 版本说明

- **kaleidoscope-self.html** - 三棱镜式万花筒：迭代镜面反射、管道深度透视
- **kaleidoscope.html** - 三角形镜片万花筒：等边三角形镶嵌、眼睛区域反射

## 手机使用

1. 将项目部署到 GitHub Pages
2. 在手机浏览器打开 Pages 地址（需 HTTPS）
3. 点击「启动摄像头」并允许权限
4. 将眼睛对准摄像头区域即可看到效果
