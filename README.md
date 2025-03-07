# Blinko Image Compressor

一个自动压缩上传图片的Blinko插件，帮助节省存储空间和带宽。

## 功能特点

- 自动压缩上传的图片
- 支持JPG、PNG、WebP和GIF格式
- 可调节压缩质量和最大尺寸
- 适用于所有主流平台和浏览器
- 支持Android、iOS、Windows、Linux、Mac
- 兼容Chrome、Firefox、Safari等浏览器

## 安装方法

1. 在Blinko中打开设置
2. 点击"插件设置"
3. 切换到"本地开发"标签
4. 点击"添加本地插件"按钮
5. 输入WebSocket URL:
   - 本地: `ws://localhost:8080`
   - 网络: `ws://<your-local-ip>:8080`
   - Ngrok: `wss://xxxx-xx-xx-xxx-xx.ngrok.io`（如果使用ngrok）
6. 点击"连接"开始使用插件

## 使用方法

安装插件后，所有上传的图片将自动进行压缩。您可以通过以下方式查看和调整压缩设置：

1. 点击工具栏中的图片压缩图标
2. 查看当前压缩设置
3. 点击"压缩设置"按钮打开设置面板
4. 调整压缩质量和最大尺寸
5. 启用或禁用自动压缩功能

> **注意**: 插件设置项在编辑界面处，您可以通过点击界面上的图片编辑图标来快速访问设置面板。

## 压缩设置

- **图片质量**：调整压缩质量（10%-100%）
- **最大宽度**：设置图片的最大宽度（像素）
- **最大高度**：设置图片的最大高度（像素）
- **启用自动压缩**：开启或关闭自动压缩功能

## 开发

### 安装依赖

```bash
bun install
```

### 启动开发服务器

```bash
bun dev
```

### 构建发布版本

```bash
bun run release:publish
```

## 许可证

MIT