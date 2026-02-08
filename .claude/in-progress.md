# 当前进行中的任务

## 当前 Sprint 目标

<!-- 填写当前迭代的目标 -->

## 进行中的任务

### [任务 ID] 任务名称

**状态**: 进行中
**优先级**: 高/中/低
**负责人**: [可选]

**描述**:
- 当前进度: [例如: 完成了模块开发，正在进行测试]
- 遇到的问题: [可选]
- 下一步: [具体行动]

**相关文件**:
- `src/superclaude/`
- `tests/`

---

## 待办事项

- [ ] 示例任务 1
- [ ] 示例任务 2
- [ ] 示例任务 3

## 阻塞问题

<!-- 列出当前阻碍开发的问题 -->

---

## 开发重点领域

### Python 开发
- **UV**: 所有 Python 操作使用 UV
- **Pytest**: 测试框架，支持 markers
- **Ruff**: 代码检查和格式化

### 核心模块
- **pytest_plugin**: 自动加载的 pytest 集成
- **pm_agent**: confidence, self_check, reflexion
- **execution**: parallel, reflection, self_correction
- **cli**: main, doctor, install_skill

### MCP 服务器
- **Gateway**: AIRIS MCP Gateway (推荐)
- **安装**: `superclaude mcp --servers airis-mcp-gateway`

### 命令
- `/pm`: 项目管理
- `/research`: 研究任务
- `/index-repo`: 仓库索引

---

## 项目资源

- [CLAUDE.md](../CLAUDE.md) - 完整配置指南
- [PLANNING.md](../PLANNING.md) - 架构和规则
- [KNOWLEDGE.md](../KNOWLEDGE.md) - 累积的洞察
- [AGENTS.md](../AGENTS.md) - 代理说明
