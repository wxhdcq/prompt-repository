# 提示词仓库

这是我的个人 AI 提示词仓库，用于把常用工作流沉淀成可复用模板。内容主要面向 ChatGPT、Codex、Deep Research、学习作业、投资复盘、软件研究、银行卡权益查询、新闻简报和文档生成等场景。

## 使用方式

1. 打开对应 Markdown 文件。
2. 复制「完整提示词」代码块。
3. 在 ChatGPT iOS、网页版 ChatGPT、Codex 或 Deep Research 中粘贴使用。
4. 把方括号里的占位内容替换成自己的需求。
5. 对重要信息进行二次验证，尤其是金融、银行、价格、实时新闻和政策信息。

## 模板目录

| 编号 | 模板名称 | 文件路径 | 用途 | 适合场景 |
| --- | --- | --- | --- | --- |
| 01 | 软件反软广研究模板 | [prompts/01-app-anti-shill-research.md](prompts/01-app-anti-shill-research.md) | 识别软广、水军、停更风险和订阅陷阱 | App、相机软件、股票记录软件、AI 工具、订阅制软件 |
| 02 | 美股持仓复盘模板 | [prompts/02-us-stock-daily-review.md](prompts/02-us-stock-daily-review.md) | 每天美股收盘后复盘重点持仓 | NVDA、AMD、MU、FTNT、QQQM 等持仓观察 |
| 03 | 股票深度分析模板 | [prompts/03-stock-deep-analysis.md](prompts/03-stock-deep-analysis.md) | 分析单只股票、ETF 或行业 | 短线交易、中线持有、长期配置、加仓/止盈判断 |
| 04 | 银行卡权益检查模板 | [prompts/04-bank-card-benefit-check.md](prompts/04-bank-card-benefit-check.md) | 检查银行卡活动、返现、迎新、保级 | 中信 GBA、汇丰 Pulse、恒生香港、建行亚洲等 |
| 05 | Codex 任务模板 | [prompts/05-codex-task-template.md](prompts/05-codex-task-template.md) | 把普通需求整理成 Codex 可执行任务 | 代码修改、仓库整理、页面修复、部署排查 |
| 06 | Codex 仓库审查模板 | [prompts/06-codex-repo-doctor.md](prompts/06-codex-repo-doctor.md) | 检查仓库结构、README、格式、测试和部署 | GitHub 仓库、Skill、CSV、YAML、CI、部署 |
| 07 | 学习作业速成模板 | [prompts/07-coursework-fast-draft.md](prompts/07-coursework-fast-draft.md) | 快速生成可复制的课堂作业草稿 | 图片题、观后感、三分钟发言稿、报告 |
| 08 | 新闻简报模板 | [prompts/08-news-briefing.md](prompts/08-news-briefing.md) | 整理指定主题的权威新闻简报 | 全球政治、AI、美股、德国、东京、拜仁、足球 |
| 09 | PDF/文档生成模板 | [prompts/09-pdf-document-generation.md](prompts/09-pdf-document-generation.md) | 生成教程、说明书、报告和 PDF 文档 | 中文文档、使用指南、作业、技术说明 |
| 10 | 网页部署教程模板 | [prompts/10-web-deploy-guide.md](prompts/10-web-deploy-guide.md) | 部署网页或生成完整部署教程 | Cloudflare Pages、Vercel、GitHub Pages、静态网站 |

## 推荐使用顺序

- 查软件/产品：先用 [软件反软广研究模板](prompts/01-app-anti-shill-research.md)。
- 查股票：先用 [股票深度分析模板](prompts/03-stock-deep-analysis.md)。
- 每日持仓：用 [美股持仓复盘模板](prompts/02-us-stock-daily-review.md)。
- 查银行卡权益：用 [银行卡权益检查模板](prompts/04-bank-card-benefit-check.md)。
- 写作业：用 [学习作业速成模板](prompts/07-coursework-fast-draft.md)。
- 给 Codex 派任务：用 [Codex 任务模板](prompts/05-codex-task-template.md)。
- 检查仓库质量：用 [Codex 仓库审查模板](prompts/06-codex-repo-doctor.md)。
- 做新闻简报：用 [新闻简报模板](prompts/08-news-briefing.md)。
- 生成文档/PDF：用 [PDF/文档生成模板](prompts/09-pdf-document-generation.md)。
- 部署网页：用 [网页部署教程模板](prompts/10-web-deploy-guide.md)。

## 配套文件

- [codex/issue-template.md](codex/issue-template.md)：通用 GitHub Issue 模板。
- [codex/pr-checklist.md](codex/pr-checklist.md)：PR 检查清单。
- [codex/repo-rules.md](codex/repo-rules.md)：仓库规则。
- [examples/app-research-example.md](examples/app-research-example.md)：相机 App 研究示例。
- [examples/stock-review-example.md](examples/stock-review-example.md)：美股持仓复盘示例。
- [examples/bank-benefit-example.md](examples/bank-benefit-example.md)：银行卡权益检查示例。

## 注意事项

- AI 可能出错，重要信息必须二次验证。
- 投资内容不构成买卖建议。
- 银行权益以官方条款和 App 实际显示为准。
- 软件价格、地区价和活动可能随时变化。
- 不要把密码、验证码、token、身份证件等敏感信息放进提示词。
- 不要让 AI 自动交易、自动下单、绕过登录、伪造数据或替代官方确认。
