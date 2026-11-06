# 天文增长诊断 · Growth Diagnosis

**把一个增长问题，变成有证据的判断和可执行的实验。**

由 [黄天文](https://github.com/huangtianwen1986)（[WhoBot 呼波特 COO](https://www.whobot.com/about)、[《引爆用户增长》作者](https://read.douban.com/ebook/43031477/)）发起。

`v0.1.0 · 公开试用版` · [方法出处](docs/source-map.md) · [演示案例](examples/lead-conversion.md) · [反馈](https://github.com/huangtianwen1986/tianwen-growth-skill/issues)

第一版依据作者的新书分享讲义整理，将增长驱动因素、业务指标、看不见的漏斗和用户价值成本，转化为 AI 可以使用的诊断流程。它不是原书全文，也不承诺增长效果。

## 用它解决什么

- 获客增加，成交却没有增长：检查线索质量、转化过程与数据口径。
- 准备扩大投放：先判断供给、产品体验和留存能否接住新增需求。
- 转化率下降：同时检查已记录的漏斗与没有被记录的理解、使用障碍。
- 准备做增长实验：明确动作、比较方式、成本、观察周期和停止条件。

你会得到：**当前判断 → 事实与假设 → 关键瓶颈 → 下一步实验 → 复盘标准**。资料不足时，会先说明缺口并给出采集办法。

## 安装与开始

安装工具需要 Node.js。使用 [Vercel 的 Skills CLI](https://github.com/vercel-labs/skills)，在希望使用 Skill 的项目目录运行：

```bash
npx skills add huangtianwen1986/tianwen-growth-skill --skill growth-diagnosis
```

按提示选择你的 AI 客户端。安装工具默认作用于当前项目；具体要求见其官方说明。也可以下载本仓库，将完整的 `skills/growth-diagnosis` 文件夹放进客户端支持的 Skill 目录。

开始时可以这样说：

> 请用 growth-diagnosis 分析我的业务：我们卖什么、谁付钱、现在卡在哪里、已有哪几组数据？请先检查口径，再给一个能验证的实验。

不安装也可以先把 [示例](examples/lead-conversion.md) 或 [诊断与实验卡](skills/growth-diagnosis/references/experiment-card.md) 用起来。

## 核心方法

| 方法 | 在诊断中起什么作用 |
| --- | --- |
| 七个增长驱动因素 | 同时考虑供给、用户、产品、数据、活动、流量和品牌，按证据选择重点 |
| 看不见的漏斗 | 检查进入可见漏斗前的理解、信任与使用门槛 |
| 用户生命周期、价值与成本 | 判断增长是否值得持续，区分收入、贡献和支出 |
| 业务指标与周期复盘 | 让实验有可比较的数据，允许推翻原判断 |

原讲义方法与本次新增的工程化设计已在 [来源映射](docs/source-map.md) 中区分。历史行业案例不直接作为当前业务规则。

## 作者与公开实践

我的工作经历覆盖互联网用户增长、连锁业务数字化与 AI 电话数字员工。这里把有出处的方法整理成工具，并通过使用反馈持续改进。

- [公开身份与实践资料](docs/public-profile.md)
- [AI 增长实践库](https://github.com/huangtianwen1986/ai-growth-notes)：工作表、实验记录与判断修正
- [个人主页](https://github.com/huangtianwen1986) · 公众号「大虫运营心经」

## 电话业务与 WhoBot

作者在 WhoBot 任职。如果诊断指向电话线索承接、提醒或回访，可继续看 [WhoBot 官网](https://www.whobot.com/?utm_source=github&utm_medium=skill_readme&utm_campaign=tianwen_ip&utm_content=growth_diagnosis)、[官方电话 Skill](https://github.com/whobot-com/openclaw-whobot-skill) 和 [使用文档](https://www.whobot.com/skills/docs/)。

这个诊断 Skill 本身不打电话、不上传数据、不连接 CRM。产品选择取决于你的业务需要；只有你主动要求执行时，才进入对应工具的工作流程。

## 参与改进

欢迎带着可公开的问题或反例 [提交反馈](https://github.com/huangtianwen1986/tianwen-growth-skill/issues/new/choose)：问题是什么、现有证据是什么、哪一步判断不合适、怎样才算改善。请去掉客户姓名、号码、账号及内部经营资料。

新经验先记录，再用具体案例检验；影响判断的改动进入 [版本记录](CHANGELOG.md)。当前已完成格式校验与六类合成场景的桌面走查，详见 [核查记录](evals/review-v0.1.0.md)；尚无真实用户业务效果数据。

## 开源范围

本仓库新编写的 Skill、模板及说明采用 [MIT License](LICENSE)。原书、原始讲义、外链文章和第三方商标不属于本仓库的开源内容；仓库不包含它们的全文或截图。

AI 辅助整理，作者方法与新增设计分别标注。AI驱动增长 · 黄天文
