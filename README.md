# Awesome AI Skills

> 中文：AI 技能与项目精选目录  
> English: A curated catalog of AI skills, agent projects, workflows, and developer tools.

Awesome AI Skills is a bilingual knowledge base maintained by SunyataAI. It collects high-quality open source repositories and practical projects around AI skills, agents, MCP, automation workflows, developer tooling, and applied AI products.

本仓库由 SunyataAI 维护，目标是持续收集、介绍、解读和分类整理市面上优秀的 AI Skills、Agent 项目、MCP 工具、自动化工作流、开发者工具和应用型 AI 项目，方便公开分享，也方便团队日常查找和研究。

## About SunyataAI / 关于 SunyataAI

SunyataAI is building an open AI community for the next generation of human-agent collaboration. It is a place for creators, developers, researchers, and intelligent agents to share knowledge, discover tools, connect real needs, and shape how AI becomes part of everyday creation and work.

SunyataAI 正在建设面向下一代人机协作的开放式 AI 社区。我们希望让创作者、开发者、研究者和智能 Agent 在这里共享知识、发现工具、连接真实需求，并共同塑造 AI 进入日常创造与工作的方式。

Website / 官网: [sunyataai.com](https://sunyataai.com)<br>
Contact / 联系方式: [sunyataai@outlook.com](mailto:sunyataai@outlook.com)

## What We Collect / 收录范围

- AI skills, agent skills, prompt/programmatic workflows
- Agent frameworks and multi-agent orchestration projects
- MCP servers, clients, tools, and integration examples
- AI developer tools, CLIs, SDKs, evaluation tools, and observability projects
- Practical AI applications with reusable architecture or workflow value
- High-quality learning resources related to AI agents and AI-native software

## Categories / 分类

| Category | 中文说明 | English Description |
| --- | --- | --- |
| `skills` | AI 技能、任务模板、可复用工作流 | Reusable AI skills, task recipes, and workflows |
| `agents` | Agent 框架、多 Agent 协作、任务执行系统 | Agent frameworks, multi-agent systems, and task runners |
| `mcp` | MCP server/client、工具接入、协议示例 | MCP servers, clients, integrations, and protocol examples |
| `developer-tools` | CLI、SDK、调试、评估、可观测性工具 | CLIs, SDKs, debugging, evaluation, and observability tools |
| `applications` | 有参考价值的 AI 应用项目 | Practical AI applications with reusable ideas |
| `research-learning` | 论文、教程、课程、案例研究 | Papers, tutorials, courses, and case studies |

## Featured Index / 精选索引

The first public version starts with a small structured seed list. More entries will be added after review.

首版先建立结构和少量示例条目，后续按标准持续补充。

| Project | Category | Tags | Why It Matters |
| --- | --- | --- | --- |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | `mcp` | MCP, integrations, tools | Reference MCP server implementations and common integrations. |
| [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | `developer-tools` | examples, recipes, SDK | Practical examples for building with OpenAI APIs and AI workflows. |
| [microsoft/autogen](https://github.com/microsoft/autogen) | `agents` | multi-agent, orchestration | A widely referenced framework for building multi-agent applications. |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | `agents` | agents, workflow | A popular project for role-based agent workflow orchestration. |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | `developer-tools` | framework, integrations | Broad ecosystem for LLM application development and integrations. |
| [diffusionstudio/lottie](https://github.com/diffusionstudio/lottie) | `skills` | Lottie, motion, Skia | Generates and verifies editable Lottie JSON animations in an official local player. |
| [greensock/gsap-skills](https://github.com/greensock/gsap-skills) | `skills` | GSAP, animation, ScrollTrigger | Eight official skills covering GSAP core, timelines, frameworks, plugins, and performance. |
| [three-scope-map-skill](https://github.com/songsummer920-dazzle/three-scope-map-skill) | `skills` | Three.js, 3D maps, Vue | A template-driven skill for building and validating drill-down 3D geographic maps. |
| [web-to-design-md](https://github.com/Paidax01/web-to-design-md) | `skills` | design extraction, browser, DESIGN.md | Converts a live website into a reusable design system document and HTML preview. |
| [shadcn skill](https://ui.shadcn.com/docs/skills) | `skills` | shadcn/ui, components, CLI | Official project-aware guidance for composing and maintaining shadcn/ui interfaces. |
| [zhongerxin/cowart](https://github.com/zhongerxin/cowart) | `developer-tools` | Codex plugin, tldraw, canvas, image generation | Adds a project-local infinite canvas for visual thinking, AI image generation, and annotation-driven iteration. |
| [eze-is/web-access](https://github.com/eze-is/web-access) | `skills` | web access, CDP, browser automation | Gives agents a structured web-access layer with tool selection, browser CDP control, local browser history lookup, and parallel research patterns. |
| [bozhouDev/codex-orange-book](https://github.com/bozhouDev/codex-orange-book) | `research-learning` | Codex, guide, workflow, PDF | A Chinese open guide that explains Codex installation, workflows, skills, MCP, plugins, and practical examples. |
| [inlineresearch/Inline-Studio](https://github.com/inlineresearch/Inline-Studio) | `applications` | ComfyUI, visual art, node canvas, desktop app | A desktop creative tool for building, iterating, exporting, and sharing generative visual pipelines on top of a user's own ComfyUI. |

## Entry Format / 条目格式

Each project should be described in both Chinese and English when possible.

每个项目尽量同时提供中文和英文介绍。

```yaml
- name: project-name
  repo: owner/repo
  url: https://github.com/owner/repo
  category: agents
  tags:
    - multi-agent
    - workflow
  languages:
    - Python
  summary_zh: 简短中文介绍。
  summary_en: Short English summary.
  why_it_matters_zh: 为什么值得关注。
  why_it_matters_en: Why this project is worth tracking.
  status: active
```

## Evaluation Notes / 解读维度

When adding or reviewing a project, prefer concrete observations over hype.

收录和解读时尽量避免空泛评价，重点关注可验证的信息。

- Use case: what problem does it solve?
- Reusability: can the idea, architecture, or workflow be reused?
- Maturity: is the project maintained and usable?
- Integration value: does it connect well with other AI tools or protocols?
- Learning value: does it help readers understand AI-native software design?
- Risk: are there security, privacy, maintenance, or lock-in concerns?

## Repository Structure / 仓库结构

```text
.
├── README.md
├── data/
│   └── projects.yml
├── CONTRIBUTING.md
├── LICENSE
└── .github/
    └── ISSUE_TEMPLATE/
        └── recommend-project.yml
```

## Contributing / 参与贡献

You can suggest a project by opening an issue with the recommendation template. Pull requests are welcome when the entry is factual, bilingual where possible, and includes a clear reason for inclusion.

你可以通过 Issue 推荐项目。也欢迎直接提交 PR，但请尽量保证信息准确、分类清晰，并说明为什么值得收录。

## Maintainer / 维护者

Maintained by SunyataAI.

由 SunyataAI 维护。