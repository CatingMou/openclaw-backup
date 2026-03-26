# OpenClaw 助手项目

> 一个基于 OpenClaw 的智能助手系统，专注于沟通需求管理、任务分解和项目协作。

## 📖 项目简介

这是一个个人 AI 助手项目，通过 OpenClaw 框架实现智能对话、任务管理和项目协作。项目包含完整的人设定义、工作流程、自动化文档和项目配置。

## ✨ 核心特性

- **智能对话** - 基于人设的友好、专业对话体验
- **任务管理** - 自动分解任务、分配执行
- **项目协作** - 支持多人协作和远程控制
- **自动化支持** - 提供多种自动化工具和技能
- **隐私保护** - 敏感信息本地管理，安全可靠

## 📁 项目结构

```
openclaw-backup/
├── README.md                    # 项目说明
├── AGENTS.md                    # 助手工作流和规范
├── SOUL.md                      # 人设定义
├── USER.md                      # 用户信息
├── MEMORY.md                    # 长期记忆
├── TOOLS.md                     # 工具说明
├── AUTOMATION.md                # 自动化文档
├── WECHAT_AUTOMATION_PLAN.md    # 微信自动化方案
├── 场景-反派AI查水表.md          # 场景文档
├── .gitignore                   # Git 忽略配置
├── .env.example                 # 环境变量模板
├── memory/                      # 会话记录（不提交）
└── .openclaw/                   # 本地配置（不提交）
```

## 🚀 快速开始

### 环境要求

- OpenClaw 框架
- Git
- Python 3.8+（可选，用于部分自动化功能）

### 安装步骤

1. **克隆仓库**

```bash
git clone https://github.com/CatingMou/openclaw-backup.git
cd openclaw-backup
```

2. **配置环境变量**

```bash
cp .env.example .env
# 编辑 .env 文件，填入你的配置
```

3. **启动 OpenClaw**

```bash
openclaw start
```

## 📚 文档说明

### 核心文档

- **[AGENTS.md](./AGENTS.md)** - 助手工作流和规范
  - 项目启动流程
  - 工作区管理
  - Memory 管理
  - 安全规范

- **[SOUL.md](./SOUL.md)** - 人设定义
  - 核心原则
  - 性格特点
  - 风格指南

- **[USER.md](./USER.md)** - 用户信息
  - 用户姓名
  - 时间区
  - 个人偏好

- **[MEMORY.md](./MEMORY.md)** - 长期记忆
  - 人设定义
  - 重要信息
  - 核心原则
  - 当前目标

### 功能文档

- **[AUTOMATION.md](./AUTOMATION.md)** - 自动化文档
  - OpenClaw 自动化能力
  - 技能使用指南
  - 最佳实践

- **[WECHAT_AUTOMATION_PLAN.md](./WECHAT_AUTOMATION_PLAN.md)** - 微信自动化方案
  - 技术可行性分析
  - 实现方案对比
  - 经验教训总结

### 工具文档

- **[TOOLS.md](./TOOLS.md)** - 本地工具说明
  - 技能使用
  - 配置管理
  - 本地笔记

## 🛠️ 使用指南

### 基本使用

1. 启动 OpenClaw 后，助手会自动读取 SOUL.md、USER.md、MEMORY.md 等文件
2. 在对话中提出你的需求，助手会根据人设和记忆提供帮助
3. 任务会自动记录到 MEMORY.md 和 memory/ 目录

### 常用命令

```bash
# 查看会话列表
openclaw sessions list

# 发送消息到指定会话
openclaw sessions send <session-key> "消息内容"

# 查看子代理状态
openclaw subagents list

# 执行健康检查
openclaw doctor
```

## 🎯 当前目标

**寻找能盈利的副业，要求：**
1. 两个人就可以实现的副业
2. 一个月至少盈利一千人民币以上

## 🔐 安全规范

- 敏感信息存储在 `.env` 文件中，已添加到 `.gitignore`
- `memory/` 目录包含会话记录，不提交到 Git
- `.openclaw/` 目录包含本地配置，不提交到 Git
- 遵循最小权限原则，不暴露不必要的敏感信息

## 📝 记录说明

### Daily Notes

`memory/YYYY-MM-DD.md` - 每日会话记录和任务总结

### Long-term Memory

`MEMORY.md` - 长期记忆，包含：
- 人设定义
- 重要信息
- 核心原则
- 决策记录
- 经验教训

## 🤝 贡献指南

本项目为个人项目，欢迎：
- 提出改进建议
- 分享使用经验
- 帮助完善文档

## 📄 许可证

本项目采用 [MIT License](LICENSE)

## 👤 作者

**CatingMou** - 项目维护者

## 📧 联系方式

- GitHub: https://github.com/CatingMou
- OpenClaw 文档: https://docs.openclaw.ai

## 🙏 致谢

- OpenClaw 框架团队
- 所有使用和测试过本项目的人

---

*最后更新: 2026-03-26*
