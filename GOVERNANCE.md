# Governance | 治理文档

[English](#english) | [中文](#中文)

---

## 中文

本文档描述了 Raven-Pensieve 组织的治理结构和决策流程。

### 🏛️ 组织结构

#### 核心维护者 (Core Maintainers)

核心维护者是组织的主要决策者，负责：

- 制定项目的技术方向和优先级
- 审核和合并 Pull Request
- 管理发布流程
- 解决社区争议

当前核心维护者：

| 成员          | GitHub                                             | 角色                    |
| ------------- | -------------------------------------------------- | ----------------------- |
| RavenHogWarts | [@RavenHogWarts](https://github.com/RavenHogWarts) | 组织创始人 & 主要维护者 |

#### 贡献者 (Contributors)

任何向组织项目提交过被接受的贡献的人都被视为贡献者。贡献者可以：

- 提交 Issue 和 Pull Request
- 参与讨论
- 帮助其他用户

#### 社区成员 (Community Members)

使用我们项目的所有人都是社区成员。我们重视每一位成员的反馈和建议。

### 📜 决策流程

#### 日常决策

- **Bug 修复**: 任何维护者可以独立审核和合并
- **小型功能**: 需要至少一位维护者的批准
- **文档更新**: 任何维护者可以独立合并

#### 重大决策

对于影响项目方向的重大决策，我们遵循以下流程：

1. **提案** - 通过 Issue 或 Discussion 提出
2. **讨论** - 开放给所有社区成员参与
3. **共识** - 寻求大多数核心维护者的同意
4. **执行** - 由指定维护者负责实施

重大决策包括但不限于：

- 重大架构变更
- 新项目的创建
- 废弃现有功能
- 更改许可证

### 🔄 版本发布

我们遵循 [语义化版本](https://semver.org/lang/zh-CN/) 规范：

- **主版本 (Major)** - 不兼容的 API 变更
- **次版本 (Minor)** - 向后兼容的功能新增
- **修订版本 (Patch)** - 向后兼容的问题修复

发布流程：

1. 更新 CHANGELOG
2. 更新版本号 (`manifest.json`, `package.json`)
3. 创建 Git Tag
4. 发布 GitHub Release
5. 更新文档（如需要）

### 🌱 成为维护者

我们欢迎活跃的贡献者成为维护者。成为维护者的一般路径：

1. 持续为项目做出高质量的贡献
2. 积极参与社区讨论和 Issue 处理
3. 展示对项目愿景的理解
4. 获得现有核心维护者的提名
5. 通过核心维护者的一致同意

### ⚖️ 争议解决

当出现分歧时：

1. **首先** - 尝试在相关 Issue/PR 中进行建设性讨论
2. **其次** - 如果无法达成共识，提请核心维护者介入
3. **最后** - 由组织创始人做出最终决定

### 📝 文档更新

本治理文档会根据组织发展进行更新。任何重大更改都会：

1. 通过 Pull Request 提出
2. 开放社区讨论期（至少 7 天）
3. 需要核心维护者的一致同意

---

## English

This document describes the governance structure and decision-making processes of the Raven-Pensieve organization.

### 🏛️ Organizational Structure

#### Core Maintainers

Core maintainers are the primary decision-makers of the organization, responsible for:

- Setting technical direction and priorities
- Reviewing and merging Pull Requests
- Managing release processes
- Resolving community disputes

Current core maintainers:

| Member        | GitHub                                             | Role                                   |
| ------------- | -------------------------------------------------- | -------------------------------------- |
| RavenHogWarts | [@RavenHogWarts](https://github.com/RavenHogWarts) | Organization Founder & Lead Maintainer |

#### Contributors

Anyone who has submitted an accepted contribution to organization projects is considered a contributor. Contributors can:

- Submit Issues and Pull Requests
- Participate in discussions
- Help other users

#### Community Members

Everyone using our projects is a community member. We value feedback and suggestions from all members.

### 📜 Decision Making Process

#### Routine Decisions

- **Bug fixes**: Any maintainer can independently review and merge
- **Small features**: Require approval from at least one maintainer
- **Documentation updates**: Any maintainer can independently merge

#### Major Decisions

For major decisions affecting project direction, we follow this process:

1. **Proposal** - Submit via Issue or Discussion
2. **Discussion** - Open to all community members
3. **Consensus** - Seek agreement from majority of core maintainers
4. **Execution** - Assigned maintainer responsible for implementation

Major decisions include but are not limited to:

- Significant architectural changes
- Creation of new projects
- Deprecation of existing features
- License changes

### 🔄 Release Process

We follow [Semantic Versioning](https://semver.org/):

- **Major** - Incompatible API changes
- **Minor** - Backward-compatible new features
- **Patch** - Backward-compatible bug fixes

Release workflow:

1. Update CHANGELOG
2. Update version numbers (`manifest.json`, `package.json`)
3. Create Git Tag
4. Publish GitHub Release
5. Update documentation (if needed)

### 🌱 Becoming a Maintainer

We welcome active contributors to become maintainers. The typical path:

1. Consistently make high-quality contributions
2. Actively participate in community discussions and Issue handling
3. Demonstrate understanding of project vision
4. Receive nomination from existing core maintainers
5. Gain unanimous approval from core maintainers

### ⚖️ Conflict Resolution

When disagreements arise:

1. **First** - Attempt constructive discussion in the relevant Issue/PR
2. **Then** - If consensus cannot be reached, escalate to core maintainers
3. **Finally** - Organization founder makes the final decision

### 📝 Document Updates

This governance document will be updated as the organization evolves. Any major changes will:

1. Be proposed via Pull Request
2. Have an open community discussion period (at least 7 days)
3. Require unanimous approval from core maintainers

---

<div align="center">

*最后更新 | Last Updated: 2026-01*

</div>
