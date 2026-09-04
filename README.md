# Hosting

静态资源托管仓库：图片、幻灯片导出等资源统一放在仓库根目录下。

- 原始文件：<https://raw.githubusercontent.com/zrr1999/hosting/main/>
- 仓库：<https://github.com/zrr1999/hosting>

## 用途

### 图片

- 存放项目相关图片与图表
- 支持 SVG 等矢量格式
- 统一放在顶层 `images/` 下，按项目或主题继续分目录，例如 `images/blog/simple-cache/`
- `images/profile/` 用于跨平台头像与标识，按身份组织为 `images/profile/<identity>/`
- 每个身份目录统一提供 `avatar.png`（1024×1024，全尺寸）和 `icon.png`（256×256，为浏览器标签、小徽标等小尺寸场景优化构图）
- 当前身份包括 `personal/`、`zendev-lab/` 和 `morirun/`
- 通过 GitHub Actions 自动优化 `images/` 中的图片

### 幻灯片

- 存放演示文稿的 HTML 导出版本，可离线浏览
- 统一放在顶层 `slides/` 下，按主题继续分目录
- 当前 deck 位于 `slides/open-source-innovation/` 与 `slides/national-scholarship/`，每套 deck 内包含自己的 `assets/` 与 `lib/`

## 使用方法

### 访问资源

直接访问 Raw：

```
https://raw.githubusercontent.com/zrr1999/hosting/main/<path-to-file>
```

### 添加资源

1. 将文件放入 `images/`、`slides/` 等对应目录
2. 提交并推送到 `main`
3. 若为图片，Actions 会在适用时自动优化

## 自动化

- **图片优化**：压缩 `images/` 中新变更的图片（不处理 `slides/`）
- **链接检查**：定期检查 Markdown 中的外链是否有效

## 许可证

以 [GNU GPL v3](./LICENSE) 授权。

## 相关链接

- [GitHub 仓库](https://github.com/zrr1999/hosting)
- [Issues](https://github.com/zrr1999/hosting/issues)
