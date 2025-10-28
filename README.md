# Hosting Repository

本仓库用于托管各类静态资源，包括图片、幻灯片和其他媒体文件。

## 📁 仓库结构

```
hosting/
├── images/          # 图片资源
│   └── simple-cache/
├── slides/          # 幻灯片
│   ├── 国奖答辩/
│   └── 中国软件开源创新大赛/
├── LICENSE          # MIT许可证
└── README.md        # 本文件
```

## 🎯 用途

### 图片托管
- 存储各种项目相关的图片和图表
- 支持 SVG 等矢量图格式
- 通过 GitHub Actions 自动优化图片

### 幻灯片托管
- 存储演示文稿的 HTML 导出版本
- 支持离线浏览
- 包含竞赛答辩、奖学金答辩等场景的幻灯片

## 🚀 使用方法

### 访问资源

您可以通过以下方式访问托管的资源：

**直接访问原始文件**：
```
https://raw.githubusercontent.com/zrr1999/hosting/main/<path-to-file>
```

### 添加新资源

1. 将文件放入相应的目录（`images/` 或 `slides/`）
2. 提交并推送到仓库
3. GitHub Actions 会自动优化图片（如适用）

## 🤖 自动化

本仓库配置了以下 GitHub Actions 工作流：

- **图片优化**：自动压缩和优化 `images/` 目录中新添加的图片，减小文件大小
- **链接检查**：定期检查 Markdown 文件中的链接是否有效

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源许可证。

## 🔗 相关链接

- [GitHub Repository](https://github.com/zrr1999/hosting)
- [Issues](https://github.com/zrr1999/hosting/issues)

## 📝 贡献

欢迎提交 Issue 或 Pull Request 来改进本仓库。

---

*This repository is maintained by [@zrr1999](https://github.com/zrr1999)*
