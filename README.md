<div align="center">

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="social" src="https://github.com/user-attachments/assets/a6f310af-8fed-4766-9649-b190575b399d" />
</a>

<br/>
<br/>

<div align="center">
    <strong>Discover 700+ community-built OpenClaw skills, organized by category.
    </strong>
    <br />
    <br />
</div>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a> 

![Skills Count](https://img.shields.io/badge/skills-700+-blue?style=flat-square)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-clawdbot-skills?label=Last%20update&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![GitHub forks](https://img.shields.io/github/forks/VoltAgent/awesome-clawdbot-skills?style=social)](https://github.com/VoltAgent/awesome-claude-skills/network/members)
</div>

# Awesome OpenClaw(Moltbot(Clawdbot)) 技能集

OpenClaw（曾用名 Moltbot，最初名为 Clawdbot...包含身份危机，无需额外费用）是一个在您本地机器上直接运行的 AI 助手。技能（Skills）扩展了它的能力，使其能够与外部服务交互、自动化工作流程并执行专门任务。本集合帮助您发现并安装符合需求的技能。

此列表中的技能源自 [OpenClaw](https://clawdhub.com)（OpenClaw 的公共技能注册中心），并已分类以便于查找。

这些技能遵循由 Anthropic 开发的 Agent Skill 规范，这是一个面向 AI 编程助手的开放标准。

## 安装

### ClawdHub CLI

> **注意：** 正如您可能知道的，他们一直在重命名。这里反映的是当前的官方文档。当他们再次重命名时，我们会更新此部分。
```bash
npx clawdhub@latest install <skill-slug>
```

### 手动安装

将技能文件夹复制到以下任一位置：

| 位置 | 路径 |
|----------|------|
| 全局（Global） | `~/.openclaw/skills/` |
| 工作区（Workspace） | `<项目路径>/skills/` |

优先级：工作区 > 本地 > 内置


## 目录

- [Web 与前端开发](#web-与前端开发) (14)
- [编程助手与 IDE](#编程助手与-ide) (15)
- [Git 与 GitHub](#git-与-github) (9)
- [DevOps 与云服务](#devops-与云服务) (41)
- [浏览器与自动化](#浏览器与自动化) (11)
- [图像与视频生成](#图像与视频生成) (19)
- [苹果应用与服务](#苹果应用与服务) (14)
- [搜索与研究](#搜索与研究) (23)
- [Clawdbot 工具](#clawdbot-工具) (17)
- [CLI 工具集](#cli-工具集) (41)
- [市场营销与销售](#市场营销与销售) (42)
- [生产力与任务管理](#生产力与任务管理) (42)
- [AI 与 LLMs](#ai-与-llms) (38)
- [金融](#金融) (29)
- [媒体与流媒体](#媒体与流媒体) (29)
- [笔记与个人知识管理](#笔记与个人知识管理) (44)
- [iOS 与 macOS 开发](#ios-与-macos-开发) (13)
- [交通出行](#交通出行) (34)
- [个人发展](#个人发展) (27)
- [健康与健身](#健康与健身) (26)
- [通讯](#通讯) (26)
- [语音与转录](#语音与转录) (21)
- [智能家居与物联网](#智能家居与物联网) (31)
- [购物与电子商务](#购物与电子商务) (22)
- [日历与日程安排](#日历与日程安排) (16)
- [PDF 与文档](#pdf-与文档) (12)
- [自托管与自动化](#自托管与自动化) (11)
- [安全与密码管理](#安全与密码管理) (6)

<br/>

<a href="https://github.com/VoltAgent/voltagent">
<img width="1390" height="296" alt="social" src="https://github.com/user-attachments/assets/4c40affa-8e20-443a-9ec5-1abb6679b170" />
</a>

<br/>

<details open>
<summary><h3 style="display:inline">Web 与前端开发</h3></summary>

- [discord](https://github.com/openclaw/skills/tree/main/skills/steipete/discord/SKILL.md) - 当需要通过 Discord 工具从 Clawdbot 控制 Discord 时使用：发送消息、添加反应。
- [frontend-design](https://github.com/openclaw/skills/tree/main/skills/steipete/frontend-design/SKILL.md) - 创建独特、生产级且具有高设计质量的前端界面。
- [linux-service-triage](https://github.com/openclaw/skills/tree/main/skills/kowl64/linux-service-triage/SKILL.md) - 使用日志、systemd/PM2、文件权限诊断常见的 Linux 服务问题。
- [miniflux-news](https://github.com/openclaw/skills/tree/main/skills/hartlco/miniflux-news/SKILL.md) - 从 Miniflux 实例获取并分类最新的未读 RSS/新闻条目。
- [pinak-frontend-guru](https://github.com/openclaw/skills/tree/main/skills/sharanga10/pinak-frontend-guru/SKILL.md) - 专家级 UI/UX 和 React 性能审核器（PinakBot 角色）。
- [remotion-best-practices](https://github.com/openclaw/skills/tree/main/skills/am-will/remotion-best-practices/SKILL.md) - Remotion 最佳实践 - 在 React 中创建视频。
- [remotion-server](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/remotion-server/SKILL.md) - 使用 Remotion 进行无头视频渲染。可在任何 Linux 服务器上运行 - 无需 Mac 或 GUI。
- [slack](https://github.com/openclaw/skills/tree/main/skills/steipete/slack/SKILL.md) - 当需要通过 Slack 工具从 Clawdbot 控制 Slack 时使用。
- [ui-audit](https://github.com/openclaw/skills/tree/main/skills/tommygeoco/ui-audit/SKILL.md) - 用于自动化 UI 审核的 AI 技能。根据成熟的 UX 原则评估界面。
- [ui-skills](https://github.com/openclaw/skills/tree/main/skills/correctroadh/ui-skills/SKILL.md) - 用于通过智能体构建更好界面的规范性约束。
- [ux-audit](https://github.com/openclaw/skills/tree/main/skills/tommygeoco/ux-audit/SKILL.md) - 用于自动化设计审核的 AI 技能。根据成熟的 UX 原则评估界面。
- [ux-decisions](https://github.com/openclaw/skills/tree/main/skills/tommygeoco/ux-decisions/SKILL.md) - 用于 Tommy Geoco 的 Making UX Decisions 框架 (uxdecisions.com) 的 AI 技能。
- [vercel-react-best-practices](https://github.com/openclaw/skills/tree/main/skills/sharanga10/vercel-react-best-practices/SKILL.md) - 来自 Vercel 工程的 React 和 Next.js 性能优化指南。
- [web-design-guidelines](https://github.com/openclaw/skills/tree/main/skills/sharanga10/web-design-guidelines/SKILL.md) - 审查 UI 代码是否符合 Web 界面指南。

</details>

<details open>
<summary><h3 style="display:inline">编程助手与IDE</h3></summary>

- [agentlens](https://github.com/openclaw/skills/tree/main/skills/nguyenphutrong/agentlens/SKILL.md) - 使用agentlens层次化文档导航和理解代码库
- [claude-team](https://github.com/openclaw/skills/tree/main/skills/jalehman/claude-team/SKILL.md) - 通过claude-team MCP服务器在iTerm2中协调多个Claude Code工作器
- [codex-account-switcher](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-account-switcher/SKILL.md) - 管理多个OpenAI Codex账户，捕获当前登录令牌
- [codex-monitor](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-monitor/SKILL.md) - 浏览存储在~/.codex/sessions中的OpenAI Codex会话日志
- [codex-orchestration](https://github.com/openclaw/skills/tree/main/skills/shanelindsay/codex-orchestration/SKILL.md) - Codex的通用编排工具
- [codex-quota](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-quota/SKILL.md) - 使用本地会话日志检查OpenAI Codex CLI的速率限制状态(每日/每周配额)
- [codexmonitor](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codexmonitor/SKILL.md) - 列出/检查/监控本地OpenAI Codex会话(CLI + VS Code)
- [coding-agent](https://github.com/openclaw/skills/tree/main/skills/steipete/coding-agent/SKILL.md) - 运行Codex CLI、Claude Code、OpenCode或Pi Coding Agent
- [cursor-agent](https://github.com/openclaw/skills/tree/main/skills/swiftlysingh/cursor-agent/SKILL.md) - 使用Cursor CLI助手的综合技能
- [factory-ai](https://github.com/openclaw/skills/tree/main/skills/mitchellbernstein/factory-ai/SKILL.md) - 使用Factory AI的droid CLI处理软件工程任务
- [model-usage](https://github.com/openclaw/skills/tree/main/skills/steipete/model-usage/SKILL.md) - 使用CodexBar CLI本地成本使用情况汇总每个模型的Codex使用情况
- [opencode-acp-control](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/opencode-acp-control/SKILL.md) - 通过Agent Client Protocol(ACP)直接控制OpenCode
- [perry-coding-agents](https://github.com/openclaw/skills/tree/main/skills/gricha/perry-coding-agents/SKILL.md) - 将编码任务分派到Perry工作区的OpenCode或Claude Code
- [perry-workspaces](https://github.com/openclaw/skills/tree/main/skills/gricha/perry-workspaces/SKILL.md) - 在您的tailnet上使用Claude Code创建和管理隔离的Docker工作区
- [prompt-log](https://github.com/openclaw/skills/tree/main/skills/thesash/prompt-log/SKILL.md) - 从AI编码会话日志(Clawdbot、Claude Code、Codex)中提取对话记录

</details>

<details open>
<summary><h3 style="display:inline">Git 与 GitHub</h3></summary>

- [conventional-commits](https://github.com/openclaw/skills/tree/main/skills/bastos/conventional-commits/SKILL.md) - 使用 Conventional Commits 规范格式化提交信息
- [deepwiki](https://github.com/openclaw/skills/tree/main/skills/arun-8687/deepwiki/SKILL.md) - 查询 DeepWiki MCP 服务器获取 GitHub 仓库文档和 wiki 结构
- [deepwork-tracker](https://github.com/openclaw/skills/tree/main/skills/adunne09/deepwork-tracker/SKILL.md) - 本地跟踪深度工作会话（开始/停止/状态）
- [deploy-agent](https://github.com/openclaw/skills/tree/main/skills/sherajdev/deploy-agent/SKILL.md) - 全栈应用的多步骤部署代理
- [github](https://github.com/openclaw/skills/tree/main/skills/steipete/github/SKILL.md) - 使用 `gh` CLI 与 GitHub 交互
- [github-pr](https://github.com/openclaw/skills/tree/main/skills/dbhurley/github-pr/SKILL.md) - 获取、预览、合并和本地测试 GitHub PR
- [gitload](https://github.com/openclaw/skills/tree/main/skills/waldekmastykarz/gitload/SKILL.md) - 从 GitHub 下载文件或文件夹而无需克隆整个仓库
- [pr-commit-workflow](https://github.com/openclaw/skills/tree/main/skills/joshp123/pr-commit-workflow/SKILL.md) - 创建提交或拉取请求时应使用此技能
- [read-github](https://github.com/openclaw/skills/tree/main/skills/am-will/read-github/SKILL.md) - 通过 gitmcp.io 读取 GitHub 仓库，支持语义搜索和 LLM 优化输出

</details>

<details>
<summary><h3 style="display:inline">DevOps 与云服务</h3></summary>

- [Azure CLI](https://github.com/openclaw/skills/tree/main/skills/ddevaal/azure-cli/SKILL.md) - 通过命令行界面全面管理 Azure 云平台
- [cloudflare](https://github.com/openclaw/skills/tree/main/skills/asleep123/wrangler/SKILL.md) - 使用 Wrangler CLI 管理 Cloudflare Workers、KV、D1、R2 和密钥
- [coolify](https://github.com/openclaw/skills/tree/main/skills/visiongeist/coolify/SKILL.md) - 通过 Coolify API 管理部署、应用、数据库和服务
- [digital-ocean](https://github.com/openclaw/skills/tree/main/skills/dbhurley/digital-ocean/SKILL.md) - 通过 DO API 管理 Digital Ocean 虚拟机、域名和基础设施
- [dokploy](https://github.com/openclaw/skills/tree/main/skills/joshuarileydev/dokploy/SKILL.md) - 通过 Dokploy API 管理部署、项目、应用和域名
- [domain-dns-ops](https://github.com/openclaw/skills/tree/main/skills/steipete/domain-dns-ops/SKILL.md) - 跨 Cloudflare、DNSimple 和 Namecheap 的域名/DNS 操作
- [domaindetails](https://github.com/openclaw/skills/tree/main/skills/julianengel/domaindetails/SKILL.md) - 查询域名 WHOIS/RDAP 信息并检查市场列表（免费 API，无需认证）
- [exa-plus](https://github.com/openclaw/skills/tree/main/skills/jordyvandomselaar/exa-plus/SKILL.md) - 通过 Exa AI 进行神经网络网络搜索（人员、公司、新闻、研究、代码）
- [exe-dev](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/exe-dev/SKILL.md) - 在 exe.dev 上管理持久性虚拟机（创建、配置 HTTP 代理、共享访问）
- [hetzner](https://github.com/openclaw/skills/tree/main/skills/thesethrose/hetzner/SKILL.md) - 使用 hcloud CLI 管理 Hetzner Cloud 服务器
- [hetzner-cloud](https://github.com/openclaw/skills/tree/main/skills/pasogott/hetzner-cloud/SKILL.md) - Hetzner Cloud CLI（管理服务器、卷、防火墙、网络、DNS 和快照）
- [Joan Workflow](https://github.com/openclaw/skills/tree/main/skills/donny-son/joan-workflow/SKILL.md) - 当用户询问"joan"、"pods"、"workspace"或"domain knowledge"时使用
- [komodo](https://github.com/openclaw/skills/tree/main/skills/weird-aftertaste/komodo/SKILL.md) - 管理 Komodo 基础设施（服务器、Docker 部署、堆栈、构建和流程）
- [kubectl-skill](https://github.com/openclaw/skills/tree/main/skills/ddevaal/kubectl/SKILL.md) - 通过 kubectl 命令执行和管理 Kubernetes 集群
- [linearis](https://github.com/openclaw/skills/tree/main/skills/whoisnnamdi/linearis/SKILL.md) - Linear.app CLI（问题跟踪：列表、创建、更新）
- [npm-proxy](https://github.com/openclaw/skills/tree/main/skills/weird-aftertaste/npm-proxy/SKILL.md) - 管理 Nginx Proxy Manager (NPM) 主机、证书和访问列表
- [portainer](https://github.com/openclaw/skills/tree/main/skills/asteinberger/portainer/SKILL.md) - 通过 Portainer API 控制 Docker 容器和堆栈
- [premium-domains](https://github.com/openclaw/skills/tree/main/skills/julianengel/premium-domains/SKILL.md) - 在 Afternic、Sedo、Atom、Dynadot、Namecheap、NameSilo 搜索待售高级域名
- [private-connect](https://github.com/openclaw/skills/tree/main/skills/dantelex/private-connect/SKILL.md) - 通过名称访问私有服务（无需 VPN 或 SSH 隧道）
- [proxmox](https://github.com/openclaw/skills/tree/main/skills/weird-aftertaste/proxmox/SKILL.md) - 通过 REST API 管理 Proxmox VE 集群
- [proxmox-full](https://github.com/openclaw/skills/tree/main/skills/msarheed/proxmox-full/SKILL.md) - 完整的 Proxmox VE 管理（创建/克隆/启动/停止虚拟机）
- [Send Me My Files - R2 upload with short lived signed urls](https://github.com/openclaw/skills/tree/main/skills/julianengel/r2-upload/SKILL.md) - 上传文件到 Cloudflare R2、AWS S3 或任何 S3 兼容存储
- [servicenow-agent](https://github.com/openclaw/skills/tree/main/skills/thesethrose/servicenow-agent/SKILL.md) - ServiceNow 表、附件和聚合的只读 CLI 访问
- [servicenow-docs](https://github.com/openclaw/skills/tree/main/skills/thesethrose/servicenow-docs/SKILL.md) - 搜索和检索 ServiceNow 文档及发行说明
- [supabase](https://github.com/openclaw/skills/tree/main/skills/stopmoclay/supabase/SKILL.md) - 连接 Supabase 进行数据库操作、向量搜索和存储
- [sysadmin-toolbox](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/sysadmin-toolbox/SKILL.md) - 系统管理员、DevOps 和安全任务的工具发现与 shell 单行命令参考
- [tailscale](https://github.com/openclaw/skills/tree/main/skills/jmagar/tailscale/SKILL.md) - 通过 CLI 和 API 管理 Tailscale tailnet
- [tailscale-serve](https://github.com/openclaw/skills/tree/main/skills/snopoke/tailscale-serve/SKILL.md) - tailscale-serve 功能
- [tavily](https://github.com/openclaw/skills/tree/main/skills/bert-builder/tavily/SKILL.md) - 使用 Tavily Search API 进行 AI 优化的网页搜索
- [unraid](https://github.com/openclaw/skills/tree/main/skills/jmagar/unraid/SKILL.md) - 通过 GraphQL API 查询和监控 Unraid 服务器
- [uptime-kuma](https://github.com/openclaw/skills/tree/main/skills/msarheed/uptime-kuma/SKILL.md) - 与 Uptime Kuma 监控服务器交互
- [vercel](https://github.com/openclaw/skills/tree/main/skills/thesethrose/vercel/SKILL.md) - 部署应用和管理项目（完整 CLI 参考）
- [vercel-deploy](https://github.com/openclaw/skills/tree/main/skills/sharanga10/vercel-deploy-claimable/SKILL.md) - 将应用程序和网站部署到 Vercel
- [pi-admin](https://github.com/openclaw/skills/tree/main/skills/thesethrose/pi-admin/SKILL.md) - Raspberry Pi 系统管理（监控资源、管理服务、执行更新）

- [k8s-skills](https://github.com/openclaw/skills/tree/main/skills/rohitg00) - 6 个 Kubernetes 技能：自动缩放(HPA/VPA/KEDA)、备份(Velero)、多集群、Cluster API、cert-manager、仪表板浏览器
- [kubernetes](https://github.com/openclaw/skills/tree/main/skills/kcns008/kubernetes/SKILL.md) - 全面的 Kubernetes 和 OpenShift 集群管理
- [flyio-cli](https://github.com/openclaw/skills/tree/main/skills/justinburdett/flyio-cli/SKILL.md) - Fly.io 部署、日志、SSH、密钥、扩展和 Postgres 管理
- [nomad](https://github.com/openclaw/skills/tree/main/skills/danfedick/nomad/SKILL.md) - 查询 HashiCorp Nomad 集群（作业、节点、分配、服务）
- [pm2](https://github.com/openclaw/skills/tree/main/skills/asteinberger/pm2/SKILL.md) - 使用 PM2 进程管理器管理 Node.js 应用
- [cloudflare](https://github.com/openclaw/skills/tree/main/skills/dbhurley/cloudflare/SKILL.md) - Cloudflare CLI（DNS 记录、缓存清除、Workers 路由）
- [tmux-agents](https://github.com/openclaw/skills/tree/main/skills/cuba6112/tmux-agents/SKILL.md) - 在 tmux 会话中管理后台编码代理

</details>

<details>
<summary><h3 style="display:inline">浏览器与自动化</h3></summary>

- [Agent Browser](https://github.com/openclaw/skills/tree/main/skills/thesethrose/agent-browser/SKILL.md) - 基于Rust的无头浏览器自动化CLI工具，支持Node.js回退，使AI代理能够执行网页操作
- [browsh](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/browsh/SKILL.md) - 现代文本浏览器，使用无头Firefox在终端中渲染网页
- [browser-use](https://github.com/openclaw/skills/tree/main/skills/shawnpana/browser-use/SKILL.md) - 基于云的浏览器自动化，提供托管会话和自主任务执行功能
- [context7](https://github.com/openclaw/skills/tree/main/skills/am-will/context7-api/SKILL.md) - 上下文管理API
- [guru-mcp](https://github.com/openclaw/skills/tree/main/skills/pvoo/guru-mcp/SKILL.md) - 通过MCP访问Guru知识库：提问AI、搜索文档、创建草稿
- [mcporter](https://github.com/openclaw/skills/tree/main/skills/steipete/mcporter/SKILL.md) - 使用mcporter CLI直接列出、配置、认证和调用MCP服务器/工具(HTTP协议)
- [verify-on-browser](https://github.com/openclaw/skills/tree/main/skills/myestery/verify-on-browser/SKILL.md) - 通过Chrome DevTools协议控制浏览器(完整CDP访问权限)
- [playwright-cli](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/playwright-cli/SKILL.md) - 通过Playwright CLI实现浏览器自动化测试和网页抓取
- [tekin](https://github.com/openclaw/skills/tree/main/skills/gwqwghksvq-sketch/tekin/SKILL.md) - 基于Rust的无头浏览器CLI工具，支持Node.js回退
- [agent-browser](https://github.com/openclaw/skills/tree/main/skills/murphykobe/agent-browser-2/SKILL.md) - 网页测试、表单填写、截图和数据提取功能
- [agent-zero](https://github.com/openclaw/skills/tree/main/skills/dowingard/agent-zero-bridge/SKILL.md) - 将任务委托给Agent Zero自主编码框架

</details>

<details>
<summary><h3 style="display:inline">图像与视频生成</h3></summary>

- [clinkding](https://github.com/openclaw/skills/tree/main/skills/daveonkels/clinkding/SKILL.md) - 管理linkding书签：保存URL、搜索、标签、整理
- [coloring-page](https://github.com/openclaw/skills/tree/main/skills/borahm/coloring-page/SKILL.md) - 将上传的照片转换为可打印的黑白涂色页
- [comfy-cli](https://github.com/openclaw/skills/tree/main/skills/johntheyoung/comfy-cli/SKILL.md) - 安装、管理和运行ComfyUI实例
- [Excalidraw Flowchart](https://github.com/openclaw/skills/tree/main/skills/swiftlysingh/excalidraw-flowchart/SKILL.md) - 根据描述创建Excalidraw流程图
- [gamma](https://github.com/openclaw/skills/tree/main/skills/stopmoclay/gamma/SKILL.md) - 使用Gamma.app API生成AI驱动的演示文稿、文档和社交媒体帖子
- [krea-api](https://github.com/openclaw/skills/tree/main/skills/fossilizedcarlos/krea-api/SKILL.md) - 通过Krea.ai API生成图像（Flux、Imagen、Ideogram、Seedream等）
- [meshy-ai](https://github.com/openclaw/skills/tree/main/skills/sabatesduran/clawdbot-meshyai-skill/SKILL.md) - 使用Meshy.ai REST API生成资源：(1)文生图（Meshy文本转图像）
- [vap-media](链接) - 通过VAP API进行AI图像、视频和音乐生成。Flux、Veo 3.1、Suno V5，价格透明
- [veo](https://github.com/openclaw/skills/tree/main/skills/buddyh/veo/SKILL.md) - 使用Google Veo生成视频（Veo 3.1 / Veo 3.0）
- [video-frames](https://github.com/openclaw/skills/tree/main/skills/steipete/video-frames/SKILL.md) - 使用ffmpeg从视频中提取帧或短片
- [cad-agent](https://github.com/clawdbot/skills/tree/main/skills/clawd-maf/cad-agent/SKILL.md) - 用于AI代理进行CAD工作的渲染服务器。发送build123d命令，接收渲染图像
- [figma](https://github.com/openclaw/skills/tree/main/skills/maddiedreese/figma/SKILL.md) - Figma设计分析、资源导出、可访问性审核
- [venice-ai](https://github.com/openclaw/skills/tree/main/skills/nhannah/venice-ai-media/SKILL.md) - Venice AI：图像/视频生成、放大、AI编辑
- [pollinations](https://github.com/openclaw/skills/tree/main/skills/isaacgounton/pollinations/SKILL.md) - Pollinations.ai：文本、图像、视频、音频，支持25+模型
- [reve-ai](https://github.com/openclaw/skills/tree/main/skills/dpaluy/reve-ai/SKILL.md) - Reve AI图像生成、编辑和混音
- [vap-media](https://github.com/openclaw/skills/tree/main/skills/elestirelbilinc-sketch/vap-media/SKILL.md) - AI媒体生成：Flux、Veo 3.1、Suno V5
- [gifhorse](https://github.com/openclaw/skills/tree/main/skills/coyote-git/gifhorse/SKILL.md) - 搜索视频对话并创建带字幕的反应GIF
- [superdesign](https://github.com/openclaw/skills/tree/main/skills/mpociot/superdesign/SKILL.md) - 现代UI的专业前端设计指南
- [comfyui](https://github.com/openclaw/skills/tree/main/skills/xtopher86/comfyui-request/SKILL.md) - 向ComfyUI发送工作流请求并获取图像结果
- [fal-ai](https://github.com/openclaw/skills/tree/main/skills/agmmnn/fal-ai/SKILL.md) - 使用Fal.ai的生成媒体API生成图像、视频和音频

</details>

<details>
<summary><h3 style="display:inline">苹果应用与服务</h3></summary>

- [apple-contacts](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-contacts/SKILL.md) - 从macOS通讯录应用查找联系人
- [apple-music](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-music/SKILL.md) - 搜索Apple Music、添加歌曲到资料库、管理播放列表、控制播放和AirPlay
- [apple-photos](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-photos/SKILL.md) - macOS照片应用集成。列出相册、浏览照片、按日期/人物/内容搜索
- [get-focus-mode](https://github.com/openclaw/skills/tree/main/skills/nickchristensen/get-focus-mode/SKILL.md) - 获取当前macOS专注模式状态
- [healthkit-sync](https://github.com/openclaw/skills/tree/main/skills/mneves75/healthkit-sync/SKILL.md) - iOS健康数据同步CLI命令和模式
- [homebrew](https://github.com/openclaw/skills/tree/main/skills/thesethrose/homebrew/SKILL.md) - macOS的Homebrew包管理器。搜索、安装、管理及排查软件包和cask问题
- [icloud-findmy](https://github.com/openclaw/skills/tree/main/skills/liamnichols/icloud-findmy/SKILL.md) - 通过iCloud查询家人设备的"查找"位置和电量状态
- [media-backup](https://github.com/openclaw/skills/tree/main/skills/dbhurley/media-backup/SKILL.md) - 将Clawdbot对话中的媒体文件(照片、视频)归档到本地文件夹
- [mole-mac-cleanup](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/mole-mac-cleanup/SKILL.md) - 结合CleanMyMac、AppCleaner、DaisyDisk功能的Mac清理优化工具
- [shortcuts-generator](https://github.com/openclaw/skills/tree/main/skills/erik-agens/shortcuts-skill/SKILL.md) - 通过创建plist文件生成macOS/iOS快捷指令
- [apple-remind-me](https://github.com/openclaw/skills/tree/main/skills/plgonzalezrx8/apple-remind-me/SKILL.md) - 通过Apple提醒事项应用设置自然语言提醒
- [apple-mail-search](https://github.com/openclaw/skills/tree/main/skills/mneves75/apple-mail-search/SKILL.md) - 通过SQLite实现快速Apple邮件搜索(~50ms vs 8+分钟)
- [alter-actions](https://github.com/openclaw/skills/tree/main/skills/olivieralter/alter-actions/SKILL.md) - 通过x-callback-url触发84+种Alter macOS应用操作
- [voice-wake-say](https://github.com/openclaw/skills/tree/main/skills/xadenryan/voice-wake-say/SKILL.md) - 通过macOS的say命令语音播报响应内容

</details>

<details>
<summary><h3 style="display:inline">搜索与研究</h3></summary>

- [brave-search](https://github.com/openclaw/skills/tree/main/skills/steipete/brave-search/SKILL.md) - 通过Brave搜索API进行网页搜索和内容提取
- [brightdata](https://github.com/openclaw/skills/tree/main/skills/meirkad/bright-data/SKILL.md) - 通过Bright Data API进行网页抓取和搜索
- [clawdbot-logs](https://github.com/openclaw/skills/tree/main/skills/satriapamudji/clawdbot-logs/SKILL.md) - 分析Clawdbot日志和诊断信息（当用户询问机器人性能时使用）
- [exa](https://github.com/openclaw/skills/tree/main/skills/fardeenxyz/exa/SKILL.md) - 通过Exa AI API进行神经网络网页搜索和代码上下文分析（需要EXA_API_KEY）
- [kagi-search](https://github.com/openclaw/skills/tree/main/skills/silversteez/kagi-search/SKILL.md) - 使用Kagi搜索API进行网页搜索（需要搜索网页时使用）
- [literature-review](https://github.com/openclaw/skills/tree/main/skills/weird-aftertaste/literature-review/SKILL.md) - 通过搜索学术资源协助撰写文献综述
- [parallel](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/parallel/SKILL.md) - 通过Parallel.ai API进行高精度网页搜索和研究
- [seo-audit](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/seo-audit/SKILL.md) - 当用户需要审核、检查或诊断网站SEO问题时使用
- [spots](https://github.com/openclaw/skills/tree/main/skills/foeken/spots/SKILL.md) - 使用基于网格扫描的详尽Google Places搜索
- [tavily](https://github.com/openclaw/skills/tree/main/skills/arun-8687/tavily-search/SKILL.md) - 通过Tavily API进行AI优化的网页搜索（为AI代理返回简洁相关的结果）
- [tweet-writer](https://github.com/openclaw/skills/tree/main/skills/sanky369/tweet-writer/SKILL.md) - 撰写病毒式传播、有说服力且引人入胜的推文和推文串
- [web-search-plus](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/web-search-plus/SKILL.md) - 具有智能自动路由的统一搜索技能
- [seo-analytics](https://github.com/openclaw/skills/tree/main/skills/adamkristopher) - 3种SEO/分析技能：DataForSEO关键词、GA4+搜索控制台、YouTube分析
- [last30days](https://github.com/openclaw/skills/tree/main/skills/zats/last30days/SKILL.md) - 研究Reddit、X和网页上最近30天的任何主题
- [youtube-summarizer](https://github.com/openclaw/skills/tree/main/skills/abe238/youtube-summarizer/SKILL.md) - 获取YouTube字幕并生成结构化摘要
- [gemini-yt-transcript](https://github.com/openclaw/skills/tree/main/skills/odrobnik/gemini-yt-video-transcript/SKILL.md) - 通过Google Gemini获取带说话人标签的YouTube字幕
- [arxiv-watcher](https://github.com/openclaw/skills/tree/main/skills/rubenfb23/arxiv-watcher/SKILL.md) - 搜索和总结ArXiv上的论文
- [serpapi](https://github.com/openclaw/skills/tree/main/skills/ianpcook/serpapi/SKILL.md) - 统一搜索Google、Amazon、Yelp、OpenTable、Walmart
- [grok-search](https://github.com/openclaw/skills/tree/main/skills/notabhay/grok-search/SKILL.md) - 使用xAI Grok搜索网页或X/Twitter
- [perplexity](https://github.com/openclaw/skills/tree/main/skills/dronnick/perplexity-bash/SKILL.md) - 使用Perplexity API进行有引用的基于网页的搜索
- [parallel](https://github.com/openclaw/skills/tree/main/skills/pntrivedy/parallel-1-0-1/SKILL.md) - 为AI代理优化的Parallel.ai网页搜索
- [searxng](https://github.com/openclaw/skills/tree/main/skills/abk234/searxng/SKILL.md) - 通过本地SearXNG实例进行尊重隐私的元搜索
- [news-aggregator](https://github.com/openclaw/skills/tree/main/skills/cclank/news-aggregator-skill/SKILL.md) - 来自8个来源的新闻：Hacker News、GitHub Trending、Product Hunt等

</details>

<details>
<summary><h3 style="display:inline">Clawdbot 工具</h3></summary>

- [agent-browser](https://github.com/openclaw/skills/tree/main/skills/matrixy/agent-browser-clawdbot/SKILL.md) - 为AI代理优化的无头浏览器自动化CLI，支持无障碍树快照
- [auto-updater](https://github.com/openclaw/skills/tree/main/skills/maximeprades/auto-updater/SKILL.md) - 自动每日更新Clawdbot及所有已安装技能
- [claude-code-usage](https://github.com/openclaw/skills/tree/main/skills/azaidi94/claude-code-usage/SKILL.md) - 检查Claude Code OAuth使用限制（会话和每周配额）
- [claude-connect](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/claude-connect/SKILL.md) - 即时将Claude连接到Clawdbot并保持24/7连接
- [clawd-modifier](https://github.com/openclaw/skills/tree/main/skills/masonc15/clawd-modifier/SKILL.md) - 修改Claude Code吉祥物Clawd（当用户想要自定义Clawd时使用）
- [clawdbot-documentation-expert](https://github.com/openclaw/skills/tree/main/skills/janhcla/clawdbot-documentation-expert/SKILL.md) - Clawdbot文档专家
- [clawdbot-skill-update](https://github.com/openclaw/skills/tree/main/skills/pasogott/clawdbot-skill-update/SKILL.md) - 包含动态工作区检测的全面备份、更新和恢复工作流
- [clawdbot-workspace-template-review](https://github.com/openclaw/skills/tree/main/skills/xadenryan/clawdbot-skill-clawdbot-workspace-template-review/SKILL.md) - 将Clawdbot工作区与官方模板（通过npm安装）进行比较
- [clawddocs](https://github.com/openclaw/skills/tree/main/skills/nicholasspisak/clawddocs/SKILL.md) - 具有决策树导航、搜索脚本、文档获取功能的Clawdbot文档专家
- [clawdhub](https://github.com/openclaw/skills/tree/main/skills/steipete/clawdhub/SKILL.md) - 使用ClawdHub CLI从clawdhub.com搜索、安装、更新和发布代理技能
- [clawdlink](https://github.com/openclaw/skills/tree/main/skills/davemorin/clawdlink/SKILL.md) - 加密的Clawdbot间消息传递
- [skills-audit](https://github.com/openclaw/skills/tree/main/skills/morozred/skill-audit/SKILL.md) - 审计本地安装的代理技能的安全/策略问题
- [skills-search](https://github.com/openclaw/skills/tree/main/skills/thesethrose/skills-search/SKILL.md) - 从CLI搜索skills.sh注册表，发现skills.sh生态系统中的代理技能
- [git-notes-memory](https://github.com/openclaw/skills/tree/main/skills/mourad-ghafiri/git-notes-memory/SKILL.md) - 基于Git-notes的跨会话持久化内存
- [triple-memory](https://github.com/openclaw/skills/tree/main/skills/ktpriyatham/triple-memory/SKILL.md) - LanceDB + Git-Notes + 基于文件的内存系统
- [self-reflect](https://github.com/openclaw/skills/tree/main/skills/stevengonsalvez/self-reflect/SKILL.md) - 通过对话分析和学习实现自我改进
- [mcporter-skill](https://github.com/openclaw/skills/tree/main/skills/livvux/mcporter-skill/SKILL.md) - 通过mcporter CLI列出、配置、认证和调用MCP服务器/工具

</details>

<details>
<summary><h3 style="display:inline">命令行工具</h3></summary>

- [bible](https://github.com/openclaw/skills/tree/main/skills/dbhurley/bible-votd/SKILL.md) - 获取Bible.com每日经文并生成可分享图片
- [camsnap](https://github.com/openclaw/skills/tree/main/skills/steipete/camsnap/SKILL.md) - 从RTSP/ONVIF摄像头捕获画面或片段
- [canvas-lms](https://github.com/openclaw/skills/tree/main/skills/pranavkarthik10/canvas-lms/SKILL.md) - 访问Canvas LMS(Instructure)获取课程数据、作业、成绩和提交内容
- [Cat Fact](https://github.com/openclaw/skills/tree/main/skills/thesethrose/catfact/SKILL.md) - 从catfact.ninja获取随机猫咪知识和品种信息(免费无需API密钥)
- [content-advisory](https://github.com/openclaw/skills/tree/main/skills/dbhurley/content-advisory/SKILL.md) - 查询电影和电视节目的详细内容评级(性/裸露、暴力/血腥等)
- [create-cli](https://github.com/openclaw/skills/tree/main/skills/steipete/create-cli/SKILL.md) - 设计CLI参数、标志、子命令和帮助文本
- [data-reconciliation-exceptions](https://github.com/openclaw/skills/tree/main/skills/kowl64/data-reconciliation-exceptions/SKILL.md) - 使用稳定标识符(工资号、驾照、司机卡等)协调数据源
- [dilbert](https://github.com/openclaw/skills/tree/main/skills/hjanuschka/dilbert/SKILL.md) - 获取Dilbert漫画
- [dropbox](https://github.com/openclaw/skills/tree/main/skills/ryanlisse/dropbox/SKILL.md) - Dropbox文件管理
- [duckdb-en](https://github.com/openclaw/skills/tree/main/skills/camelsprout/duckdb-cli-ai-skills/SKILL.md) - DuckDB CLI专家，用于SQL分析、数据处理和文件转换
- [entr](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/entr/SKILL.md) - 文件变更时执行任意命令(常用于监控文件变化触发构建或测试)
- [gifgrep](https://github.com/openclaw/skills/tree/main/skills/steipete/gifgrep/SKILL.md) - 通过CLI/TUI搜索GIF提供商，下载结果并提取静态图/序列图
- [goplaces](https://github.com/openclaw/skills/tree/main/skills/steipete/goplaces/SKILL.md) - 通过goplaces CLI查询Google Places API(New)进行文本搜索、地点详情解析
- [journal-to-post](https://github.com/openclaw/skills/tree/main/skills/itsflow/journal-to-post/SKILL.md) - 将个人日记转换为可分享的社交媒体帖子
- [jq](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/jq/SKILL.md) - 命令行JSON处理器(提取、过滤、转换JSON数据)
- [local-places](https://github.com/openclaw/skills/tree/main/skills/steipete/local-places/SKILL.md) - 通过本地代理的Google Places API搜索地点(餐厅、咖啡馆等)
- [native-app-performance](https://github.com/openclaw/skills/tree/main/skills/steipete/native-app-performance/SKILL.md) - 通过xctrace/Time Profiler进行原生macOS/iOS应用性能分析
- [office-quotes](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/office-quotes/SKILL.md) - 生成《办公室》(美版)随机台词
- [parcel-package-tracking](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/parcel-package-tracking/SKILL.md) - 通过Parcel API跟踪和添加快递包裹
- [peekaboo](https://github.com/openclaw/skills/tree/main/skills/steipete/peekaboo/SKILL.md) - 使用Peekaboo CLI捕获和自动化macOS UI操作
- [portable-tools](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/portable-tools/SKILL.md) - 构建跨设备工具而无需硬编码路径或账户名
- [post-at](https://github.com/openclaw/skills/tree/main/skills/krausefx/post-at/SKILL.md) - 管理奥地利邮政(post.at)快递(列出包裹、检查投递状态)
- [process-watch](https://github.com/openclaw/skills/tree/main/skills/dbhurley/process-watch/SKILL.md) - 监控系统进程(CPU、内存、磁盘I/O、网络、打开文件、端口)
- [sag](https://github.com/openclaw/skills/tree/main/skills/steipete/sag/SKILL.md) - 使用ElevenLabs文本转语音，提供类似mac say命令的UX
- [shorten](https://github.com/openclaw/skills/tree/main/skills/kesslerio/shorten/SKILL.md) - 使用is.gd缩短URL(无需认证)，返回永久短链接
- [simple-backup](https://github.com/openclaw/skills/tree/main/skills/vacinc/simple-backup/SKILL.md) - 备份代理大脑(工作区)和身体(状态)到本地文件夹
- [smalltalk](https://github.com/openclaw/skills/tree/main/skills/johnmci/smalltalk/SKILL.md) - 与实时Smalltalk镜像(Cuis或Squeak)交互
- [songsee](https://github.com/openclaw/skills/tree/main/skills/steipete/songsee/SKILL.md) - 使用songsee CLI从音频生成频谱图和特征面板可视化
- [steam](https://github.com/openclaw/skills/tree/main/skills/mjrussell/steam/SKILL.md) - 浏览、筛选和发现Steam游戏库中的游戏
- [sudoku](https://github.com/openclaw/skills/tree/main/skills/odrobnik/sudoku/SKILL.md) - 获取数独谜题并存储为JSON，按需渲染图像或显示答案
- [tldr](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/tldr/SKILL.md) - 来自tldr-pages的简化版man手册(快速理解CLI工具)
- [tmdb](https://github.com/openclaw/skills/tree/main/skills/dbhurley/tmdb/SKILL.md) - 通过TMDb API搜索电影/电视节目，获取演员表、评分、流媒体信息和个人化推荐
- [tmux](https://github.com/openclaw/skills/tree/main/skills/steipete/tmux/SKILL.md) - 远程控制tmux会话，发送按键并抓取面板输出实现交互式CLI
- [track17](https://github.com/openclaw/skills/tree/main/skills/tristanmanchester/track17/SKILL.md) - 通过17TRACK API跟踪包裹(本地SQLite数据库，轮询+可选webhook接收)
- [units](https://github.com/openclaw/skills/tree/main/skills/asleep123/units/SKILL.md) - 使用GNU Units进行单位换算和计算
- [voicenotes](https://github.com/openclaw/skills/tree/main/skills/shawnhansen/voicenotes/SKILL.md) - 同步和访问Voicenotes.com的语音备忘录
- [xkcd](https://github.com/openclaw/skills/tree/main/skills/dbhurley/xkcd/SKILL.md) - 获取xkcd漫画(最新、随机、指定编号或关键词搜索)
- [ecto](https://github.com/openclaw/skills/tree/main/skills/visionik/ecto/SKILL.md) - 通过Ghost.io管理API管理博客
- [domain](https://github.com/openclaw/skills/tree/main/skills/abtdomain/domain/SKILL.md) - 域名情报：NRDS关键词搜索和NS反向查询
- [george](https://github.com/openclaw/skills/tree/main/skills/odrobnik/george/SKILL.md) - George网上银行自动化(奥地利第一储蓄银行/Sparkasse)
- [emredoganer-fizzy](https://github.com/openclaw/skills/tree/main/skills/emredoganer/emredoganer-fizzy-cli/SKILL.md) - 通过CLI管理Fizzy看板板和卡片

</details>

<details>
<summary><h3 style="display:inline">iOS & macOS 开发</h3></summary>

- [apple-docs](https://github.com/openclaw/skills/tree/main/skills/thesethrose/apple-docs/SKILL.md) - 查询苹果开发者文档、API和WWDC视频(2014-2025)
- [apple-docs-mcp](https://github.com/openclaw/skills/tree/main/skills/janhcla/apple-docs-mcp/SKILL.md) - 苹果文档MCP服务
- [instruments-profiling](https://github.com/openclaw/skills/tree/main/skills/steipete/instruments-profiling/SKILL.md) - 使用Instruments/xctrace分析原生macOS或iOS应用性能时使用
- [ios-simulator](https://github.com/openclaw/skills/tree/main/skills/tristanmanchester/ios-simulator/SKILL.md) - 自动化iOS模拟器工作流(simctl + idb)：创建/启动/擦除设备，安装/运行应用
- [macos-spm-app-packaging](https://github.com/openclaw/skills/tree/main/skills/dimillian/macos-spm-app-packaging/SKILL.md) - 无需Xcode项目，直接搭建、构建和打包基于SwiftPM的macOS应用
- [PagerKit](https://github.com/openclaw/skills/tree/main/skills/szpakkamil/pagerkit/SKILL.md) - PagerKit专家指导，这是一个用于高级可定制页面导航的SwiftUI库
- [sfsymbol-generator](https://github.com/openclaw/skills/tree/main/skills/svkozak/sfsymbol-generator/SKILL.md) - 从SVG生成Xcode SF Symbols资源目录.symbolset
- [swift-concurrency-expert](https://github.com/openclaw/skills/tree/main/skills/steipete/swift-concurrency-expert/SKILL.md) - Swift并发代码审查和修复(适用于Swift 6.2+)
- [swiftui-empty-app-init](https://github.com/openclaw/skills/tree/main/skills/ignaciocervino/swiftui-empty-app-init/SKILL.md) - 在当前目录初始化一个极简SwiftUI iOS应用，生成单个.xcodeproj文件
- [swiftui-liquid-glass](https://github.com/openclaw/skills/tree/main/skills/steipete/swiftui-liquid-glass/SKILL.md) - 使用iOS 26+ Liquid Glass API实现、审查或改进SwiftUI功能
- [swiftui-performance-audit](https://github.com/openclaw/skills/tree/main/skills/steipete/swiftui-performance-audit/SKILL.md) - 通过代码审查和架构分析，审核和改进SwiftUI运行时性能
- [swiftui-ui-patterns](https://github.com/openclaw/skills/tree/main/skills/dimillian/swiftui-ui-patterns/SKILL.md) - 构建SwiftUI视图和组件的最佳实践与示例驱动指导
- [swiftui-view-refactor](https://github.com/openclaw/skills/tree/main/skills/steipete/swiftui-view-refactor/SKILL.md) - 重构和审查SwiftUI视图文件，确保结构一致性和依赖注入

</details>

<summary><h3 style="display:inline">市场营销与销售</h3></summary>

- [ab-test-setup](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/ab-test-setup/SKILL.md) - 当用户需要规划、设计或实施A/B测试或实验时使用
- [apollo](https://github.com/openclaw/skills/tree/main/skills/jhumanj/apollo/SKILL.md) - 通过Apollo.io REST API交互(人员/组织信息丰富、搜索、列表)
- [basecamp-cli](https://github.com/openclaw/skills/tree/main/skills/emredoganer/basecamp-cli/SKILL.md) - 管理Basecamp项目(通过bc3 API/37signals Launchpad)：待办事项、消息等
- [bearblog](https://github.com/openclaw/skills/tree/main/skills/azade-c/bearblog/SKILL.md) - 在Bear Blog(bearblog.dev)上创建和管理博客文章
- [bird](https://github.com/openclaw/skills/tree/main/skills/steipete/bird/SKILL.md) - X/Twitter CLI工具(通过cookies或Sweetistics进行阅读、搜索和发帖)
- [bluesky](https://github.com/openclaw/skills/tree/main/skills/jeffaf/bluesky/SKILL.md) - 通过CLI与Bluesky(AT协议)交互：阅读、发帖等
- [competitor-alternatives](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/competitor-alternatives/SKILL.md) - 当用户需要为SEO创建竞品对比或替代方案页面时使用
- [copy-editing](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/copy-editing/SKILL.md) - 当用户需要编辑、审查或改进现有营销文案时使用
- [copywriting](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/copywriting/SKILL.md) - 当用户需要撰写、重写或改进营销文案时使用
- [email-sequence](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/email-sequence/SKILL.md) - 当用户需要创建或优化邮件序列、滴灌营销活动或自动邮件流程时使用
- [form-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/form-cro/SKILL.md) - 当用户需要优化非注册/登录表单(包括潜在客户捕获表单)时使用
- [free-tool-strategy](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/free-tool-strategy/SKILL.md) - 当用户需要规划、评估或构建免费工具时使用
- [ga4](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/ga4/SKILL.md) - 通过Analytics Data API查询Google Analytics 4(GA4)数据
- [gong](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/gong/SKILL.md) - Gong API(用于搜索通话记录、转录文本和对话智能分析)
- [google-ads](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/google-ads/SKILL.md) - 查询、审核和优化Google Ads广告系列
- [gsc](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/gsc/SKILL.md) - 查询Google Search Console获取SEO数据(搜索查询、热门页面、CTR优化机会)
- [hubspot](https://github.com/openclaw/skills/tree/main/skills/kwall1/hubspot/SKILL.md) - HubSpot CRM和CMS API集成(联系人、公司、交易、所有者和内容管理)
- [humanizer](https://github.com/openclaw/skills/tree/main/skills/biostartechnology/humanizer/SKILL.md) - 人性化内容生成工具
- [marketing-mode](https://github.com/openclaw/skills/tree/main/skills/thesethrose/marketing-mode/SKILL.md) - 营销模式(整合23种综合营销技能，涵盖策略、心理学、内容等领域)
- [marketing-psychology](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/marketing-psychology/SKILL.md) - 当用户需要应用心理学原理和心理模型时使用
- [marketing-skills](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/SKILL.md) - 23个营销手册(CRO、SEO、文案、分析、实验、定价、发布、广告等)
- [otter](https://github.com/openclaw/skills/tree/main/skills/dbhurley/otter/SKILL.md) - Otter.ai转录CLI工具(列出、搜索、下载会议转录文本并同步到CRM)
- [paywall-upgrade-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/paywall-upgrade-cro/SKILL.md) - 当用户需要创建或优化应用内付费墙、升级界面或加售弹窗时使用
- [pinch-to-post](https://github.com/openclaw/skills/tree/main/skills/nickhamze/pinch-to-post/SKILL.md) - WordPress自动化工具(管理文章、页面、WooCommerce产品、订单和库存)
- [popup-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/popup-cro/SKILL.md) - 当用户需要创建或优化弹窗、模态框、覆盖层或滑动窗口时使用
- [pricing-strategy](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/pricing-strategy/SKILL.md) - 当用户需要定价决策、包装或变现策略帮助时使用
- [programmatic-seo](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/programmatic-seo/SKILL.md) - 当用户需要使用模板和数据大规模创建SEO驱动页面时使用
- [reddit](https://github.com/openclaw/skills/tree/main/skills/theglove44/reddit/SKILL.md) - 浏览、搜索、发帖和管理Reddit内容
- [reddit-search](https://github.com/openclaw/skills/tree/main/skills/thesethrose/reddit-search/SKILL.md) - 搜索Reddit子论坛并获取相关信息
- [referral-program](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/referral-program/SKILL.md) - 当用户需要创建、优化或分析推荐计划或联盟计划时使用
- [schema-markup](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/schema-markup/SKILL.md) - 当用户需要添加、修复或优化网站的结构化数据标记时使用
- [signup-flow-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/signup-flow-cro/SKILL.md) - 当用户需要优化注册、账户创建或试用激活流程时使用
- [solobuddy](https://github.com/openclaw/skills/tree/main/skills/humanji7/solobuddy/SKILL.md) - 独立开发者公开构建助手(内容工作流、Twitter互动等)
- [twenty-crm](https://github.com/openclaw/skills/tree/main/skills/jhumanj/twenty-crm/SKILL.md) - 通过REST/GraphQL与Twenty CRM(自托管)交互
- [typefully](https://github.com/openclaw/skills/tree/main/skills/thesethrose/typefully/SKILL.md) - Typefully社交媒体管理工具
- [x-article-editor](https://github.com/openclaw/skills/tree/main/skills/jchopard69/x-article-editor/SKILL.md) - 将主题或草稿转化为高互动性的X平台文章
- [shashwatgtm-skills](https://github.com/openclaw/skills/tree/main/skills/shashwatgtm) - B2B营销技能(竞争情报、内容写作、新闻简报、个人品牌、社交媒体管理)
- [sales-toolkit](https://github.com/openclaw/skills/tree/main/skills/andrewdmwalker) - 销售工具包(Apollo.io信息丰富、Attio CRM、PhantomBuster自动化、Firecrawl网页抓取)
- [octolens](https://github.com/openclaw/skills/tree/main/skills/garrrikkotua/octolens/SKILL.md) - 品牌提及追踪工具(覆盖Twitter、Reddit、GitHub、LinkedIn，含情感分析)
- [geo-optimization](https://github.com/openclaw/skills/tree/main/skills/andrewdmwalker/geo-optimization/SKILL.md) - 为AI搜索可见性优化内容(ChatGPT、Perplexity、Claude)
- [recruitment-automation](https://github.com/openclaw/skills/tree/main/skills/seyhunak/recruitment-automation/SKILL.md) - 自动化招聘(职位描述、候选人评估、外联邮件)
- [late-api](https://github.com/openclaw/skills/tree/main/skills/mikipalet/late-api/SKILL.md) - Late API(用于在13个社交媒体平台安排帖子发布)

</details>

<details>
<summary><h3 style="display:inline">生产力与任务管理</h3></summary>

- [clawd-docs-v2](https://github.com/openclaw/skills/tree/main/skills/aranej/clawd-docs-v2/SKILL.md) - 智能访问ClawdBot文档(本地搜索索引、缓存片段和按需获取)
- [clickup-mcp](https://github.com/openclaw/skills/tree/main/skills/pvoo/clickup-mcp/SKILL.md) - 通过官方MCP管理ClickUp任务、文档、时间跟踪、评论、聊天和搜索
- [dex](https://github.com/openclaw/skills/tree/main/skills/gricha/dex/SKILL.md) - 异步/多步骤工作的任务跟踪
- [dexcom](https://github.com/openclaw/skills/tree/main/skills/chris-clem/dexcom/SKILL.md) - 通过Dexcom G7/G6连续血糖监测仪监测血糖
- [dexter](https://github.com/openclaw/skills/tree/main/skills/igorhvr/dexter/SKILL.md) - 自主财务研究代理(股票分析、财务报表、指标、价格)
- [dvsa-tc-audit-readiness-operator-licence-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/dvsa-tc-audit-readiness-operator-licence-uk/SKILL.md) - 构建DVSA/交通委员会"show me"审计准备清单和证据索引
- [gno](https://github.com/openclaw/skills/tree/main/skills/gmickel/gno/SKILL.md) - 搜索本地文档、文件、笔记和知识库
- [jira](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/jira/SKILL.md) - 通过jira-cli管理Jira问题、看板、冲刺和项目
- [linear](https://github.com/openclaw/skills/tree/main/skills/manuelhettich/linear/SKILL.md) - 查询和管理Linear问题、项目和团队工作流
- [morning-manifesto](https://github.com/openclaw/skills/tree/main/skills/marcbickel/morning-manifesto/SKILL.md) - 每日晨间反思工作流(任务同步到Obsidian、Apple提醒事项和Linear)
- [plan-my-day](https://github.com/openclaw/skills/tree/main/skills/itsflow/plan-my-day/SKILL.md) - 生成能量优化、时间分块的每日计划
- [prd](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/prd/SKILL.md) - 创建和管理产品需求文档(PRD)
- [prowlarr](https://github.com/openclaw/skills/tree/main/skills/jmagar/prowlarr/SKILL.md) - 搜索索引器和管理Prowlarr(当用户要求"搜索"时使用)
- [qmd](https://github.com/openclaw/skills/tree/main/skills/steipete/qmd/SKILL.md) - 本地搜索/索引CLI(BM25 + 向量 + 重排序)带MCP模式
- [samsung-smart-tv](https://github.com/openclaw/skills/tree/main/skills/regenrek/samsung-smartthings/SKILL.md) - 通过SmartThings控制三星电视(OAuth应用+设备控制)
- [task](https://github.com/openclaw/skills/tree/main/skills/amirbrooks/task/SKILL.md) - 通过tool-dispatch管理Tasker文档存储任务
- [task-tracker](https://github.com/openclaw/skills/tree/main/skills/kesslerio/task-tracker/SKILL.md) - 个人任务管理(每日站会和每周回顾)
- [things-mac](https://github.com/openclaw/skills/tree/main/skills/steipete/things-mac/SKILL.md) - 在macOS上通过`things` CLI管理Things 3(添加/更新项目+待办事项)
- [ticktick](https://github.com/openclaw/skills/tree/main/skills/manuelhettich/ticktick/SKILL.md) - 从命令行管理TickTick任务和项目(支持OAuth2认证和批量操作)
- [timesheet](https://github.com/openclaw/skills/tree/main/skills/florianrauscha/timesheet/SKILL.md) - 使用timesheet.io CLI跟踪时间、管理项目和任务
- [todo-tracker](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/todo-tracker/SKILL.md) - 持久化TODO便签(用于跨会话跟踪任务)
- [todoist](https://github.com/openclaw/skills/tree/main/skills/mjrussell/todoist/SKILL.md) - 管理Todoist中的任务和项目(当用户询问任务、待办事项、提醒时使用)
- [topydo](https://github.com/openclaw/skills/tree/main/skills/bastos/topydo/SKILL.md) - 使用topydo CLI管理todo.txt任务(添加、列出、完成、优先排序、标记)
- [trello](https://github.com/openclaw/skills/tree/main/skills/steipete/trello/SKILL.md) - 通过Trello REST API管理Trello看板、列表和卡片
- [vikunja](https://github.com/openclaw/skills/tree/main/skills/dbhurley/vikunja/SKILL.md) - 在Vikunja(开源项目管理工具)中管理项目和任务
- [vikunja-fast](https://github.com/openclaw/skills/tree/main/skills/tmigone/vikunja-fast/SKILL.md) - 管理Vikunja项目和任务(逾期/到期/今日)，标记完成
- [web-perf](https://github.com/openclaw/skills/tree/main/skills/elithrar/web-perf/SKILL.md) - 使用Chrome DevTools MCP分析网页性能
- [withings-health](https://github.com/openclaw/skills/tree/main/skills/hisxo/withings-health/SKILL.md) - 从Withings API获取健康数据(包括体重、体脂率、肌肉量、骨量等)
- [outlook](https://github.com/openclaw/skills/tree/main/skills/jotamed/outlook/SKILL.md) - 通过Microsoft Graph API访问Outlook邮件和日历
- [imap-email](https://github.com/openclaw/skills/tree/main/skills/mvarrieur/imap-email/SKILL.md) - 通过IMAP读取和管理邮件(支持ProtonMail、Gmail等)
- [google-workspace](https://github.com/openclaw/skills/tree/main/skills/dru-ca/google-workspace-mcp/SKILL.md) - Gmail、日历、Drive(支持简单OAuth登录)
- [gogcli](https://github.com/openclaw/skills/tree/main/skills/luccast/gogcli/SKILL.md) - Google Workspace CLI(Gmail、日历、Drive、Sheets、Docs、Slides)
- [ticktick](https://github.com/openclaw/skills/tree/main/skills/kaiofreitas/ticktick-tasks/SKILL.md) - TickTick任务管理器(项目、任务、提醒)
- [omnifocus](https://github.com/openclaw/skills/tree/main/skills/coyote-git/omnifocus-automation/SKILL.md) - 通过Omni Automation管理OmniFocus任务、项目和GTD工作流
- [todoist](https://github.com/openclaw/skills/tree/main/skills/2mawi2/todoist-task-manager/SKILL.md) - Todoist CLI(列出、添加、修改、完成、删除任务)
- [taskleef](https://github.com/openclaw/skills/tree/main/skills/xatter/taskleef/SKILL.md) - Taskleef.com待办事项、项目和看板
- [linear-issues](https://github.com/openclaw/skills/tree/main/skills/emrekilinc/linear-issues/SKILL.md) - Linear问题跟踪(创建、更新、列出、搜索问题)
- [jira](https://github.com/openclaw/skills/tree/main/skills/kyjus25/clawdbot-jira-skill/SKILL.md) - 通过REST API管理Jira问题、转换和工作日志
- [atlassian-mcp](https://github.com/openclaw/skills/tree/main/skills/atakanermis/atlassian-mcp/SKILL.md) - Atlassian MCP(通过Docker集成Jira和Confluence)
- [asana](https://github.com/openclaw/skills/tree/main/skills/k0nkupa/asana/SKILL.md) - 通过REST API管理Asana任务、项目和工作区
- [mogcli](https://github.com/openclaw/skills/tree/main/skills/visionik/mogcli/SKILL.md) - Microsoft 365 CLI(邮件、日历、Drive、Word、Excel、OneNote)

</details>

<details>
<summary><h3 style="display:inline">AI与大型语言模型</h3></summary>

- [antigravity-quota](https://github.com/openclaw/skills/tree/main/skills/mukhtharcm/antigravity-quota/SKILL.md) - 检查Antigravity账户中Claude和Gemini模型的配额使用情况
- [ask-questions-if-underspecified](https://github.com/openclaw/skills/tree/main/skills/lc0rp/ask-questions-if-underspecified/SKILL.md) - 在实施前澄清需求(仅在明确调用时使用，不自动触发)
- [claude-oauth-refresher](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/claude-oauth-refresher/SKILL.md) - 保持Claude访问令牌24/7有效
- [council](https://github.com/openclaw/skills/tree/main/skills/emasoudy/council/SKILL.md) - 通过Memory Bridge进行Council Chamber编排
- [de-ai-ify](https://github.com/openclaw/skills/tree/main/skills/itsflow/de-ai-ify/SKILL.md) - 去除AI生成的行话，恢复文本的人性化表达
- [gemini](https://github.com/openclaw/skills/tree/main/skills/steipete/gemini/SKILL.md) - Gemini CLI工具(用于单次问答、摘要和生成)
- [gemini-computer-use](https://github.com/openclaw/skills/tree/main/skills/am-will/gemini-computer-use/SKILL.md) - 使用Playwright构建和运行Gemini 2.5计算机控制代理
- [gemini-deep-research](https://github.com/openclaw/skills/tree/main/skills/arun-8687/gemini-deep-research/SKILL.md) - 使用Gemini深度研究代理执行复杂、长期的研究任务
- [gemini-stt](https://github.com/openclaw/skills/tree/main/skills/araa47/gemini-stt/SKILL.md) - 通过Google Gemini API或Vertex AI转录音频文件
- [llm-council](https://github.com/openclaw/skills/tree/main/skills/am-will/llm-council/SKILL.md) - 编排多LLM委员会来生成和合并实施方案
- [lmstudio-subagents](https://github.com/openclaw/skills/tree/main/skills/t-sinclair2500/lm-studio-subagents/SKILL.md) - 使代理能够搜索并将任务卸载到LM Studio中的本地模型
- [minimax-usage](https://github.com/openclaw/skills/tree/main/skills/thesethrose/minimax-usage/SKILL.md) - 监控Minimax Coding Plan使用情况以确保不超出API限制
- [model-router](https://github.com/openclaw/skills/tree/main/skills/digitaladaption/model-router/SKILL.md) - 综合AI模型路由系统，自动选择最适合任何任务的模型
- [nano-banana-pro](https://github.com/openclaw/skills/tree/main/skills/steipete/nano-banana-pro/SKILL.md) - 使用Nano Banana Pro(Gemini 3 Pro Image)生成/编辑图像
- [openai-docs-skill](https://github.com/openclaw/skills/tree/main/skills/am-will/openai-docs/SKILL.md) - 通过OpenAI Docs MCP服务器查询OpenAI开发者文档(使用curl/jq CLI)
- [openai-image-gen](https://github.com/openclaw/skills/tree/main/skills/steipete/openai-image-gen/SKILL.md) - 通过OpenAI Images API批量生成图像(随机提示采样器+index.html画廊)
- [openai-tts](https://github.com/openclaw/skills/tree/main/skills/pors/openai-tts/SKILL.md) - 通过OpenAI Audio Speech API实现文本转语音
- [openrouter-transcribe](https://github.com/openclaw/skills/tree/main/skills/obviyus/openrouter-transcribe/SKILL.md) - 通过OpenRouter使用支持音频的模型(Gemini、GPT-4o-audio等)转录音频文件
- [oracle](https://github.com/openclaw/skills/tree/main/skills/steipete/oracle/SKILL.md) - 使用@steipete/oracle CLI打包提示和正确的文件
- [perplexity](https://github.com/openclaw/skills/tree/main/skills/zats/perplexity/SKILL.md) - 通过Perplexity API使用AI增强的答案搜索网页
- [personas](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/personas/SKILL.md) - 按需转换为31种专业AI人格
- [pi-orchestration](https://github.com/openclaw/skills/tree/main/skills/dbhurley/pi-orchestration/SKILL.md) - 使用Pi Coding Agent编排多个AI模型(GLM、MiniMax等)作为工作器
- [recipe-to-list](https://github.com/openclaw/skills/tree/main/skills/borahm/recipe-to-list/SKILL.md) - 将食谱转换为Todoist购物清单
- [research](https://github.com/openclaw/skills/tree/main/skills/pors/research/SKILL.md) - 通过Gemini CLI进行深度研究(在后台子代理中运行，避免消耗Claude令牌)
- [screen-monitor](https://github.com/openclaw/skills/tree/main/skills/emasoudy/screen-monitor/SKILL.md) - 双模式屏幕共享和分析(模型无关，支持Gemini/Claude/Qwen3-VL)
- [search-x](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/search-x/SKILL.md) - 使用Grok实时搜索X/Twitter(查找推文、趋势和讨论，带引用)
- [self-improvement](https://github.com/openclaw/skills/tree/main/skills/pskoett/self-improving-agent/SKILL.md) - 捕获学习、错误和修正以实现持续改进
- [smart-followups](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/smart-followups/SKILL.md) - 在AI响应后生成上下文相关的后续建议
- [xai](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/xai/SKILL.md) - 通过xAI API与Grok模型聊天(支持Grok-3、Grok-3-mini、视觉等)
- [manus](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/manus/SKILL.md) - 通过Manus API创建和管理AI代理任务
- [hokipoki](https://github.com/openclaw/skills/tree/main/skills/budjoskop/hokipoki/SKILL.md) - 在Claude、Codex和Gemini之间切换(当某个模型卡住时)
- [council-of-the-wise](https://github.com/openclaw/skills/tree/main/skills/jeffaf/council-of-the-wise/SKILL.md) - 从生成的子代理人格获取多角度反馈
- [multi-viewpoint-debates](https://github.com/openclaw/skills/tree/main/skills/latentfreedom/multi-viewpoint-debates/SKILL.md) - 从多种世界观角度辩论决策，暴露盲点
- [chaos-lab](https://github.com/openclaw/skills/tree/main/skills/jbbottoms/chaos-lab/SKILL.md) - 通过冲突优化目标探索AI对齐
- [ralph-loop](https://github.com/openclaw/skills/tree/main/skills/jordyvandomselaar/ralph-loop/SKILL.md) - 为AI代理循环(Codex、Claude、OpenCode)生成bash脚本
- [research-tracker](https://github.com/openclaw/skills/tree/main/skills/julian1645/research-tracker/SKILL.md) - 使用SQLite跟踪管理自主AI研究代理
- [claude-code-wingman](https://github.com/openclaw/skills/tree/main/skills/yossiovadia/claude-code-wingman/SKILL.md) - 将Claude Code作为技能运行，从WhatsApp控制
- [adversarial-prompting](https://github.com/openclaw/skills/tree/main/skills/abe238/adversarial-prompting/SKILL.md) - 对抗性分析以批评、修复和整合解决方案

</details>

<details>
<summary><h3 style="display:inline">金融与财务</h3></summary>

- [analytics-tracking](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/analytics-tracking/SKILL.md) - 当用户需要设置、改进或审核分析跟踪和测量时使用
- [api-credentials-hygiene](https://github.com/openclaw/skills/tree/main/skills/kowl64/api-credentials-hygiene/SKILL.md) - 审计和强化API凭证处理(环境变量、隔离、轮换计划、最小权限)
- [app-store-changelog](https://github.com/openclaw/skills/tree/main/skills/dimillian/app-store-changelog/SKILL.md) - 通过收集变更内容创建面向用户的App Store发布说明
- [clawdbot-release-check](https://github.com/openclaw/skills/tree/main/skills/pors/clawdbot-release-check/SKILL.md) - 检查clawdbot新版本并在发现更新时通知(每个新版本仅通知一次)
- [copilot-money](https://github.com/openclaw/skills/tree/main/skills/jayhickey/copilot-money/SKILL.md) - 查询Copilot Money个人财务数据(账户、交易、净资产、持仓等)
- [create-content](https://github.com/openclaw/skills/tree/main/skills/itsflow/create-content/SKILL.md) - 将想法转化为平台优化内容的思想伙伴
- [harvey](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/harvey/SKILL.md) - Harvey是一个想象中的朋友和对话伙伴
- [ibkr-trading](https://github.com/openclaw/skills/tree/main/skills/flokiew/ibkr-trader/SKILL.md) - 通过Interactive Brokers(IBKR)Client Portal API实现交易自动化
- [idea](https://github.com/openclaw/skills/tree/main/skills/andrewjiang/idea/SKILL.md) - 启动后台Claude会话来探索和分析商业想法
- [just-fucking-cancel](https://github.com/openclaw/skills/tree/main/skills/chipagosfinest/just-fucking-cancel/SKILL.md) - 分析银行交易CSV文件找出重复收费，分类订阅服务
- [launch-strategy](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/launch-strategy/SKILL.md) - 当用户需要规划产品发布、功能公告或发布策略时使用
- [marketing-ideas](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/marketing-ideas/SKILL.md) - 当用户需要为SaaS或软件产品获取营销创意、灵感或策略时使用
- [nordpool-fi](https://github.com/openclaw/skills/tree/main/skills/ovaris/nordpool-fi/SKILL.md) - 芬兰每小时电价查询及最优电动车充电窗口计算(3小时、4小时、5小时)
- [openssl](https://github.com/openclaw/skills/tree/main/skills/asleep123/openssl/SKILL.md) - 使用OpenSSL生成安全随机字符串、密码和加密令牌
- [page-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/page-cro/SKILL.md) - 当用户需要优化、改进或提高任何营销页面的转化率时使用
- [plaid](https://github.com/openclaw/skills/tree/main/skills/jverdi/plaid/SKILL.md) - plaid-cli用于与Plaid金融平台交互的命令行工具
- [publisher](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/publisher/SKILL.md) - 让你的技能易于理解且不容忽视
- [relationship-skills](https://github.com/openclaw/skills/tree/main/skills/jhillin8/relationship-skills/SKILL.md) - 通过沟通工具、冲突解决方法和连接创意改善人际关系
- [solo-cli](https://github.com/openclaw/skills/tree/main/skills/rursache/solo-cli/SKILL.md) - 通过CLI监控和交互SOLO.ro会计平台
- [swissweather](https://github.com/openclaw/skills/tree/main/skills/xenofex7/swissweather/SKILL.md) - 从MeteoSwiss(瑞士官方气象服务)获取当前天气和预报
- [yahoo-finance](https://github.com/openclaw/skills/tree/main/skills/ajanraj/yahoo-finance/SKILL.md) - 获取股票价格、报价、基本面、收益、期权、股息等信息
- [ynab](https://github.com/openclaw/skills/tree/main/skills/obviyus/ynab/SKILL.md) - 通过CLI管理YNAB预算、账户、类别和交易
- [monarch-money](https://github.com/openclaw/skills/tree/main/skills/davideasaf/monarch-money/SKILL.md) - Monarch Money预算管理和交易追踪
- [tax-professional](https://github.com/openclaw/skills/tree/main/skills/scottfo/tax-professional/SKILL.md) - 美国税务顾问、扣除优化和支出追踪
- [card-optimizer](https://github.com/openclaw/skills/tree/main/skills/scottfo/card-optimizer/SKILL.md) - 信用卡奖励优化器(现金返还、积分和里程)
- [watch-my-money](https://github.com/openclaw/skills/tree/main/skills/andreolf/watch-my-money/SKILL.md) - 分析银行交易、分类支出、追踪预算
- [refund-radar](https://github.com/openclaw/skills/tree/main/skills/andreolf/refund-radar/SKILL.md) - 扫描银行对账单查找重复收费并起草退款请求
- [expense-tracker-pro](https://github.com/openclaw/skills/tree/main/skills/jhillin8/expense-tracker-pro/SKILL.md) - 通过自然语言追踪支出并生成预算摘要
- [financial-market-analysis](https://github.com/openclaw/skills/tree/main/skills/seyhunak/financial-market-analysis/SKILL.md) - 通过Yahoo Finance进行股票和市场情绪分析

</details>

</details>

<details>
<summary><h3 style="display:inline">媒体与流媒体</h3></summary>

- [apple-media](https://github.com/openclaw/skills/tree/main/skills/aaronn/apple-media/SKILL.md) - 通过pyatv控制Apple TV、HomePod和AirPlay设备(扫描、流媒体、播放、音量)
- [blucli](https://github.com/openclaw/skills/tree/main/skills/steipete/blucli/SKILL.md) - BluOS CLI(blu)用于设备发现、播放控制、分组和音量调节
- [chill-institute](https://github.com/openclaw/skills/tree/main/skills/baanish/chill-institute/SKILL.md) - 使用chill.institute(网页界面)搜索内容并点击"发送到put.io"(建议搭配使用)
- [chromecast](https://github.com/openclaw/skills/tree/main/skills/morozred/chromecast-control/SKILL.md) - 控制本地网络中的Chromecast设备 - 发现设备、投射媒体、控制播放
- [lastfm](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/lastfm/SKILL.md) - 访问Last.fm收听历史、音乐统计和发现推荐
- [overseerr](https://github.com/openclaw/skills/tree/main/skills/j1philli/overseerr/SKILL.md) - 通过Overseerr API请求电影/电视节目并监控请求状态(稳定版Overseerr)
- [pet](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/pet/SKILL.md) - 简单的命令行片段管理器，用于保存和复用复杂命令
- [plex](https://github.com/openclaw/skills/tree/main/skills/dbhurley/plex/SKILL.md) - 控制Plex媒体服务器 - 浏览媒体库、搜索、播放媒体、管理播放
- [pocket-casts](https://github.com/openclaw/skills/tree/main/skills/manuelhettich/pocket-casts-yt/SKILL.md) - 下载YouTube视频并上传到Pocket Casts Files以供离线观看
- [putio](https://github.com/openclaw/skills/tree/main/skills/baanish/putio/SKILL.md) - 通过kaput CLI管理put.io账户(传输、文件、搜索) - 升起主帆
- [qbittorrent](https://github.com/openclaw/skills/tree/main/skills/jmagar/qbittorrent/SKILL.md) - 使用qBittorrent管理种子(当用户要求"列出种子"、"添加种子"时使用)
- [radarr](https://github.com/openclaw/skills/tree/main/skills/jordyvandomselaar/radarr/SKILL.md) - 搜索并添加电影到Radarr(支持合集、添加时搜索选项)
- [roku](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/roku/SKILL.md) - 通过python-roku控制Roku设备的CLI接口
- [sabnzbd](https://github.com/openclaw/skills/tree/main/skills/jmagar/sabnzbd/SKILL.md) - 使用SABnzbd管理Usenet下载(当用户要求"检查SABnzbd"、"列出NZB队列"时使用)
- [sonarr](https://github.com/openclaw/skills/tree/main/skills/jordyvandomselaar/sonarr/SKILL.md) - 搜索并添加电视节目到Sonarr(支持监控选项、添加时搜索)
- [sonoscli](https://github.com/openclaw/skills/tree/main/skills/steipete/sonoscli/SKILL.md) - 控制Sonos音响(发现/状态/播放/音量/分组)
- [spotify](https://github.com/openclaw/skills/tree/main/skills/2mawi2/spotify/SKILL.md) - 在macOS上控制Spotify播放(播放/暂停、跳过曲目、调节音量)
- [spotify-applescript](https://github.com/openclaw/skills/tree/main/skills/andrewjiang/spotify-applescript/SKILL.md) - 通过AppleScript控制Spotify桌面应用
- [spotify-history](https://github.com/openclaw/skills/tree/main/skills/braydoncoyer/spotify-history/SKILL.md) - 访问Spotify收听历史、热门艺人/曲目
- [spotify-player](https://github.com/openclaw/skills/tree/main/skills/steipete/spotify-player/SKILL.md) - 通过spogo(首选)或spotify_player在终端进行Spotify播放/搜索
- [spotify-web-api](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/spotify-web-api/SKILL.md) - 通过Web API控制Spotify - 播放、历史记录、热门曲目、搜索
- [summarize](https://github.com/openclaw/skills/tree/main/skills/steipete/summarize/SKILL.md) - 使用summarize CLI摘要URL或文件(网页、PDF、图片、音频、YouTube)
- [thinking-partner](https://github.com/openclaw/skills/tree/main/skills/itsflow/thinking-partner/SKILL.md) - 通过提问探索复杂问题的协作思考伙伴
- [trakt](https://github.com/openclaw/skills/tree/main/skills/mjrussell/trakt/SKILL.md) - 通过trakt.tv追踪和查看已观看的电影和电视节目
- [video-transcript-downloader](https://github.com/openclaw/skills/tree/main/skills/steipete/video-transcript-downloader/SKILL.md) - 从YouTube下载视频、音频、字幕和整理段落式转录文本
- [youtube-instant-article](https://github.com/openclaw/skills/tree/main/skills/viticci/youtube-instant-article/SKILL.md) - 将YouTube视频转换为Telegraph Instant View文章(带视觉幻灯片)
- [youtube-watcher](https://github.com/openclaw/skills/tree/main/skills/michaelgathara/youtube-watcher/SKILL.md) - 获取并阅读YouTube视频的字幕
- [ytmusic](https://github.com/openclaw/skills/tree/main/skills/gentrycopsy/ytmusic/SKILL.md) - YouTube Music媒体库、播放列表和发现功能
- [apple-music](https://github.com/openclaw/skills/tree/main/skills/epheterson/mcp-applemusic/SKILL.md) - 通过AppleScript或MusicKit API集成Apple Music

</details>

<details>
<summary><h3 style="display:inline">笔记与个人知识管理</h3></summary>

- [apple-mail](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-mail/SKILL.md) - macOS上的Apple Mail.app集成(阅读收件箱、搜索邮件、发送邮件、回复)
- [apple-notes](https://github.com/openclaw/skills/tree/main/skills/steipete/apple-notes/SKILL.md) - 在macOS上通过`memo` CLI管理Apple Notes(创建、查看、编辑、删除、搜索、移动)
- [bear-notes](https://github.com/openclaw/skills/tree/main/skills/steipete/bear-notes/SKILL.md) - 通过grizzly CLI创建、搜索和管理Bear笔记
- [better-notion](https://github.com/openclaw/skills/tree/main/skills/tyler6204/better-notion/SKILL.md) - Notion页面、数据库和块的全功能CRUD(创建、读取、更新、删除、搜索和查询)
- [bookstack](https://github.com/openclaw/skills/tree/main/skills/xenofex7/bookstack/SKILL.md) - BookStack Wiki和文档API集成
- [calctl](https://github.com/openclaw/skills/tree/main/skills/rainbat/calctl/SKILL.md) - 通过icalBuddy + AppleScript CLI管理Apple日历事件
- [craft](https://github.com/openclaw/skills/tree/main/skills/noah-ribaudo/craft/SKILL.md) - 通过CLI管理Craft笔记、文档和任务
- [fizzy-cli](https://github.com/openclaw/skills/tree/main/skills/tobiasbischoff/fizzy-cli/SKILL.md) - 使用fizzy-cli工具认证和管理Fizzy看板板、卡片、评论、标签
- [gkeep](https://github.com/openclaw/skills/tree/main/skills/vacinc/gkeep/SKILL.md) - 通过gkeepapi访问Google Keep笔记(列出、搜索、创建和管理笔记)
- [granola](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/granola-notes/SKILL.md) - 访问Granola AI会议笔记(CSV导入、共享笔记获取)
- [nb](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/nb/SKILL.md) - 使用nb CLI管理笔记、书签和笔记本
- [Notebook](https://github.com/openclaw/skills/tree/main/skills/thesethrose/notebook/SKILL.md) - 本地优先的个人知识库(用于追踪想法、项目、任务、习惯)
- [notectl](https://github.com/openclaw/skills/tree/main/skills/rainbat/notectl/SKILL.md) - 通过AppleScript CLI管理Apple Notes
- [notion](https://github.com/openclaw/skills/tree/main/skills/steipete/notion/SKILL.md) - Notion API(用于创建和管理页面、数据库和块)
- [obsidian](https://github.com/openclaw/skills/tree/main/skills/steipete/obsidian/SKILL.md) - 处理Obsidian仓库(纯Markdown笔记)并通过obsidian-cli自动化
- [obsidian-conversation-backup](https://github.com/openclaw/skills/tree/main/skills/laserducktales/obsidian-conversation-backup/SKILL.md) - Obsidian自动对话备份系统(带增量快照、每小时分解)
- [obsidian-daily](https://github.com/openclaw/skills/tree/main/skills/bastos/obsidian-daily/SKILL.md) - 通过obsidian-cli管理Obsidian每日笔记
- [onboarding-cro](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/onboarding-cro/SKILL.md) - 当用户需要优化注册后引导、用户激活或首次使用体验时使用
- [purelymail](https://github.com/openclaw/skills/tree/main/skills/dbhurley/purelymail/SKILL.md) - 为Clawdbot代理设置和测试PurelyMail电子邮件
- [resend](https://github.com/openclaw/skills/tree/main/skills/mjrussell/resend/SKILL.md) - 通过Resend API管理接收(入站)邮件和附件
- [second-brain](https://github.com/openclaw/skills/tree/main/skills/christinetyip/second-brain/SKILL.md) - 由Ensue驱动的个人知识库(用于捕获和检索理解)
- [shared-memory](https://github.com/openclaw/skills/tree/main/skills/christinetyip/shared-memory/SKILL.md) - 与其他用户共享记忆和状态
- [skillcraft](https://github.com/openclaw/skills/tree/main/skills/jmz1/skillcraft/SKILL.md) - 创建、设计和打包Clawdbot技能
- [sports-ticker](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/sports-ticker/SKILL.md) - 足球、NFL、NBA、NHL、MLB、F1等赛事的实时体育提醒
- [reflect](https://github.com/openclaw/skills/tree/main/skills/sergical/reflect/SKILL.md) - 在Reflect应用中追加到每日笔记并创建笔记
- [notion-api](https://github.com/openclaw/skills/tree/main/skills/timenotspace/notion-api/SKILL.md) - Notion API CLI(搜索、查询数据库、创建页面)
- [granola](https://github.com/openclaw/skills/tree/main/skills/scald/granola/SKILL.md) - 访问Granola会议转录和笔记
- [fabric-api](https://github.com/openclaw/skills/tree/main/skills/tristanmanchester/fabric-api/SKILL.md) - 通过HTTP API创建/搜索Fabric资源(记事本、文件夹、书签、文件)
- [instapaper](https://github.com/openclaw/skills/tree/main/skills/vburojevic/instapaper/SKILL.md) - 当操作instapaper-cli(ip)工具或故障排除时使用(认证等)
- [karakeep](https://github.com/openclaw/skills/tree/main/skills/jayphen/karakeep/SKILL.md) - 在Karakeep实例中管理书签和链接
- [linkding](https://github.com/openclaw/skills/tree/main/skills/jmagar/linkding/SKILL.md) - 使用Linkding管理书签(当用户要求"保存书签"、"添加链接"时使用)
- [readeck](https://github.com/openclaw/skills/tree/main/skills/jayphen/readeck/SKILL.md) - Readeck集成(用于保存和管理文章)
- [readwise](https://github.com/openclaw/skills/tree/main/skills/refrigerator/readwise/SKILL.md) - 访问Readwise高亮和Reader保存的文章
- [twitter-bookmark-sync](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/twitter-bookmark-sync/SKILL.md) - 自动每日排名Twitter书签并交付精选阅读清单
- [raindrop](https://github.com/openclaw/skills/tree/main/skills/velvet-shark/raindrop/SKILL.md) - Raindrop.io书签(搜索、列表、添加、用标签组织)
- [substack-formatter](https://github.com/openclaw/skills/tree/main/skills/maddiedreese/substack-formatter/SKILL.md) - 将文本转换为Substack文章格式(带HTML格式)
- [bbc-news](https://github.com/openclaw/skills/tree/main/skills/ddrayne/bbc-news/SKILL.md) - 通过RSS源获取和显示BBC新闻故事(来自不同板块和地区)
- [blogwatcher](https://github.com/openclaw/skills/tree/main/skills/steipete/blogwatcher/SKILL.md) - 使用blogwatcher CLI监控博客和RSS/Atom源的更新
- [hn](https://github.com/openclaw/skills/tree/main/skills/dbhurley/hn/SKILL.md) - 浏览Hacker News(热门故事、最新、最佳、问答、展示、工作和带评论的故事详情)
- [hn-digest](https://github.com/openclaw/skills/tree/main/skills/cpojer/hn-digest/SKILL.md) - 按需获取和发送Hacker News首页帖子
- [miniflux](https://github.com/openclaw/skills/tree/main/skills/shekohex/miniflux/SKILL.md) - 浏览、阅读和管理Miniflux源文章
- [news-summary](https://github.com/openclaw/skills/tree/main/skills/joargp/news-summary/SKILL.md) - 当用户要求新闻更新、每日简报时使用此技能
- [newsletter-digest](https://github.com/openclaw/skills/tree/main/skills/jhillin8/newsletter-digest/SKILL.md) - 摘要新闻简报和文章，提取关键见解，创建阅读清单
- [orf-digest](https://github.com/openclaw/skills/tree/main/skills/cpojer/orf/SKILL.md) - 德语按需ORF新闻摘要(当用户说'orf'、'pull orf'或'orf 10'时使用)

</details>

<details>
<summary><h3 style="display:inline">交通出行</h3></summary>

- [anachb](https://github.com/openclaw/skills/tree/main/skills/manmal/a-nach-b/SKILL.md) - 奥地利公共交通(VOR AnachB)覆盖全奥地利
- [charger](https://github.com/openclaw/skills/tree/main/skills/borahm/charger/SKILL.md) - 通过Google Places检查电动车充电桩可用性(收藏夹、附近搜索)
- [flight-tracker](https://github.com/openclaw/skills/tree/main/skills/xenofex7/flight-tracker/SKILL.md) - 航班追踪和调度。按地区、呼号实时追踪航班
- [flights](https://github.com/openclaw/skills/tree/main/skills/dbhurley/flights/SKILL.md) - 追踪航班状态、延误和搜索航线。使用FlightAware数据
- [gotrain](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/gotrain/SKILL.md) - MTA系统列车发车时间(纽约地铁、长岛铁路、大都会北方铁路)
- [incident-pcn-evidence-appeal-corrective-actions-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/incident-pcn-evidence-appeal-corrective-actions-uk/SKILL.md) - 构建事件/PCN证据包(含时间线、申诉草稿、纠正措施)
- [mbta](https://github.com/openclaw/skills/tree/main/skills/dbhurley/mbta/SKILL.md) - 波士顿地区地铁、公交、通勤铁路和渡轮的实时MBTA交通预测
- [oebb-scotty](https://github.com/openclaw/skills/tree/main/skills/manmal/oebb-scotty/SKILL.md) - 奥地利铁路旅行规划器(ÖBB Scotty)
- [openerz](https://github.com/openclaw/skills/tree/main/skills/mbjoern/erz-entsorgung-recycling-zurich/SKILL.md) - 通过OpenERZ API获取苏黎世垃圾回收日历
- [railil](https://github.com/openclaw/skills/tree/main/skills/lirantal/railil/SKILL.md) - 使用railil CLI搜索以色列铁路列车时刻表
- [rejseplanen](https://github.com/openclaw/skills/tree/main/skills/bjarkehs/rejseplanen/SKILL.md) - 通过Rejseplanen API查询丹麦公共交通发车、到达和行程规划
- [skanetrafiken](https://github.com/openclaw/skills/tree/main/skills/rezkam/skanetrafiken/SKILL.md) - 斯科讷公共交通行程规划器(Skånetrafiken)。规划公交/火车行程(含实时延误)
- [swiss-geo](https://github.com/openclaw/skills/tree/main/skills/mbjoern/swiss-geo-and-tourism-assistant/SKILL.md) - 瑞士地理数据和旅游景点。搜索地点/地址，查询海拔
- [swiss-phone-directory](https://github.com/openclaw/skills/tree/main/skills/xenofex7/swiss-phone-directory/SKILL.md) - 通过search.ch API查询瑞士电话目录
- [swiss-transport](https://github.com/openclaw/skills/tree/main/skills/xenofex7/swiss-transport/SKILL.md) - 瑞士公共交通实时信息
- [tachograph-infringement-triage-root-cause-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/tachograph-infringement-triage-root-cause-uk/SKILL.md) - 分类速度记录仪违规，识别常见模式
- [tesla](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/tesla/SKILL.md) - 控制特斯拉车辆 - 锁定/解锁、空调、位置、充电状态等
- [tesla-commands](https://github.com/openclaw/skills/tree/main/skills/ovaris/tesla-commands/SKILL.md) - 通过MyTeslaMate API控制特斯拉。支持多车辆账户、空调控制
- [tessie](https://github.com/openclaw/skills/tree/main/skills/baanish/tessie/SKILL.md) - Tessie特斯拉控制应用
- [tfl-journey-disruption](https://github.com/openclaw/skills/tree/main/skills/diegopetrucci/transport-for-london-journey-disruption/SKILL.md) - 规划伦敦交通局行程(起点/终点/时间)，解析位置(优先邮编)
- [transport-investigation-acas-aligned-pack](https://github.com/openclaw/skills/tree/main/skills/kowl64/transport-investigation-acas-aligned-pack/SKILL.md) - 生成ACAS对齐的调查邀请措辞、中性问题集和证据日志
- [trimet](https://github.com/openclaw/skills/tree/main/skills/mjrussell/trimet/SKILL.md) - 获取波特兰交通信息(包括到站时间、行程规划和警报)
- [virus-monitor](https://github.com/openclaw/skills/tree/main/skills/pasogott/virus-monitor/SKILL.md) - 维也纳病毒监测(废水和哨点监测)
- [wienerlinien](https://github.com/openclaw/skills/tree/main/skills/hjanuschka/wienerlinien/SKILL.md) - 维也纳公共交通(Wiener Linien)实时数据
- [uk-trains](https://github.com/openclaw/skills/tree/main/skills/jabbslad/uk-trains/SKILL.md) - 英国国家铁路发车、到达、延误、站台信息
- [trein](https://github.com/openclaw/skills/tree/main/skills/joehoel/trein/SKILL.md) - 荷兰铁路(NS)发车、行程、中断信息
- [bahn](https://github.com/openclaw/skills/tree/main/skills/tobiasbischoff/bahn/SKILL.md) - 德国铁路列车连接和旅行规划
- [railil](https://github.com/openclaw/skills/tree/main/skills/lirantal/skill-railil/SKILL.md) - 以色列铁路列车时刻表(带模糊车站搜索)
- [wheels-router](https://github.com/openclaw/skills/tree/main/skills/anscg/wheels-router/SKILL.md) - 通过Transitous进行全球公共交通规划
- [flight-tracker](https://github.com/openclaw/skills/tree/main/skills/copey02/aviationstack-flight-tracker/SKILL.md) - 实时航班追踪(含登机口信息和延误)
- [aviation-weather](https://github.com/openclaw/skills/tree/main/skills/dimitryvin/aviation-weather/SKILL.md) - 航空天气：METAR、TAF、PIREPs(用于飞行计划)
- [travel-concierge](https://github.com/openclaw/skills/tree/main/skills/arein/travel-concierge/SKILL.md) - 查找Airbnb、Booking.com、VRBO房源的联系方式
- [surfline](https://github.com/openclaw/skills/tree/main/skills/miguelcarranza/surfline/SKILL.md) - Surfline提供的冲浪预报和条件
- [mechanic](https://github.com/openclaw/skills/tree/main/skills/scottfo/mechanic/SKILL.md) - 车辆维护追踪器(含保养间隔和召回信息)

</details>

<details>
<summary><h3 style="display:inline">个人成长</h3></summary>

- [daily-review](https://github.com/openclaw/skills/tree/main/skills/henrino3/daily-review/SKILL.md) - 包含沟通追踪和会议分析的全面每日绩效回顾
- [drivers-hours-wtd-infringement-coach-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/drivers-hours-wtd-infringement-coach-uk/SKILL.md) - 创建面向司机的1页式速度记录仪/WTD违规说明(含纠正措施和复查日期)
- [graphiti](https://github.com/openclaw/skills/tree/main/skills/emasoudy/graphiti/SKILL.md) - 通过Graphiti API进行知识图谱操作
- [morning-routine](https://github.com/openclaw/skills/tree/main/skills/jhillin8/morning-routine/SKILL.md) - 建立高效的晨间习惯(含习惯清单、时间安排和连续打卡追踪)
- [munger-observer](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/munger-observer/SKILL.md) - 应用查理·芒格的思维模型每日检视工作和思考
- [night-routine](https://github.com/openclaw/skills/tree/main/skills/jhillin8/night-routine/SKILL.md) - 建立放松的夜间习惯(含放松活动、睡眠准备和次日计划)
- [overcome-problem](https://github.com/openclaw/skills/tree/main/skills/jhillin8/overcome-problem/SKILL.md) - 用结构化思维分解问题(含行动计划制定和进度追踪)
- [procrastination-buster](https://github.com/openclaw/skills/tree/main/skills/jhillin8/procrastination-buster/SKILL.md) - 战胜拖延症(任务分解、2分钟启动法和责任追踪)
- [quit-alcohol](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-alcohol/SKILL.md) - 追踪戒酒进度(无酒精天数、渴望管理和康复里程碑)
- [quit-caffeine](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-caffeine/SKILL.md) - 减少或戒除咖啡因(戒断追踪、渐进计划和能量里程碑)
- [quit-overspending](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-overspending/SKILL.md) - 戒除冲动消费(消费天数追踪、冲动记录和储蓄里程碑)
- [quit-porn](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-porn/SKILL.md) - 戒除色情成瘾(无接触天数、渴望管理和康复里程碑)
- [quit-smoking](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-smoking/SKILL.md) - 戒烟(无烟天数追踪、渴望支持和健康恢复时间线)
- [quit-vaping](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-vaping/SKILL.md) - 戒除电子烟(无尼古丁天数追踪、渴望工具和健康里程碑)
- [quit-weed](https://github.com/openclaw/skills/tree/main/skills/jhillin8/quit-weed/SKILL.md) - 戒除大麻(无接触天数追踪和渴望支持)
- [self-love-confidence](https://github.com/openclaw/skills/tree/main/skills/jhillin8/self-love-confidence/SKILL.md) - 建立自爱和自信(肯定语、胜利记录和内在批评管理)
- [social-media-detox](https://github.com/openclaw/skills/tree/main/skills/jhillin8/social-media-detox/SKILL.md) - 戒除社交媒体成瘾(无屏幕天数、冲动记录和数字健康)
- [stress-relief](https://github.com/openclaw/skills/tree/main/skills/jhillin8/stress-relief/SKILL.md) - 管理压力(快速技巧、压力记录和恢复工具)
- [study-habits](https://github.com/openclaw/skills/tree/main/skills/jhillin8/study-habits/SKILL.md) - 建立高效学习习惯(间隔重复、主动回忆和学习会话追踪)
- [therapy-mode](https://github.com/openclaw/skills/tree/main/skills/thesethrose/therapy-mode/SKILL.md) - 全面的AI辅助治疗支持框架
- [weekly-synthesis](https://github.com/openclaw/skills/tree/main/skills/itsflow/weekly-synthesis/SKILL.md) - 创建一周工作和思考的全面综合报告
- [wellness-skills](https://github.com/openclaw/skills/tree/main/skills/jhillin8) - 12项健康技能：焦虑缓解、冥想、习惯追踪、禁食、感恩、自律、动机等
- [thinking-frameworks](https://github.com/openclaw/skills/tree/main/skills/artyomx33) - 6种思维框架：第一性原理、逆向思维、JTBD、事前剖析、交叉授粉、推理角色
- [adhd-body-doubling](https://github.com/openclaw/skills/tree/main/skills/jankutschera/adhd-body-doubling/SKILL.md) - 朋克风格的ADHD陪伴工作法(专注会话)
- [fix-life-in-1-day](https://github.com/openclaw/skills/tree/main/skills/evgyur/fix-life-in-1-day/SKILL.md) - 基于Dan Koe方法的10个心理疗愈课程
- [daily-review-ritual](https://github.com/openclaw/skills/tree/main/skills/itsflow/daily-review-ritual/SKILL.md) - 每日回顾仪式(记录进展并规划明天)
- [whatdo](https://github.com/openclaw/skills/tree/main/skills/scottfo/whatdo/SKILL.md) - 活动发现(含天气、电影时间、流媒体和群组档案)

</details>

<details>
<summary><h3 style="display:inline">健康与健身</h3></summary>

- [endurance-coach](https://github.com/openclaw/skills/tree/main/skills/shiv19/endurance-coach/SKILL.md) - 创建个性化的铁人三项、马拉松和超耐力训练计划
- [fitbit](https://github.com/openclaw/skills/tree/main/skills/mjrussell/fitbit/SKILL.md) - 查询Fitbit健康数据(包括睡眠、心率、活动、血氧饱和度和呼吸频率)
- [fitbit-analytics](https://github.com/openclaw/skills/tree/main/skills/kesslerio/fitbit-analytics/SKILL.md) - Fitbit健康和健身数据集成
- [hevy](https://github.com/openclaw/skills/tree/main/skills/mjrussell/hevy/SKILL.md) - 从Hevy查询锻炼数据(包括训练、常规、练习和历史记录)
- [huckleberry](https://github.com/openclaw/skills/tree/main/skills/jayhickey/huckleberry/SKILL.md) - 通过Huckleberry CLI追踪婴儿睡眠、喂养、尿布和成长数据
- [muscle-gain](https://github.com/openclaw/skills/tree/main/skills/jhillin8/muscle-gain/SKILL.md) - 追踪肌肉增长(重量进展、蛋白质追踪和力量里程碑)
- [oura](https://github.com/openclaw/skills/tree/main/skills/ruhrpotter/oura/SKILL.md) - Oura健康戒指数据访问
- [oura-analytics](https://github.com/openclaw/skills/tree/main/skills/kesslerio/oura-analytics/SKILL.md) - Oura Ring数据集成和分析
- [pregnancy-tracker](https://github.com/openclaw/skills/tree/main/skills/jhillin8/pregnancy-tracker/SKILL.md) - 追踪孕期旅程(每周更新、症状记录和里程碑倒计时)
- [ranked-gym](https://github.com/openclaw/skills/tree/main/skills/jhillin8/ranked-gym/SKILL.md) - 游戏化健身训练(经验值、等级、成就和训练连续打卡)
- [strava](https://github.com/openclaw/skills/tree/main/skills/bohdanpodvirnyi/strava/SKILL.md) - 使用Strava API加载和分析Strava活动、统计数据和训练
- [testosterone-optimization](https://github.com/openclaw/skills/tree/main/skills/jhillin8/testosterone-optimization/SKILL.md) - 优化自然睾酮水平(睡眠、锻炼、营养和生活方式追踪)
- [the-sports-db](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/the-sports-db/SKILL.md) - 通过TheSportsDB访问体育数据(球队、赛事、比分)
- [weight-loss](https://github.com/openclaw/skills/tree/main/skills/jhillin8/weight-loss/SKILL.md) - 追踪减重旅程(体重记录、趋势分析和目标里程碑)
- [whoop](https://github.com/openclaw/skills/tree/main/skills/borahm/whoop/SKILL.md) - WHOOP晨间检查(恢复/睡眠/压力)并提供建议
- [whoop-morning](https://github.com/openclaw/skills/tree/main/skills/borahm/whoop-morning/SKILL.md) - 每天早晨检查WHOOP恢复/睡眠/压力数据并发送建议
- [whoopskill](https://github.com/openclaw/skills/tree/main/skills/koala73/whoopskill/SKILL.md) - WHOOP CLI(健康洞察、趋势分析和数据获取：睡眠、恢复、HRV、压力)
- [workout](https://github.com/openclaw/skills/tree/main/skills/gricha/workout/SKILL.md) - 使用workout-cli追踪训练、记录组数、管理练习和模板
- [workout-logger](https://github.com/openclaw/skills/tree/main/skills/jhillin8/workout-logger/SKILL.md) - 记录训练、追踪进度、获取练习建议和PR追踪
- [garmin-health](https://github.com/openclaw/skills/tree/main/skills/eversonl/garmin-health-analysis/SKILL.md) - Garmin数据：睡眠、HRV、最大摄氧量、身体电量、训练准备度
- [whoop-health](https://github.com/openclaw/skills/tree/main/skills/rodrigouroz/whoop-health-analysis/SKILL.md) - Whoop健康数据(含交互式图表和可视化)
- [oura-ring](https://github.com/openclaw/skills/tree/main/skills/sameerbajaj/oura-ring-skill/SKILL.md) - Oura Ring准备度、睡眠评分和7天趋势
- [strava-cycling](https://github.com/openclaw/skills/tree/main/skills/ericrosenberg/strava-cycling-coach/SKILL.md) - Strava骑行表现分析和教练洞察
- [who-growth-charts](https://github.com/openclaw/skills/tree/main/skills/odrobnik/who-growth-charts/SKILL.md) - WHO儿童生长图表(含百分位曲线)
- [intervals-icu](https://github.com/openclaw/skills/tree/main/skills/pseuss/intervals-icu-api/SKILL.md) - Intervals.icu训练数据：活动、训练、健康指标

</details>

<details>
<summary><h3 style="display:inline">通讯</h3></summary>

- [apple-mail-search-safe](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/apple-mail-search-safe/SKILL.md) - 快速安全的Apple邮件搜索(支持正文内容)
- [beeper](https://github.com/openclaw/skills/tree/main/skills/krausefx/beeper/SKILL.md) - 搜索和浏览本地Beeper聊天历史(线程、消息、全文搜索)
- [camelcamelcamel-alerts](https://github.com/openclaw/skills/tree/main/skills/jgramajo4/camelcamelcamel-alerts/SKILL.md) - 通过RSS监控CamelCamelCamel价格下降提醒，并在商品降价时发送Telegram通知
- [discord-doctor](https://github.com/openclaw/skills/tree/main/skills/jhillock/discord-doctor/SKILL.md) - Discord机器人、网关、OAuth令牌和旧版配置问题的快速诊断和修复
- [google-chat](https://github.com/openclaw/skills/tree/main/skills/darconada/google-chat/SKILL.md) - 通过webhooks或OAuth向Google Chat空间和用户发送消息
- [himalaya](https://github.com/openclaw/skills/tree/main/skills/lamelas/himalaya/SKILL.md) - 通过IMAP/SMTP管理邮件的CLI工具。使用`himalaya`列出、阅读、撰写、回复、转发、搜索邮件
- [imsg](https://github.com/openclaw/skills/tree/main/skills/steipete/imsg/SKILL.md) - iMessage/SMS CLI工具(列出聊天、历史记录、监控和发送消息)
- [linkedin](https://github.com/openclaw/skills/tree/main/skills/biostartechnology/linkedin/SKILL.md) - 通过浏览器中继或cookies实现LinkedIn自动化(消息发送、资料查看)
- [linkedin-cli](https://github.com/openclaw/skills/tree/main/skills/arun-8687/linkedin-cli/SKILL.md) - 类似bird的LinkedIn CLI工具(搜索资料、检查消息)
- [ms365](https://github.com/openclaw/skills/tree/main/skills/cvsloane/ms365/SKILL.md) - Microsoft 365集成工具
- [paid-ads](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/paid-ads/SKILL.md) - 当用户需要Google Ads、Meta(Facebook/Instagram)等平台的付费广告活动帮助时使用
- [protonmail](https://github.com/openclaw/skills/tree/main/skills/durchblick-nl/protonmail/SKILL.md) - 通过IMAP桥接(Proton Bridge或hydroxide)阅读、搜索和扫描ProtonMail
- [social-content](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/references/social-content/SKILL.md) - 当用户需要创建、安排或优化社交媒体内容时使用
- [table-image](https://github.com/openclaw/skills/tree/main/skills/joargp/table-image/SKILL.md) - 从表格生成图像，提高Telegram等消息应用中的可读性
- [telegram-usage](https://github.com/openclaw/skills/tree/main/skills/c-drew/telegram-usage/SKILL.md) - 显示会话使用统计(配额、会话时间、令牌、上下文)
- [wacli](https://github.com/openclaw/skills/tree/main/skills/steipete/wacli/SKILL.md) - 向他人发送WhatsApp消息或搜索/同步WhatsApp历史记录
- [webchat-audio-notifications](链接) - 网页聊天的浏览器音频通知(5种强度级别、自定义声音和智能标签检测)
- [whatsapp-video-mockup](https://github.com/openclaw/skills/tree/main/skills/danpeg/whatsapp-video-mockup/SKILL.md) - WhatsApp视频模拟工具
- [postiz](https://github.com/openclaw/skills/tree/main/skills/nevo-david/postiz/SKILL.md) - 向28+个频道安排帖子发布：X、LinkedIn、Reddit、Instagram、TikTok等
- [walkie-talkie](https://github.com/openclaw/skills/tree/main/skills/rubenfb23/walkie-talkie/SKILL.md) - WhatsApp语音对话：转录音频，使用TTS回复
- [claw-me-maybe](https://github.com/openclaw/skills/tree/main/skills/nickhamze/claw-me-maybe/SKILL.md) - Beeper集成：WhatsApp、Telegram、Signal、Discord、Slack、iMessage、LinkedIn
- [tootbot](https://github.com/openclaw/skills/tree/main/skills/behrangsa/tootbot/SKILL.md) - 向Mastodon发布内容
- [upload-post](https://github.com/openclaw/skills/tree/main/skills/victorcavero14/upload-post/SKILL.md) - 上传到TikTok、Instagram、YouTube、LinkedIn、Facebook、X等平台
- [gram](https://github.com/openclaw/skills/tree/main/skills/arein/gram/SKILL.md) - Instagram CLI(动态、帖子、个人资料、互动)
- [reddit-cli](https://github.com/openclaw/skills/tree/main/skills/kelsia14/reddit-cli/SKILL.md) - 用于浏览帖子和子论坛的Reddit CLI工具
- [discord-voice](https://github.com/openclaw/skills/tree/main/skills/avatarneil/discord-voice/SKILL.md) - 在Discord中进行实时语音对话(与Claude AI集成)

</details>

<details>
<summary><h3 style="display:inline">语音与转录</h3></summary>

- [assemblyai-transcribe](https://github.com/openclaw/skills/tree/main/skills/tristanmanchester/assemblyai-transcribe/SKILL.md) - 使用AssemblyAI转录音频/视频(支持本地上传)
- [audio-gen](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/audio-gen/SKILL.md) - 按需生成有声书、播客或教育音频内容
- [audio-reply](https://github.com/openclaw/skills/tree/main/skills/matrixy/audio-reply-skill/SKILL.md) - 使用TTS生成音频回复。通过"read it to me [URL]"触发
- [edge-tts](https://github.com/openclaw/skills/tree/main/skills/i3130002/edge-tts/SKILL.md) - 边缘TTS服务
- [gettr-transcribe-summarize](https://github.com/openclaw/skills/tree/main/skills/kevin37li/gettr-transcribe-summarize/SKILL.md) - 从GETTR帖子下载音频(通过HTML og:video)，本地转录并总结
- [llmwhisperer](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/llmwhisperer/SKILL.md) - 使用LLMWhisperer API从图像和PDF中提取文本和布局
- [local-whisper](https://github.com/openclaw/skills/tree/main/skills/araa47/local-whisper/SKILL.md) - 使用OpenAI Whisper进行本地语音转文本。模型下载后完全离线运行
- [mlx-whisper](https://github.com/openclaw/skills/tree/main/skills/kevin37li/mlx-whisper/SKILL.md) - 使用MLX Whisper进行本地语音转文本(Apple Silicon优化，无需API密钥)
- [openai-whisper](https://github.com/openclaw/skills/tree/main/skills/steipete/openai-whisper/SKILL.md) - 使用Whisper CLI进行本地语音转文本(无需API密钥)
- [openai-whisper-api](https://github.com/openclaw/skills/tree/main/skills/steipete/openai-whisper-api/SKILL.md) - 通过OpenAI音频转录API(Whisper)转录音频
- [parakeet-mlx](https://github.com/openclaw/skills/tree/main/skills/kylehowells/parakeet-mlx/SKILL.md) - 使用Parakeet MLX(ASR)进行本地语音转文本，适用于Apple Silicon(无需API密钥)
- [parakeet-stt](https://github.com/openclaw/skills/tree/main/skills/carlulsoe/parakeet-stt/SKILL.md) - 鹦鹉语音转文本工具
- [pocket-transcripts](https://github.com/openclaw/skills/tree/main/skills/tmustier/heypocket-reader/SKILL.md) - 从Pocket AI(heypocket.com)录音设备读取转录文本和摘要
- [pocket-tts](https://github.com/openclaw/skills/tree/main/skills/sherajdev/pocket-tts/SKILL.md) - Pocket文本转语音服务
- [tts-whatsapp](https://github.com/openclaw/skills/tree/main/skills/hopyky/tts-whatsapp/SKILL.md) - 在WhatsApp上发送高质量文本转语音消息，支持40+种语言，自动发送
- [video-subtitles](https://github.com/openclaw/skills/tree/main/skills/ngutman/video-subtitles/SKILL.md) - 从视频/音频生成SRT字幕，支持翻译功能
- [voice-transcribe](https://github.com/openclaw/skills/tree/main/skills/darinkishore/voice-transcribe/SKILL.md) - 使用OpenAI的gpt-4o-mini-transcribe模型转录音频文件，支持词汇提示
- [elevenlabs-voices](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/elevenlabs-voices/SKILL.md) - ElevenLabs语音合成：18种人格，32种语言，音效
- [elevenlabs-media](https://github.com/openclaw/skills/tree/main/skills/clawdbotborges) - ElevenLabs音乐生成和语音转文本(Scribe v2)
- [elevenlabs-agents](https://github.com/openclaw/skills/tree/main/skills/pennyroyaltea/elevenlabs-agents/SKILL.md) - 创建和管理ElevenLabs对话AI代理
- [tts](https://github.com/openclaw/skills/tree/main/skills/amstko/tts/SKILL.md) - 使用Hume AI或OpenAI API进行文本转语音

</details>

<details>
<summary><h3 style="display:inline">智能家居与物联网</h3></summary>

- [anova-oven](https://github.com/openclaw/skills/tree/main/skills/dodeja/anova-skill/SKILL.md) - 通过WiFi WebSocket API控制Anova精密烤箱和精密烹饪机(真空低温烹饪)
- [bambu-cli](https://github.com/openclaw/skills/tree/main/skills/tobiasbischoff/bambu-cli/SKILL.md) - 使用bambu-cli操作和排查BambuLab 3D打印机问题(状态/监控)
- [beestat](https://github.com/openclaw/skills/tree/main/skills/mjrussell/beestat/SKILL.md) - 通过Beestat API查询ecobee恒温器数据(温度、湿度、空气质量CO2等)
- [dyson-cli](https://github.com/openclaw/skills/tree/main/skills/tmustier/dyson-cli/SKILL.md) - 通过本地MQTT控制Dyson空气净化器、风扇和加热器
- [eightctl](https://github.com/openclaw/skills/tree/main/skills/steipete/eightctl/SKILL.md) - 控制Eight Sleep智能床垫(状态、温度、闹钟、日程)
- [google-home](https://github.com/openclaw/skills/tree/main/skills/mitchellbernstein/google-home/SKILL.md) - 控制Google Nest设备(恒温器、摄像头、门铃)
- [govee-lights](https://github.com/openclaw/skills/tree/main/skills/joeynyc/govee-lights/SKILL.md) - 通过Govee API控制Govee智能灯具
- [homeassistant](https://github.com/openclaw/skills/tree/main/skills/dbhurley/homeassistant/SKILL.md) - 控制Home Assistant - 智能插座、灯光、场景、自动化
- [homey](https://github.com/openclaw/skills/tree/main/skills/maxsumrall/homey/SKILL.md) - 通过本地(LAN/VPN)或云API控制Athom Homey智能家居设备
- [homey-cli](https://github.com/openclaw/skills/tree/main/skills/krausefx/homey-cli/SKILL.md) - 通过CLI控制Homey家庭自动化中心
- [nanoleaf](https://github.com/openclaw/skills/tree/main/skills/rstierli/nanoleaf/SKILL.md) - 通过Picoleaf CLI控制Nanoleaf光板
- [nest-devices](https://github.com/openclaw/skills/tree/main/skills/amogower/nest-devices/SKILL.md) - 通过Device Access API控制Nest智能家居设备(恒温器、摄像头、门铃)
- [openhue](https://github.com/openclaw/skills/tree/main/skills/steipete/openhue/SKILL.md) - 通过OpenHue CLI控制Philips Hue灯具/场景
- [pihole](https://github.com/openclaw/skills/tree/main/skills/baanish/pihole/SKILL.md) - Pi-hole广告拦截器管理
- [printer](https://github.com/openclaw/skills/tree/main/skills/dhvanilpatel/printer/SKILL.md) - 在macOS上通过CUPS管理打印机(发现、添加、打印、队列、状态、唤醒)
- [voicemonkey](https://github.com/openclaw/skills/tree/main/skills/jayakumark/voicemonkey/SKILL.md) - 通过VoiceMonkey API v2控制Alexa设备 - 发布公告、触发例程、启动流程
- [tesla-fleet-api](https://github.com/openclaw/skills/tree/main/skills/odrobnik/tesla-fleet-api/SKILL.md) - Tesla Fleet API: HVAC控制、充电管理、唤醒车辆、OAuth流程
- [lg-thinq](https://github.com/openclaw/skills/tree/main/skills/kaiofreitas/lg-thinq/SKILL.md) - 控制LG智能家电: 冰箱、洗衣机、烘干机、空调
- [bambu-local](https://github.com/openclaw/skills/tree/main/skills/tanguyvans/bambu-local/SKILL.md) - 通过MQTT本地控制Bambu Lab 3D打印机
- [netatmo](https://github.com/openclaw/skills/tree/main/skills/florianbeer/netatmo/SKILL.md) - Netatmo恒温器控制和气象站数据
- [starlink](https://github.com/openclaw/skills/tree/main/skills/danfedick/starlink/SKILL.md) - Starlink卫星天线: 状态、速度测试、WiFi客户端、收起/展开
- [homebridge](https://github.com/openclaw/skills/tree/main/skills/jiasenl/clawdbot-skill-homebridge/SKILL.md) - 通过Homebridge REST API控制智能家居设备
- [robo-rock](https://github.com/openclaw/skills/tree/main/skills/dru-ca/robo-rock/SKILL.md) - 控制Roborock扫地机器人: 清洁、地图、耗材
- [home-music](https://github.com/openclaw/skills/tree/main/skills/asteinberger/home-music/SKILL.md) - 全屋音乐场景(Spotify + Airfoil扬声器)
- [enzoldhazam](https://github.com/openclaw/skills/tree/main/skills/daniel-laszlo/enzoldhazam/SKILL.md) - NGBS iCON智能家居恒温器控制
- [little-snitch](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/little-snitch/SKILL.md) - macOS上的Little Snitch防火墙控制
- [daily-recap](https://github.com/openclaw/skills/tree/main/skills/dbhurley/daily-recap/SKILL.md) - 生成每日回顾图片(你的AI助手举着记录成就的公告板)
- [snow-report](https://github.com/openclaw/skills/tree/main/skills/davemorin/snow-report/SKILL.md) - 获取全球任何滑雪胜地的雪况、预报和滑雪报告
- [weather](https://github.com/openclaw/skills/tree/main/skills/steipete/weather/SKILL.md) - 获取当前天气和预报(无需API密钥)
- [weather-pollen](https://github.com/openclaw/skills/tree/main/skills/thesethrose/weather-pollen/SKILL.md) - 使用免费API获取任何位置的天气和花粉报告
- [weathercli](https://github.com/openclaw/skills/tree/main/skills/pjtf93/weathercli/SKILL.md) - 获取全球任何位置的当前天气状况和预报

</details>

<details>
<summary><h3 style="display:inline">购物与电子商务</h3></summary>

- [anylist](https://github.com/openclaw/skills/tree/main/skills/mjrussell/anylist/SKILL.md) - 通过AnyList管理杂货和购物清单
- [bring-shopping](https://github.com/openclaw/skills/tree/main/skills/cutzenfriend/bring-shopping/SKILL.md) - 通过非官方的bring-shopping Node.js库管理Bring!购物清单
- [checkers-sixty60](https://github.com/openclaw/skills/tree/main/skills/snopoke/checkers-sixty60/SKILL.md) - 通过浏览器自动化在Checkers.co.za Sixty60配送服务上购物
- [event-planner](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/event-planner/SKILL.md) - 规划活动(夜生活、周末、约会之夜、团队出游、用餐、旅行)通过搜索场所
- [food-order](https://github.com/openclaw/skills/tree/main/skills/steipete/food-order/SKILL.md) - 重新订购Foodora订单并通过ordercli跟踪预计到达时间/状态
- [grocery-list](https://github.com/openclaw/skills/tree/main/skills/dbhurley/grocery-list/SKILL.md) - 独立的杂货清单、食谱和膳食计划(本地存储)
- [gurkerlcli](https://github.com/openclaw/skills/tree/main/skills/pasogott/gurkerlcli/SKILL.md) - 通过gurkerl.at进行奥地利在线杂货购物
- [idealista](https://github.com/openclaw/skills/tree/main/skills/quifago/idealista/SKILL.md) - 通过idealista-cli查询Idealista API(OAuth2客户端凭证)
- [irish-takeaway](https://github.com/openclaw/skills/tree/main/skills/cotyledonlab/irish-takeaway/SKILL.md) - 在爱尔兰查找附近的外卖店并通过Deliveroo/Just Eat浏览菜单
- [marktplaats](https://github.com/openclaw/skills/tree/main/skills/pvoo/marktplaats/SKILL.md) - 在所有类别中搜索Marktplaats.nl分类广告(支持过滤)
- [ordercli](https://github.com/openclaw/skills/tree/main/skills/steipete/ordercli/SKILL.md) - 仅限Foodora的CLI工具，用于检查历史订单和活动订单状态(Deliveroo开发中)
- [paprika](https://github.com/openclaw/skills/tree/main/skills/mjrussell/paprika/SKILL.md) - 从Paprika Recipe Manager访问食谱、膳食计划和购物清单
- [picnic](https://github.com/openclaw/skills/tree/main/skills/mpociot/picnic/SKILL.md) - 从Picnic超市订购杂货 - 搜索产品、管理购物车、安排配送
- [plan2meal](https://github.com/openclaw/skills/tree/main/skills/okikesolutions/plan2meal/SKILL.md) - 膳食计划工具
- [shopping-expert](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/shopping-expert/SKILL.md) - 在线(Google Shopping)和本地(附近商店)查找和比较产品
- [whcli](https://github.com/openclaw/skills/tree/main/skills/pasogott/whcli/SKILL.md) - Willhaben CLI用于搜索奥地利最大的分类广告市场
- [wolt-orders](https://github.com/openclaw/skills/tree/main/skills/dviros/wolt-orders/SKILL.md) - Wolt: 发现餐厅、下单、跟踪、自动检测延迟
- [gurkerl](https://github.com/openclaw/skills/tree/main/skills/florianbeer/gurkerl/SKILL.md) - 通过MCP在Gurkerl.at上进行杂货购物
- [agent-commerce](https://github.com/openclaw/skills/tree/main/skills/nowloady) - 代理电子商务引擎和四川食品配送
- [jellyseerr](https://github.com/openclaw/skills/tree/main/skills/ericrosenberg/jellyseerr/SKILL.md) - 通过Jellyseerr请求电影和电视节目
- [clawdbites](https://github.com/openclaw/skills/tree/main/skills/kylelol/clawdbites/SKILL.md) - 从Instagram短视频中提取食谱
- [marketplace-clis](https://github.com/openclaw/skills/tree/main/skills/pjtf93) - 西班牙市场CLI工具: Wallapop、Idealista、Coches.net

</details>

<details>
<summary><h3 style="display:inline">日历与日程安排</h3></summary>

- [accli](https://github.com/openclaw/skills/tree/main/skills/joargp/accli/SKILL.md) - 当需要与macOS上的Apple日历交互时使用此技能
- [apple-calendar](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-calendar/SKILL.md) - macOS上的Apple日历应用集成
- [apple-reminders](https://github.com/openclaw/skills/tree/main/skills/steipete/apple-reminders/SKILL.md) - 在macOS上通过`remindctl` CLI管理Apple提醒事项(列出、添加、编辑、完成、删除)
- [calcurse](https://github.com/openclaw/skills/tree/main/skills/gumadeiras/calcurse/SKILL.md) - 基于文本的日历和日程安排应用。严格用于基于CLI的日历管理
- [caldav-calendar](https://github.com/openclaw/skills/tree/main/skills/asleep123/caldav-calendar/SKILL.md) - 同步和查询CalDAV日历(iCloud、Google、Fastmail、Nextcloud等)
- [clippy](https://github.com/openclaw/skills/tree/main/skills/foeken/clippy/SKILL.md) - Microsoft 365/Outlook CLI(日历和邮件)
- [cpc-mpqc-competence-tracker-compliance-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/cpc-mpqc-competence-tracker-compliance-uk/SKILL.md) - 规划CPC/MPQC能力追踪(含提醒、证据清单和合规报告)
- [gog](https://github.com/openclaw/skills/tree/main/skills/steipete/gog/SKILL.md) - Google Workspace CLI(Gmail、日历、Drive、联系人、Sheets和Docs)
- [holocube](https://github.com/openclaw/skills/tree/main/skills/andrewjiang/holocube/SKILL.md) - 使用HoloClawd固件控制GeekMagic HelloCubic-Lite全息立方体显示器
- [mcd-cn](https://github.com/openclaw/skills/tree/main/skills/ryanchen01/mcd-cn/SKILL.md) - 通过mcd-cn CLI查询麦当劳中国MCP服务器(活动日历、优惠券等)
- [morning-email-rollup](https://github.com/openclaw/skills/tree/main/skills/am-will/morning-email-rollup/SKILL.md) - 每天上午8点汇总重要邮件和日历事件(含AI生成摘要)
- [remind-me](https://github.com/openclaw/skills/tree/main/skills/julianengel/remind-me/SKILL.md) - 使用自然语言设置提醒。自动创建一次性cron任务并记录到markdown
- [roadrunner](https://github.com/openclaw/skills/tree/main/skills/johntheyoung/roadrunner/SKILL.md) - Beeper桌面CLI(聊天、消息、搜索和提醒)
- [timer](https://github.com/openclaw/skills/tree/main/skills/hisxo/timer/SKILL.md) - 设置计时器和闹钟。当后台计时器完成时
- [gcal-pro](https://github.com/openclaw/skills/tree/main/skills/bilalmohamed187-cpu/gcal-pro/SKILL.md) - Google日历：使用自然语言查看、创建和管理事件
- [meeting-prep](https://github.com/openclaw/skills/tree/main/skills/hougangdev/meeting-prep/SKILL.md) - 会议准备和每日提交摘要

</details>

<details>
<summary><h3 style="display:inline">PDF与文档处理</h3></summary>

- [confluence](https://github.com/openclaw/skills/tree/main/skills/francisbrero/confluence/SKILL.md) - 使用confluence-cli搜索和管理Confluence页面和空间
- [excel](https://github.com/openclaw/skills/tree/main/skills/dbhurley/excel/SKILL.md) - 读取、写入、编辑和格式化Excel文件(.xlsx)
- [excel-dashboard](https://github.com/openclaw/skills/tree/main/skills/kowl64/excel-dashboard/SKILL.md) - 设计可刷新的Excel仪表板(含Power Query+结构化表格+数据验证+数据透视表)
- [intomd](https://github.com/openclaw/skills/tree/main/skills/rezhajulio/intomd/SKILL.md) - 使用into.md服务获取任何文档URL并将其转换为Markdown格式
- [invoice-generator](https://github.com/openclaw/skills/tree/main/skills/tmigone/invoice-generator/SKILL.md) - 从JSON数据生成专业的PDF发票
- [markdown-converter](https://github.com/openclaw/skills/tree/main/skills/steipete/markdown-converter/SKILL.md) - 使用markitdown将文档和文件转换为Markdown格式
- [mineru-pdf](https://github.com/openclaw/skills/tree/main/skills/kesslerio/mineru-pdf-parser-clawdbot-skill/SKILL.md) - 使用MinerU在本地(CPU)将PDF解析为Markdown/JSON格式
- [nano-pdf](https://github.com/openclaw/skills/tree/main/skills/steipete/nano-pdf/SKILL.md) - 使用nano-pdf CLI通过自然语言指令编辑PDF
- [nudocs](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/nudocs/SKILL.md) - 通过Nudocs.ai上传、编辑和导出文档
- [pdf-form-filler](https://github.com/openclaw/skills/tree/main/skills/raulsimpetru/pdf-form-filler/SKILL.md) - 以编程方式填写PDF表单(文本值和复选框)
- [pptx-creator](https://github.com/openclaw/skills/tree/main/skills/dbhurley/pptx-creator/SKILL.md) - 根据大纲、数据源或AI生成的内容创建专业的PowerPoint演示文稿
- [pymupdf-pdf](https://github.com/openclaw/skills/tree/main/skills/kesslerio/pymupdf-pdf-parser-clawdbot-skill/SKILL.md) - 使用PyMuPDF(fitz)快速本地解析PDF(输出Markdown/JSON格式，可选包含图片/表格)

</details>

<details>
<summary><h3 style="display:inline">自托管与自动化</h3></summary>

- [bridle](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/bridle/SKILL.md) - AI编程助手的统一配置管理器
- [fathom](https://github.com/openclaw/skills/tree/main/skills/stopmoclay/fathom/SKILL.md) - 连接Fathom AI获取通话录音、转录文本和摘要
- [frappecli](https://github.com/openclaw/skills/tree/main/skills/pasogott/frappecli/SKILL.md) - Frappe Framework/ERPNext实例的CLI工具
- [gotify](https://github.com/openclaw/skills/tree/main/skills/jmagar/gotify/SKILL.md) - 通过Gotify发送推送通知(长时间运行任务完成或重要事件发生时)
- [meetgeek](https://github.com/openclaw/skills/tree/main/skills/nexty5870/meetgeek/SKILL.md) - 从CLI查询MeetGeek会议智能(列出会议、获取AI摘要、转录文本)
- [n8n](https://github.com/openclaw/skills/tree/main/skills/thomasansems/n8n/SKILL.md) - 通过API管理n8n工作流和自动化
- [n8n-workflow-automation](https://github.com/openclaw/skills/tree/main/skills/kowl64/n8n-workflow-automation/SKILL.md) - 设计并输出n8n工作流JSON(含健壮触发器、幂等性、错误处理和日志记录)
- [paperless](https://github.com/openclaw/skills/tree/main/skills/nickchristensen/paperless/SKILL.md) - 通过ppls CLI与Paperless-NGX文档管理系统交互
- [unifi](https://github.com/openclaw/skills/tree/main/skills/jmagar/unifi/SKILL.md) - 通过本地网关API(Cloud Gateway Max/UniFi OS)查询和监控UniFi网络
- [paperless-ngx](https://github.com/openclaw/skills/tree/main/skills/oskarstark/paperless-ngx/SKILL.md) - Paperless-ngx文档管理(搜索、上传、标记、组织)
- [n8n](https://github.com/openclaw/skills/tree/main/skills/pntrivedy/n8n-1-0-2/SKILL.md) - 管理n8n工作流、执行和自动化任务

</details>

<details>
<summary><h3 style="display:inline">安全与密码管理</h3></summary>

- [1password](https://github.com/openclaw/skills/tree/main/skills/steipete/1password/SKILL.md) - 设置和使用1Password CLI(op)。在安装CLI、启用桌面应用集成时使用
- [bitwarden](https://github.com/openclaw/skills/tree/main/skills/asleep123/bitwarden/SKILL.md) - 使用rbw CLI安全访问和管理Bitwarden/Vaultwarden密码
- [dashlane](https://github.com/openclaw/skills/tree/main/skills/gnarco/dashlane/SKILL.md) - 从Dashlane保险库访问密码、安全笔记、密钥和OTP代码
- [security-skills](https://github.com/openclaw/skills/tree/main/skills/chandrasekar-r) - Clawdbot部署的安全审计和实时监控
- [security-suite](https://github.com/openclaw/skills/tree/main/skills/gtrusler/clawdbot-security-suite/SKILL.md) - 高级安全验证(模式检测、命令清理)
- [bitwarden-vault](https://github.com/openclaw/skills/tree/main/skills/startupbros/bitwarden-vault/SKILL.md) - Bitwarden CLI设置、认证和密钥读取

</details>

## 🤝 贡献指南

我们欢迎贡献！详见[CONTRIBUTING.md](CONTRIBUTING.md)获取详细指南。

- 通过Pull Request提交新技能
- 改进现有技能定义

**注意：** 请勿提交刚创建3小时的技能。我们目前重点关注社区广泛采用的技能，特别是由开发团队发布并经过实际验证的技能。质量优先于数量。

## 许可证

MIT许可证 - 详见[LICENSE](LICENSE)

本列表中的技能源自[OpenClaw官方技能库](https://github.com/openclaw/skills/tree/main/skills)，并经过分类以便于发现。所列技能由其各自作者创建和维护，非由我们维护。我们不对所列项目进行安全审计、背书或保证其安全性和正确性。这些技能未经安全审计，生产环境使用前应自行审查。
If you find an issue with a listed skill or want your skill removed, please [open an issue](https://github.com/VoltAgent/awesome-openclaw-skills/issues) and we'll take care of it promptly.
