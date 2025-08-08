---
title: "AI 命令行工具汇总"
tags: [
    "ai",
    "cli",
]
date: "2025-08-07"
categories: [
    "ai",
]
menu: "main"
---
## AI工具&特点

> 市面上好用的AI cli 工具, 汇总一下

## cli 工具

| name        | link                                               | usage  |
| ----------- | -------------------------------------------------- | ------ |
| claude code | `npm install -g @anthropic-ai/claude-code`         | claude |
| qwen code   | `npm install -g @qwen-code/qwen-code`              | qwen   |
| gemini  cli | `npm install -g @google/gemini-cli`                | gemini |
| crush       | `go install github.com/charmbracelet/crush@latest` | crush  |

### Gemini

> Google 的 AI cli工具,基于`Gemini 2.5 Pro`,可以生成图片, 视频, 音频, 文本等
> 每天可以免费使用1000次请求, 每分钟60次

```bash
# 全局安装（推荐）
npm install -g @google/gemini-cli
# 或者直接用 npx 运行，免安装
npx https://github.com/google-gemini/gemini-cli
```

- 提示词例子

> 我想让你帮我完成一个任务，但在开始前，请你先熟悉我的项目。
>
> 1. 技术栈和依赖：`@package.json`
> 2. 开发规范：`@CONTRIBUTING.md`
> 3. 目录结构规范：`@docs/directory-spec.md`
> 4. 工具函数：`@src/utils/`
>
> 阅读后请总结一下这个项目的核心技术栈和主要开发规则

