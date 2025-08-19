# GitHub Pages 部署说明

## 部署步骤

1. 将生成的静态文件推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 "GitHub Actions" 作为构建源
4. 推送代码会自动触发部署

## 文件结构

```
public/pages/
├── index.html          # 首页
├── styles.css          # 样式文件
└── *.html             # 各个页面
```

## 自定义域名

在 `public/pages/` 目录下创建 `CNAME` 文件，内容为你的域名：

```
your-domain.com
```

生成时间: 2025/8/19 19:49:44
