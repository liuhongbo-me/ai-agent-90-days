# AI Agent 90 Days

一个面向实践的 90 天 AI Agent 学习仓库。

目标不是收藏资料，而是每天沉淀可以运行、可以复盘、可以继续扩展的代码、笔记和小项目。

## 学习路线

| 阶段 | 天数 | 主题 | 主要产物 |
| --- | --- | --- | --- |
| Phase 01 | Day 1-15 | Python 基础与工程习惯 | 命令行脚本、函数、模块、文件处理 |
| Phase 02 | Day 16-30 | LLM 与 OpenAI API | Chatbot、结构化输出、流式响应 |
| Phase 03 | Day 31-45 | Agent 基础 | 记忆、规划、工具调用雏形 |
| Phase 04 | Day 46-60 | Tools / Function Calling / MCP | 可扩展工具 Agent、MCP 示例 |
| Phase 05 | Day 61-75 | LangChain / LangGraph | 多步骤工作流、状态图、可观测 Agent |
| Phase 06 | Day 76-90 | 完整 Agent 项目 | RAG Agent、工具 Agent、最终项目 |

## 仓库结构

```text
ai-agent-90-days/
├── docs/                         # 总路线、学习笔记
├── phase-01-python/              # Day 1-15
├── phase-02-llm/                 # Day 16-30
├── phase-03-agent-basics/        # Day 31-45
├── phase-04-tools-mcp/           # Day 46-60
├── phase-05-langchain-langgraph/ # Day 61-75
├── phase-06-agent-projects/      # Day 76-90
└── projects/                     # 阶段项目与最终项目
```

## 使用方式

1. 每天进入当天目录，阅读 `README.md`。
2. 完成当天的代码练习。
3. 把关键理解补充到 `docs/` 对应笔记中。
4. 阶段结束后，用 `projects/` 里的项目做一次整合。

## 本地环境

建议使用 Python 3.11+。

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

复制环境变量模板：

```powershell
Copy-Item .env.example .env
```
