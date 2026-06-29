# HowToGetAlongWithGirls · 恋爱教练
<a href="https://linux.do" alt="LINUX DO"><img src="https://img.shields.io/badge/LINUX-DO-FFB003.svg?logo=data:image/svg%2bxml;base64,DQo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCIgaGVpZ2h0PSIxMDAiPjxwYXRoIGQ9Ik00Ni44Mi0uMDU1aDYuMjVxMjMuOTY5IDIuMDYyIDM4IDIxLjQyNmM1LjI1OCA3LjY3NiA4LjIxNSAxNi4xNTYgOC44NzUgMjUuNDV2Ni4yNXEtMi4wNjQgMjMuOTY4LTIxLjQzIDM4LTExLjUxMiA3Ljg4NS0yNS40NDUgOC44NzRoLTYuMjVxLTIzLjk3LTIuMDY0LTM4LjAwNC0yMS40M1EuOTcxIDY3LjA1Ni0uMDU0IDUzLjE4di02LjQ3M0MxLjM2MiAzMC43ODEgOC41MDMgMTguMTQ4IDIxLjM3IDguODE3IDI5LjA0NyAzLjU2MiAzNy41MjcuNjA0IDQ2LjgyMS0uMDU2IiBzdHlsZT0ic3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOmV2ZW5vZGQ7ZmlsbDojZWNlY2VjO2ZpbGwtb3BhY2l0eToxIi8+PHBhdGggZD0iTTQ3LjI2NiAyLjk1N3EyMi41My0uNjUgMzcuNzc3IDE1LjczOGE0OS43IDQ5LjcgMCAwIDEgNi44NjcgMTAuMTU3cS00MS45NjQuMjIyLTgzLjkzIDAgOS43NS0xOC42MTYgMzAuMDI0LTI0LjM4N2E2MSA2MSAwIDAgMSA5LjI2Mi0xLjUwOCIgc3R5bGU9InN0cm9rZTpub25lO2ZpbGwtcnVsZTpldmVub2RkO2ZpbGw6IzE5MTkxOTtmaWxsLW9wYWNpdHk6MSIvPjxwYXRoIGQ9Ik03Ljk4IDcwLjkyNmMyNy45NzctLjAzNSA1NS45NTQgMCA4My45My4xMTNRODMuNDI2IDg3LjQ3MyA2Ni4xMyA5NC4wODZxLTE4LjgxIDYuNTQ0LTM2LjgzMi0xLjg5OC0xNC4yMDMtNy4wOS0yMS4zMTctMjEuMjYyIiBzdHlsZT0ic3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOmV2ZW5vZGQ7ZmlsbDojZjlhZjAwO2ZpbGwtb3BhY2l0eToxIi8+PC9zdmc+" /></a>


一个 **AI 恋爱教练** 技能包——专为 Claude 等 AI 助手设计，提供结构化的两性社交分析与建议能力。

## 这是什么

这是一个完整的、可复用的 **dating-coach 技能**，包含：

- **方法论框架**：从吸引 → 平淡 → 暧昧 → 恋爱 → 长期相处的全周期路线图
- **聊天记录分析引擎**：逐条解读信号、识别废测、揪出错误、给出可复制的回复
- **两性知识库**：搭讪、聊天、约会、形象、废物测试、女性心理等主题
- **对象跟踪系统**：支持同时跟进多个对象，跨会话持续更新记录
- **隐私第一设计**：支持代号管理，个人数据与技能分离

## 目录结构

```
.claude/
├── commands/
│   └── coach.md              # Slash command 入口
└── skills/
    └── dating-coach/
        ├── SKILL.md           # 主技能定义（角色、流程、路由）
        ├── TESTPLAN.md        # 测试计划
        └── references/
            ├── chat-analysis.md    # 聊天记录分析方法论
            ├── knowledge-base.md   # 完整两性知识库
            ├── lifecycle.md        # 全周期路线图
            └── profile-template.md # 对象情况记录模板
```

## 快速上手

### 方式一：作为 Claude 项目技能

1. 将本仓库添加为 Claude 项目的知识库或技能目录
2. 在对话中使用 `/coach` 命令调用，或让 AI 自动识别到该技能
3. 粘贴聊天记录即可获得逐条分析 + 建议回复

### 方式二：嵌入你自己的 AI 项目

复制 `.claude/skills/dating-coach/` 目录到你的 AI 助手技能目录，按需调整。

## 核心功能

| 功能 | 说明 |
|------|------|
| 💬 **聊天分析** | 粘贴聊天记录，AI 逐条解读信号、指出用户错误、给可直接复制的话术 |
| 📊 **阶段诊断** | 帮你定位目前走到哪一步（吸引/平淡/暧昧/恋爱），给出下一步动作 |
| 📚 **知识问答** | 约会去哪、穿搭建议、如何搭讪、废测应对等具体问题 |
| 📝 **对象记录** | 用代号建档案，跨会话跟踪每个人的阶段、兴趣变化、时间线 |
| 🔄 **全局看板** | 同时跟进多人，一眼看清每个人的状态和趋势 |

## 使用要求

- **AI 助手**：支持 skills/playbook 机制的 Claude 或其他 AI 平台
- **隐私**：个人信息建议用代号，`profiles/` 目录不要提交到公开仓库

## License

MIT
