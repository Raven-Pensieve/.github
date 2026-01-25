# Contributing to Raven-Pensieve | 贡献指南

[English](#english) | [中文](#中文)

---

## 中文

感谢你对 Raven-Pensieve 的关注！我们欢迎任何形式的贡献。本指南将帮助你了解如何参与我们的项目。

### 📋 目录

- [行为准则](#行为准则)
- [如何贡献](#如何贡献)
- [开发环境设置](#开发环境设置)
- [提交规范](#提交规范)
- [Pull Request 流程](#pull-request-流程)
- [代码风格](#代码风格)

### 行为准则

参与本项目即表示你同意遵守我们的 [行为准则](CODE_OF_CONDUCT.md)。请确保你的行为有助于营造一个友好、包容的社区环境。

### 如何贡献

#### 🐛 报告 Bug

在报告 Bug 之前，请：

1. **搜索现有 Issues** - 确保该问题尚未被报告
2. **更新到最新版本** - 确认问题在最新版本中仍然存在
3. **收集必要信息** - 包括：
   - Obsidian 版本
   - 插件版本
   - 操作系统
   - 复现步骤
   - 控制台错误日志（如有）

使用我们的 [Bug 报告模板](.github/ISSUE_TEMPLATE/bug_report.md) 提交问题。

#### 💡 功能建议

我们欢迎新功能的建议！在提交之前：

1. 确保该功能符合项目的定位和愿景
2. 检查是否已有类似的功能请求
3. 尽可能详细地描述功能的使用场景

使用我们的 [功能请求模板](.github/ISSUE_TEMPLATE/feature_request.md) 提交建议。

#### 📝 改进文档

文档贡献同样重要！你可以：

- 修复文档中的错误
- 添加缺失的说明
- 改进现有文档的清晰度
- 翻译文档

#### 🔧 提交代码

1. Fork 目标仓库
2. 创建你的功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m 'feat: add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

### 开发环境设置

#### 前置要求

- [Node.js](https://nodejs.org/) >= 18.0.0
- [pnpm](https://pnpm.io/) (推荐) 或 npm
- [Git](https://git-scm.com/)
- [Obsidian](https://obsidian.md/) (用于测试)

#### 快速开始

```bash
# 克隆仓库
git clone https://github.com/Raven-Pensieve/<repository-name>.git
cd <repository-name>

# 安装依赖
pnpm install

# 开发模式
pnpm dev

# 构建
pnpm build
```

#### 在 Obsidian 中测试

1. 在 Obsidian 中创建或打开一个测试 Vault
2. 创建 `.obsidian/plugins/<plugin-name>/` 目录
3. 将构建产物 (`main.js`, `manifest.json`, `styles.css`) 复制到该目录
4. 在 Obsidian 设置中启用插件

> 💡 **提示**: 可以使用符号链接简化开发流程

### 提交规范

我们使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

#### 类型 (Type)

| 类型       | 描述                            |
| ---------- | ------------------------------- |
| `feat`     | 新功能                          |
| `fix`      | Bug 修复                        |
| `docs`     | 文档更新                        |
| `style`    | 代码格式（不影响代码逻辑）      |
| `refactor` | 重构（既非新功能也非 Bug 修复） |
| `perf`     | 性能优化                        |
| `test`     | 测试相关                        |
| `chore`    | 构建过程或辅助工具的变动        |

#### 示例

```
feat(editor): add syntax highlighting for code blocks

- Support 10+ programming languages
- Add line number display option

Closes #123
```

### Pull Request 流程

1. **确保代码质量**
   - 运行 linter：`pnpm lint`
   - 运行测试：`pnpm test` (如适用)
   - 确保没有 TypeScript 错误

2. **更新文档**
   - 如果添加了新功能，更新相关文档
   - 更新 CHANGELOG（如果项目有的话）

3. **填写 PR 模板**
   - 详细描述你的更改
   - 关联相关的 Issue
   - 添加截图（如适用）

4. **等待审核**
   - 维护者会审查你的代码
   - 根据反馈进行必要的修改

### 代码风格

- **TypeScript** - 使用 TypeScript 编写代码
- **ESLint** - 遵循项目的 ESLint 配置
- **Prettier** - 使用 Prettier 格式化代码
- **命名规范**
  - 变量/函数：camelCase
  - 类/接口/类型：PascalCase
  - 常量：UPPER_SNAKE_CASE
  - 文件名：kebab-case 或 camelCase

---

## English

Thank you for your interest in Raven-Pensieve! We welcome contributions of all kinds. This guide will help you understand how to participate in our projects.

### 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Code Style](#code-style)

### Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please ensure your behavior contributes to a friendly, inclusive community.

### How to Contribute

#### 🐛 Reporting Bugs

Before reporting a bug:

1. **Search existing Issues** - Ensure the issue hasn't been reported
2. **Update to latest version** - Confirm the issue persists in the latest version
3. **Gather necessary information** - Including:
   - Obsidian version
   - Plugin version
   - Operating system
   - Steps to reproduce
   - Console error logs (if applicable)

Use our [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md) to submit issues.

#### 💡 Feature Requests

We welcome feature suggestions! Before submitting:

1. Ensure the feature aligns with the project's vision
2. Check if a similar request already exists
3. Describe the use case in as much detail as possible

Use our [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md) to submit suggestions.

#### 📝 Improving Documentation

Documentation contributions are equally important! You can:

- Fix errors in documentation
- Add missing explanations
- Improve clarity of existing docs
- Translate documentation

#### 🔧 Submitting Code

1. Fork the target repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Create a Pull Request

### Development Setup

#### Prerequisites

- [Node.js](https://nodejs.org/) >= 18.0.0
- [pnpm](https://pnpm.io/) (recommended) or npm
- [Git](https://git-scm.com/)
- [Obsidian](https://obsidian.md/) (for testing)

#### Quick Start

```bash
# Clone the repository
git clone https://github.com/Raven-Pensieve/<repository-name>.git
cd <repository-name>

# Install dependencies
pnpm install

# Development mode
pnpm dev

# Build
pnpm build
```

#### Testing in Obsidian

1. Create or open a test Vault in Obsidian
2. Create the `.obsidian/plugins/<plugin-name>/` directory
3. Copy build artifacts (`main.js`, `manifest.json`, `styles.css`) to that directory
4. Enable the plugin in Obsidian settings

> 💡 **Tip**: Use symbolic links to simplify the development workflow

### Commit Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

#### Types

| Type       | Description                           |
| ---------- | ------------------------------------- |
| `feat`     | New feature                           |
| `fix`      | Bug fix                               |
| `docs`     | Documentation updates                 |
| `style`    | Code formatting (no logic changes)    |
| `refactor` | Refactoring (neither feature nor fix) |
| `perf`     | Performance improvements              |
| `test`     | Test-related changes                  |
| `chore`    | Build process or tooling changes      |

#### Example

```
feat(editor): add syntax highlighting for code blocks

- Support 10+ programming languages
- Add line number display option

Closes #123
```

### Pull Request Process

1. **Ensure code quality**
   - Run linter: `pnpm lint`
   - Run tests: `pnpm test` (if applicable)
   - Ensure no TypeScript errors

2. **Update documentation**
   - Update relevant docs if adding new features
   - Update CHANGELOG (if the project has one)

3. **Fill out the PR template**
   - Describe your changes in detail
   - Link related Issues
   - Add screenshots (if applicable)

4. **Wait for review**
   - Maintainers will review your code
   - Make necessary changes based on feedback

### Code Style

- **TypeScript** - Write code in TypeScript
- **ESLint** - Follow project's ESLint configuration
- **Prettier** - Use Prettier for code formatting
- **Naming conventions**
  - Variables/functions: camelCase
  - Classes/interfaces/types: PascalCase
  - Constants: UPPER_SNAKE_CASE
  - File names: kebab-case or camelCase

---

<div align="center">

**感谢你的贡献！ | Thank you for your contribution!** 💖

</div>
