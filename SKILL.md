---
name: build-your-own-x
description: "通过从零重建你热爱的技术来掌握编程。基于 GitHub 529K+ star 项目 codecrafters-io/build-your-own-x，收录 30+ 个技术领域的 200+ 篇「从零构建」教程，涵盖 3D 渲染器、AI 模型、区块链、数据库、Docker、游戏引擎、Git、操作系统、编程语言、神经网络、Shell、Web 服务器等。触发词：从零实现/构建/重建/造轮子、build your own、byox、手写、learn by building。"
compatibility:
  - http_request: 访问教程链接内容
  - web_access: 浏览教程网页
  - command_line: 克隆代码仓库、本地实操
---

# Build Your Own X — 从零构建一切

> "What I cannot create, I do not understand." — Richard Feynman

基于 [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)（529K+ ⭐），这是一份精心整理的教程合集，教你从零重建我们热爱的各种技术。

## When to Use

当用户说以下任意内容时触发本 Skill：

- "我想从零实现一个 XXX"
- "怎么手写/手搓一个 XXX"
- "有没有教你自己写 XXX 的教程"
- "想理解 XXX 底层原理"
- "build your own XXX"
- "造一个 XXX 轮子"
- "不用框架/库，纯手写 XXX"

## Not For

- 已有现成框架/库的简单使用教程 → 直接教用
- 纯粹的理论原理讲解（不涉及动手写代码）
- 已有的单独教程（本 Skill 提供的是索引和引导）

---

## 工作流程

### 第 1 步：确认用户想构建什么

问清楚：
- 想构建什么技术？（数据库、游戏、OS、语言……）
- 用什么语言？（Python、Go、Rust、C、JS……）
- 时间预算？（一小时周末项目 vs. 深入多周学习）
- 要最简实现(< 500 行)还是完整实现？

### 第 2 步：匹配教程

从下方教程索引中找到最佳匹配。优先匹配**语言 + 难度 + 技术领域**。

### 第 3 步：引导实操

- 用 `visit_web` 打开教程链接，提取核心步骤
- 用终端或代码执行工具帮助用户开始写代码
- 如果教程有 GitHub 仓库，用 `git clone` 拉取
- 逐步引导，每步验证编译/运行

---