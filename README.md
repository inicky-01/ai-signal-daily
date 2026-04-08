# 📡 AI 情报站 · AI Signal Daily
> 个人 AI 热点情报 skill——不只是新闻，而是更快的热点信号。
> Beat the news cycle by 3 days.

## 这是什么
一个帮你每天追踪 AI 领域最新动态的 skill，核心理念是**活在信息传播链的最前端**：
论文/Demo 发布 → GitHub 有人实现 → HN 开始讨论 → 媒体才跟进
大多数人在第五步才看到，这个 skill 让你在第一步就知道。

**两种模式：**
- 📡 **Daily Brief**：每天纽约时间 22:00，三层结构输出（极简扫描 → 评论家小结 → 全部展开）
- 🚨 **Signal Alert**：突发大事件实时推送，分 BREAKING / VIRAL / SHIFT 三类

## 安装方法
把本仓库的 `SKILL.md` 文件放到你的 AI 工具对应的 skills 目录下：

| 工具 | 全局路径 | 项目路径 |
|------|---------|---------|
| **Trae** | `~/.trae/skills/ai-signal-daily/SKILL.md` | `.trae/skills/ai-signal-daily/SKILL.md` |
| **Claude Code** | `~/.claude/skills/ai-signal-daily/SKILL.md` | `.claude/skills/ai-signal-daily/SKILL.md` |
| **Cursor** | `~/.cursor/skills/ai-signal-daily/SKILL.md` | `.cursor/skills/ai-signal-daily/SKILL.md` |
| **Windsurf** | `~/.codeium/windsurf/skills/ai-signal-daily/SKILL.md` | `.windsurf/skills/ai-signal-daily/SKILL.md` |
| **Codex** | `~/.codex/skills/ai-signal-daily/SKILL.md` | `.codex/skills/ai-signal-daily/SKILL.md` |
| **OpenClaw** | ClawHub 搜索 `ai-signal-daily` 安装 | — |

> 💡 **通用方法**：大多数工具也支持放在项目根目录的 `.agent/skills/ai-signal-daily/` 下。

---

## 怎么用
安装后，在对话里直接说：
- "给我今天的 AI 情报"
- "AI 情报站"
- "有什么 AI 大新闻"
- "有没有 breaking"
- "今天发生了什么"

想深入了解某条新闻，直接说标题关键词即可，skill 会展开详细分析。

---

## 输出示例
📡 AI Signal Daily
April 8, 2026 · ET 22:00
🔴Anthropic 发布 Claude Mythos Preview + Project Glasswing，向 40+ 家机构开放用于防御性网络安全 （零日漏洞 · 网安联盟 · 未公开发布）
· Anthropic 年化收入突破 $300 亿，超越 OpenAI，估值 IPO 预期 $3800–6000 亿 （收入逆袭 · Claude Code · 企业市场）
🔴Google DeepMind 发布 Gemma 4（Apache 2.0），31B 模型跑赢 20× 参数量对手 （开源 · 端侧代理 · 无商业限制）
🟡Anthropic 签署 Google × Broadcom TPU 3.5GW 算力协议，2027 年上线 （算力 · 基础设施 · 去 NVIDIA 化）
⚪WSJ 披露 OpenAI/Anthropic 保密财务：OpenAI 2028 预计亏损 $850 亿，Anthropic 预计 2028-29 年盈利 （IPO 前数据 · 烧钱对比）
⚪MCP 累计安装量突破 9700 万，已成 AI 代理标准基础设施

今日信号小结
今天发生的事情，核心不是一个产品发布，而是 Anthropic 在三个维度上同时打出了一张牌：最强模型（Mythos）、最高收入（超越 OpenAI）、最大算力承诺（3.5GW）。这三件事同一天堆在一起，不像巧合。更值得注意的是 Project Glasswing 的底层逻辑——Anthropic 自己在内部文件里说这个模型"目前在网络安全能力上远超任何其他 AI"，同时又对外说"必须管控，不能公开"。这种罕见的自我约束，是真正的安全主义信仰，还是一种精心设计的 IPO 前叙事？两种解读都说得通。而 Google 在同一周扔出了 Gemma 4（Apache 2.0），意味着开源阵营有了第一个真正可商用、可端侧部署的高性能选手。闭源付费模型的定价权，正在被慢慢稀释。

