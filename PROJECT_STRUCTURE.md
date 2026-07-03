# 外贸AI系统 - 项目结构规范

## 1. 总体结构原则

所有工作必须按照“模块化 + 可复用 + 可迁移”原则组织。

---

## 2. 标准目录结构

Workspace（逻辑结构）对应 GitHub 仓库结构如下：

├── 00_RULES
│   ├── AI_GLOBAL_RULES.md
│   ├── PROJECT_STRUCTURE.md
│   ├── NAMING_RULES.md（后续创建）
│
├── 01_PERSONAL_CORE
│   ├── SOP（通用流程）
│   ├── PROMPTS（提示词库）
│   ├── METHODS（方法论）
│
├── 02_PROJECTS
│   ├── CustomerDevelopment（客户开发项目）
│   ├── PricingSystem（报价系统）
│   ├── LogisticsSystem（物流系统）
│
├── 03_AGENTS
│   ├── CustomerAgent.md
│   ├── PricingAgent.md
│   ├── EmailAgent.md
│
├── 04_TEMPLATES
│   ├── SOP模板.md
│   ├── Prompt模板.md
│   ├── 报价模板.md
│
├── 05_LOGS
│   ├── 踩坑日志.md
│   ├── 决策记录.md
│
└── README.md

---

## 3. 项目创建规则

每一个新项目必须满足：

- 必须有README
- 必须有SOP
- 必须有输入输出说明
- 必须有记录机制

---

## 4. Agent设计规则

每一个Agent必须：

- 只做一个任务
- 输入清晰
- 输出结构化
- 可复用
- 可独立运行

---

## 5. 重要原则

- 不允许“临时逻辑”
- 不允许“口头流程”
- 所有流程必须文档化
- 所有优化必须更新结构

---

## 6. 目标

构建一个可复制、可扩展、可迁移的外贸AI操作系统。
