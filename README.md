# 日本語文章解析文档

这是 [japanese-analyzer](https://github.com/cokice/japanese-analyzer) 的 Mintlify 文档站源码。

文档包括：

- 产品介绍与本地快速开始
- 使用指南：句子解析、单词详解与多词圈选、今日一句、图片识别、朗读、AI 日语助手和设置
- 环境变量、模型服务商、访问密码与 Umami 配置
- Vercel、Docker Compose、docker run 部署，以及让 AI Agent 部署
- 密钥与隐私说明
- 开发命令、项目结构、CI 与镜像发布、内部 API
- 常见问题与许可证

文档与应用一样提供四种语言：

| 语言 | 目录 | Mintlify 语言代码 |
| --- | --- | --- |
| 简体中文（默认） | 根目录 | `zh-Hans` |
| 繁體中文 | `zh-Hant/` | `zh-Hant` |
| English | `en/` | `en` |
| 한국어 | `ko/` | `ko` |

修改任意页面时，请同步更新其他三种语言的对应页面，并在 `docs.json` 的 `navigation.languages` 中保持导航一致。

## 本地预览

安装 Mintlify CLI：

```bash
npm i -g mint
```

在仓库根目录启动预览：

```bash
mint dev
```

然后打开 `http://localhost:3000`。

## 验证

```bash
mint validate
mint broken-links
```
