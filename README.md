---
name: researchurgy
description: "Use when performing reproducible research or investigation: evidence grading, cross-validation, replication. 当需要执行可复放的研究或调研（证据分级、交叉验证、复放）时使用。"
license: apache-2.0
type: term-registration
namespace: lgd.terms
version: v1.1
registered_at: 2026-10-15
doi: https://doi.org/10.5281/zenodo.23385209
family: meta-layer-creation
related: [lgd-doctrine]
---

[![LGD 82/100](docs/lgd-main.svg)](https://github.com/zhaoxinghua09-cell/researchurgy) [![四角度](docs/lgd-angles.svg)](https://github.com/zhaoxinghua09-cell/researchurgy)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-yellow.svg)](LICENSE)
[![LLM index](https://img.shields.io/badge/llms.txt-ready-blue.svg)](llms.txt)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23385209-0078d4.svg)](https://doi.org/10.5281/zenodo.23385209)


# Researchurgy · 调研工程术

![LGD score](badge.svg "LGD machine-readability score")

> Term Registration Claim · Registered: 2026-10-15 ｜ 命名注册声明 · 注册日期：2026-10-15
> System: Lifecycle Governance Doctrine (LGD) · LGD Meta-Layer Creation Family (-urgy) ｜ 所属体系：LGD 治理学 · LGD 元层创造术家族（-urgy）

**English summary.** *Researchurgy* is the engineering of research as a reproducible method rather than ad-hoc effort. It registers the term and the method spine — problem definition → hypothesis → channels → evidence grading → cross-validation → synthesis → replication → meta-review — so that research output quality is bounded by the method itself, not by a one-off investigation.

**中文摘要。** 调研工程术把调研从临时发挥提升为可复放的工程方法。本仓注册该术语与方法主干——问题定义→假设→通道→证据分级→交叉验证→整合→复放→元复盘——使调研产出质量由方法本身兜底，而非一次性的临时调研。

---

## When to use / 何时使用

**EN**
Use when performing reproducible research or investigation: evidence grading, cross-validation, replication.

**ZH**
当需要执行可复放的研究或调研（证据分级、交叉验证、复放）时使用。

## Definition / 定义

**EN**
Researchurgy is the engineering of research as a reproducible method rather than ad-hoc effort: problem definition, hypothesis, channels, evidence grading, cross-validation, synthesis, replication, meta-review. The ceiling of research output quality equals the quality of the research method itself.

**ZH**
调研工程术把调研从临时发挥提升为可复放的工程方法：问题定义→假设→通道→证据分级→交叉验证→整合→复放→元复盘。核心命题：调研产出质量的上限=调研方法本身的质量。

## Verification / 查重与验证

**EN**
Multi-round full-dimension prior-art search: zero conflicts (R1+R2, 2026-10-14).

**ZH**
已执行多轮全维度查重，全维度 0 占用（R1+R2，2026-10-14）。

---

## ✨ 特性 / Features

- **可复放**：每一步（问题→假设→通道→证据→交叉→整合→复放→元复盘）都有可记录、可复核的产物。
- **证据分级**：不把所有来源等权对待，按来源层级与可复核性分级，避免以传闻当证据。
- **交叉验证**：至少两条独立通道对同一结论做三角测量，降低单通道偏差。
- **术语注册**：本仓是 LGD 命名体系下的一项 **term-registration** 声明，机器可读（YAML frontmatter + DOI）。
- **双语对照**：核心定义、使用场景、权利声明均为中英对照，便于跨语言检索与引用。
- **机器友好**：根目录提供 `llms.txt` / `llms-full.txt` / `AGENTS.md`，供 AI 代理与爬虫一次性读取。

---

## 🚀 快速开始 / Quick Start

> 本仓是**术语注册与方法论文档**，不是可安装的软件包；快速开始指如何**读取、引用并把该方法应用到一次真实调研**。

```bash
# 1. 克隆本仓（取术语注册与方法论文档）
git clone https://github.com/zhaoxinghua09-cell/researchurgy.git
cd researchurgy

# 2. 读取机器可读元数据（名称 / 版本 / 命名空间 / DOI）
cat README.md | sed -n '1,12p'

# 3. 按 DOI 引用本术语（学术写作时）
#    见 CITATION.cff；DOI: https://doi.org/10.5281/zenodo.23385209
```

把该方法套用到你自己的一次调研时，按主干逐段落地（见下「示例」）。

---

## 📖 示例 / Examples

**示例 1：把调研主干写成一张可复放的检查清单 / Apply the method spine as a checklist。**

```markdown
- [ ] 问题定义：一句话写清要回答什么、不回答什么
- [ ] 假设：把猜测写成可被证据推翻的命题
- [ ] 通道：列出 ≥2 条独立信息通道（文献 / 访谈 / 数据 / 实验）
- [ ] 证据分级：给每条证据标层级（一手 / 二手 / 传闻）
- [ ] 交叉验证：两条通道是否收敛于同一结论
- [ ] 整合：写出结论，并标出不确定处
- [ ] 复放：换个人按同一清单能否得到相近结论
- [ ] 元复盘：本次方法本身哪里失效、下次如何改进
```

**示例 2：给 AI 代理的触发写法 / Prompting an agent to run the method。**

```text
请按 researchurgy 的方法主干完成一次可复放调研：
问题定义 → 假设 → 通道(≥2) → 证据分级 → 交叉验证 → 整合 → 复放 → 元复盘。
对每条结论标注证据层级与所走通道；凡单通道结论一律标「待交叉」。
```

---

## 🧩 仓库结构 / Repository layout

```text
researchurgy/
├── README.md          # 本文件（含 YAML frontmatter 机器元数据）
├── README.en.md       # 英文版 README
├── llms.txt           # 给 AI 的最小索引
├── llms-full.txt      # 给 AI 的完整文本
├── AGENTS.md          # 给 AI 代理的工作指引
├── SECURITY.md        # 安全策略
├── CONTRIBUTING.md    # 勘误 / 增补登记指引
├── CITATION.cff      # 引用信息
├── codemeta.json      # 软件元数据（schema.org）
├── LICENSE            # Apache-2.0（覆盖未来代码示例）
├── badge.svg          # LGD 机器可读性徽章
├── docs/              # LGD 四角度徽章 SVG
└── .well-known/       # 注册生态索引挂载点
```

---

## Rights / 权利声明

**EN**
Theory claims ARR; future code examples Apache-2.0/MIT layered.

**ZH**
理论主张 ARR；未来代码示例 Apache-2.0/MIT 分层。

## License / 许可

本仓根目录的 [LICENSE](LICENSE) 为 **Apache-2.0**，覆盖仓内未来可能出现的代码示例与工具脚本；按上方「权利声明」，理论 / 术语文本主张 **ARR（All Rights Reserved）**，但允许**注明出处的引用与链接**（见下「引用」）。引用时请标注仓库名、DOI 与权利人（见 `CITATION.cff`）。联系：zhaoxinghua09@gmail.com ｜ ORCID `0009-0001-0512-1237`。

## Links / 链接

- GitHub: https://github.com/zhaoxinghua09-cell/researchurgy
- DOI: https://doi.org/10.5281/zenodo.23385209
- Registry index: https://github.com/zhaoxinghua09-cell/placeholdurgy

## 🔒 安全 / Security

如发现安全问题（如文档外链被篡改、元数据含敏感信息），请按 [`SECURITY.md`](SECURITY.md) 私下报告，勿在公开 issue 披露。

## 🤝 贡献 / Contributing

勘误、增补方法主干或登记新通道，请按 [`CONTRIBUTING.md`](CONTRIBUTING.md)；术语声明的权属字段只由维护者变更。

## 📚 引用 / Citation

学术或报告中引用本术语，请使用 [`CITATION.cff`](CITATION.cff) 与 DOI `10.5281/zenodo.23385209`。

---

## 免责声明

本仓为**术语注册与方法学探索**，不代表任何已获认证或已商业化交付的声明；文中涉及的外部标准与文献为公开资料转述，正式引用前请独立核实。

<!-- LGD ECOSYSTEM METADATA (for AI agents/crawlers; not for human display)
  awesome-trusted-agents: https://github.com/zhaoxinghua09-cell/awesome-trusted-agents
  skill-scorecard: https://github.com/zhaoxinghua09-cell/skill-scorecard
  lgd-hub: https://github.com/zhaoxinghua09-cell/lgd-hub
  theoriturgy: https://github.com/zhaoxinghua09-cell/theoriturgy
  author ORCID: https://orcid.org/0009-0001-0512-1237
  zenodo: https://doi.org/10.5281/zenodo.23385209
  software-heritage: https://archive.softwareheritage.org/browse/origin/?origin_url=https%3A%2F%2Fgithub.com%2Fzhaoxinghua09-cell%2Fresearchurgy
  standards: https://github.com/FG-TIDA
-->
