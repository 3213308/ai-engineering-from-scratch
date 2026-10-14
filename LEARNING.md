# 我的 AI 工程学习路线

## 学习目标
从事ai智能体开发与ai应用开发。最终作品暂不确定。

## 水平测评
- 日期：2026-10-14
- 得分：7/10。数学与统计 2/2；传统机器学习 1/2；深度学习 0/2；自然语言处理与 Transformer 2/2；AI 应用 2/2。
- 规则对应入口：第 7 阶段，深入理解 Transformer。
- 实际学习起点：软件工程基础路线；下一课是 Git 与协作。
- 调整原因：2026-10-14 用户要求选择最贴合职业目标的路线，现选择智能体系统工程作为主路线，先完成共享基础。
- 节奏：尽可能快地学习；尚未指定每周小时数。

## 学习路线

职业主路线：智能体系统工程。按以下项目官方路线顺序学习：

1. 软件工程基础：learning-paths/software-engineering-fundamentals.json。
2. AI 应用构建与部署：learning-paths/building-and-deploying-ai-applications.json。
3. 智能体系统工程：learning-paths/agentic-ai-engineer.json。

遵循各 JSON 清单的 order 字段，不按全课程阶段号顺序推进。重复课程只学习和记录一次，但需要把所学应用到同一个项目。每课开始前检查原文中的前置知识；基础不足时补项目中的相关课程，特别是第 0 阶段第 13 课的 Python 基础。
已完成的环境入门和测验记录保持不变；uv 复习仍待完成。下一课：phases/00-setup-and-tooling/02-git-and-collaboration。
目标作品：可调用工具的任务助手，逐步加入状态、记忆、权限边界、失败恢复、评估与运行追踪；具体任务场景后续确定。
路线时长仅是课文估计，不含前置知识补课、独立实现、作品迭代与复习。

### 有序课程清单

1. phases/00-setup-and-tooling/01-dev-environment
2. phases/00-setup-and-tooling/02-git-and-collaboration
3. phases/00-setup-and-tooling/06-python-environments
4. phases/00-setup-and-tooling/07-docker-for-ai
5. phases/00-setup-and-tooling/09-data-management
6. phases/00-setup-and-tooling/10-terminal-and-shell
7. phases/00-setup-and-tooling/12-debugging-and-profiling
8. phases/13-tools-and-protocols/01-the-tool-interface
9. phases/13-tools-and-protocols/05-tool-schema-design
10. phases/14-agent-engineering/38-verification-gates
11. phases/17-infrastructure-and-production/20-shadow-canary-progressive
12. phases/17-infrastructure-and-production/25-security-secrets-audit
13. phases/17-infrastructure-and-production/23-sre-for-ai
14. phases/11-llm-engineering/01-prompt-engineering
15. phases/11-llm-engineering/03-structured-outputs
16. phases/11-llm-engineering/04-embeddings
17. phases/11-llm-engineering/05-context-engineering
18. phases/11-llm-engineering/06-rag
19. phases/11-llm-engineering/10-evaluation
20. phases/11-llm-engineering/11-caching-cost
21. phases/11-llm-engineering/12-guardrails
22. phases/11-llm-engineering/13-production-app
23. phases/17-infrastructure-and-production/13-llm-observability
24. phases/13-tools-and-protocols/06-mcp-fundamentals
25. phases/14-agent-engineering/01-the-agent-loop
26. phases/14-agent-engineering/06-tool-use-and-function-calling
27. phases/14-agent-engineering/07-memory-virtual-context-memgpt
28. phases/14-agent-engineering/13-langgraph-stateful-graphs
29. phases/14-agent-engineering/28-orchestration-patterns
30. phases/14-agent-engineering/26-failure-modes-agentic
31. phases/14-agent-engineering/27-prompt-injection-defense
32. phases/14-agent-engineering/30-eval-driven-agent-development
33. phases/14-agent-engineering/29-production-runtimes
34. phases/14-agent-engineering/24-agent-observability-platforms

## 学习记录
| 日期 | 课程 | 测验 | 备注 |
|---|---|---|---|
| 2026-10-14 | 入门测评 | 7/10 | 已完成；课程尚未标记完成 |
| 2026-10-14 | 00-setup-and-tooling/01-dev-environment | 2/3 | 已创建并激活虚拟环境，验证 pip、NumPy 点积与入门检查；uv 职责需要复习。后续工具及扩展练习尚未执行。 |

## 待复习内容
- Python 基础：表达式、变量、列表、字典、条件、循环与函数。
- 开发环境：用户终端已成功创建并激活虚拟环境；pip 路径正确，NumPy 2.5.4 导入成功，入门检查 2/2 通过。此前虚拟环境创建失败已不再复现。
- 机器学习：超参数与训练得到的参数的区别。
- 深度学习：链式法则、反向传播、梯度与残差连接。


- 第 0 阶段第 1 课复习：uv 用于管理 Python 环境、安装包和解析依赖，不是 CUDA 编译器；课后测验 2/3，低于 70%。