🔴 Anthropic 发布 Claude Mythos Preview + Project Glasswing
来源：TechCrunch · Fortune · CNBC
Anthropic 宣布将其最新、最强大但尚未公开发布的模型 Claude Mythos Preview 向 12 家核心合作伙伴（含 Apple、Google、Microsoft、CrowdStrike、Linux Foundation 等）及另外约 40 家机构开放，专用于防御性网络安全工作，品牌命名为 Project Glasswing（名称来自透明蝴蝶翅膀，寓意软件漏洞"相对不可见"）。据 TechCrunch 报道，Mythos 在过去几周内已识别出数千个零日漏洞，其中许多漏洞存在长达 20 余年——包括在 OpenBSD 中发现一个存在 27 年、可通过少量数据包使任意服务器崩溃的 bug。Anthropic 的红队研究员 Nicholas Carlini 公开表示自己近几周发现的 bug 数量超过了此前职业生涯的总和。Anthropic 明确表示不会将 Mythos 公开发布，同时为合作伙伴提供高达 $1 亿使用额度，并向开源安全组织捐款 $400 万——Anthropic 已私下警告政府官员，Mythos 级别的能力将显著提升今年大规模网络攻击的可能性。

🔴 Anthropic 年化收入超越 OpenAI，突破 $300 亿
来源：SaaStr · Yahoo Finance
Anthropic 宣布年化收入运行率突破 $300 亿，较 2025 年底的 $90 亿增长逾 230%，正式超越 OpenAI 的 $240–250 亿。据 SaaStr 报道，该数字背后的弹道是：2024 年底 $10 亿 → 2025 年底 $90 亿 → 2026 年 2 月 $140 亿 → 3 月 $190 亿 → 4 月 $300 亿——最后 8 周的增速在 200 家以上软件公司 IPO 历史中未见过类似案例。核心驱动是企业客户：年消费超 $100 万的客户在两个月内从 500 家翻倍至逾 1000 家，Fortune 10 中有 8 家是其客户；Claude Code 在 AI 编程工具市场拿下 54% 份额，年化收入超 $25 亿。与此同时 WSJ 披露的财务数据显示：OpenAI 预计 2028 年算力支出达 $1210 亿、亏损 $850 亿，而 Anthropic 同期训练成本峰值约 $300 亿，预计 2028-29 年盈利——在 4x 更低的训练成本下超越对手，是今天这则新闻真正的叙事颠覆之处。

🟡 Google DeepMind 发布 Gemma 4（Apache 2.0）
来源：Google DeepMind Blog · AI Haven
Google DeepMind 在 4 月 2 日正式发布 Gemma 4，四种尺寸（E2B / E4B / 26B MoE / 31B Dense），全部采用 Apache 2.0 许可——这是 Gemma 系列首次无商业限制，可自由修改、分发和商业化。旗舰版 31B 在 Arena AI 文本排行榜排名全球第三，在 AIME 2026 数学基准上从前代的 20.8% 跃升至 89.2%，且可在单张 80GB GPU 上全精度运行；E2B/E4B 边缘版可在 1.5GB 内存内运行，原生支持多模态（文字 + 图像 + 音频）与工具调用，专为端侧 AI 代理设计。对开源生态而言，这是 Llama 之后第一个真正可商用、可端侧部署、同时具备前沿级推理能力的主流模型，直接压缩了中低端闭源模型的定价空间。

⚪ Anthropic × Google × Broadcom：3.5GW TPU 算力协议
来源：TradingKey
Anthropic 宣布与 Google 和 Broadcom 签署协议，锁定约 3.5GW 的 TPU v7p 算力，从 2027 年起逐步上线，全部位于美国境内。这一布局让 Anthropic 成为唯一同时接入 AWS Trainium、Google TPUs、Microsoft Azure 三大云平台的前沿模型提供商，同时绕开英伟达主导的 GPU 供应链，形成自己的算力护城河。

⚪ MCP 安装量破 9700 万，成 AI 代理默认基础设施
来源：Crescendo AI
Anthropic 的 Model Context Protocol 在 2026 年 3 月安装量突破 9700 万，所有主流 AI 厂商均已推出 MCP 兼容工具，协议已从实验性标准演变为 AI 代理连接外部工具、API 和数据源的默认机制。同月，该协议已被纳入 Linux Foundation 旗下的 Agentic AI Foundation，与 OpenAI 的 AGENTS.md 共同成为中立基础设施。

🔥 今日 Viral 回顾
· Simon Willison 写的 Project Glasswing 技术拆解（simonwillison.net）— Glasswing 发布当天，这篇博文在 HN 首页停留数小时、评论持续增长；Nicholas Carlini "几周找到的 bug 超过职业生涯总和"这句话在 X 上大量转发。跨平台同步爆发，符合 Viral 触发条件。
· SaaStr：Anthropic 以 4x 更低训练成本超越 OpenAI（saastr.com）— WSJ 财务披露 + Anthropic 收入公告同时引爆，X 上"Anthropic passed OpenAI"成为 AI 圈当天讨论密度最高的话题，并扩散至 r/MachineLearning 和 r/LocalLLaMA


## 作者
Made by [@inicky-01](https://github.com/inicky-01)  
欢迎 Star ⭐ 如果你觉得有用，分享给更多人



