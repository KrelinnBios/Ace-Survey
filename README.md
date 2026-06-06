# Ace Survey（无性恋社群·基本信息调查问卷）

在线地址：<https://ace-survey.pages.dev/>

一个纯前端（单文件）问卷页面，用于收集无性恋谱系（ACE spectrum）相关的基本信息；支持自动保存填写进度，并可一键生成可分享的问卷卡片图片。

## 功能

- 单文件运行：仅需打开 `index.html`（或部署到任意静态托管）
- 自动保存：填写内容自动持久化到浏览器本地存储，避免误退出丢失
- 图片导出：使用 `html2canvas` 将问卷结果渲染为卡片长图，便于保存/转发
- 移动端兼容：针对部分移动端 WebView（如 QQ 内置浏览器）与 Firefox 导出渲染做了兼容处理

## 使用

- 本地使用：直接用浏览器打开 `index.html`
- 线上部署：将仓库内容部署到任意静态网站托管（Pages / Cloudflare Pages / Vercel 等）

## 许可（双许可）

本项目采用“代码”和“文档/站点内容”分离授权：

- Code：MIT License（见 [LICENSE](./LICENSE)）
- Documentation & Website Content：Creative Commons Attribution 4.0 International（CC BY 4.0，见 [LICENSE-CONTENT.md](./LICENSE-CONTENT.md)）

如果仓库中包含第三方资源（如字体、外部库等），其许可证以原作者声明为准。

