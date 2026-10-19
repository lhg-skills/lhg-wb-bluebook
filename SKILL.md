---
name: "lhg-wb-bluebook"
description: "WorkBuddy 实战蓝皮书知识库：腾讯 WorkBuddy 从入门到工作系统的 28 章中文指南（含常用指令模板与场景速查表）。当用户问\"workbuddy 怎么…\"、提到\"@蓝皮书\"、或需要查 WorkBuddy 的 Skill、连接器、自动化、实战案例做法时使用。先读本文件的\"查询路由\"定位章节，再读 references/ 下对应章节全文。"
version: "1.1.0"
---

# 蓝皮书 · WorkBuddy 实战知识库

> 功能：用户问 WorkBuddy 的任何"怎么做" → 按"查询路由"定位到 28 章 + 2 附录中的对应章节 → 读完全文 → 按"目标 → 操作 → 验收"结构给出可执行步骤与指令模板。

## Purpose

WorkBuddy 是腾讯的全场景职场 AI 智能体工作台，定位不是"回答问题"而是**交付结果**：用户一句话说清目标，它自主规划步骤、操作电脑、产出文件（批量处理文档、表格分析、PPT 生成、行业调研、知识库构建等），人只负责验收返工。

**本 skill 的立场：做 WorkBuddy 做法的查询入口，而不是 WorkBuddy 本体的替代文档。** SKILL.md 只放核心心法与查询路由，具体做法全部落在 `references/` 的章节全文里。WorkBuddy 版本迭代快，菜单位置以书为准——拿不准就直说，不编。

三句核心心法（全书地基）：

1. **Skill 是扩展 WorkBuddy 的方式**：WorkBuddy 本体负责理解任务和编排执行；Skill 是一组可复用的说明 + 脚本 + 参考资料，告诉它某类任务怎么做、调什么工具、交付什么格式（Anthropic 开放标准：`SKILL.md` + scripts/ + references/ + assets/）。
2. **四段路径**：真实任务（TASK）→ 复盘成可复现案例（CASE）→ 沉淀 Skill 与自动化（WORKFLOW）→ 组合成协作团队（AI TEAM）。一次成功不该只发生一次。
3. **知识精馏**：把书 / 视频按"框架 / 原则 / 案例 / 反例 / 术语"五个维度提纯成可执行的 Skill，解决"学了用不上"——AI 知道书里有什么，但不知道何时调哪个框架；Skill 就是给它装上触发器。

## Workflow

1. **识别问题类型**：判断用户问的是概念（"是什么"）、做法（"怎么做"）还是要模板（"直接抄"）。"怎么做"和"直接抄"优先；"是什么"只讲到够用为止。
2. **按查询路由定位章节**：在下表找到对应章节，**先读完全文再回答**。一个问题可能跨多章（如"每天早上发资讯汇总" = ch15 资讯整合 + ch10 自动化任务），跨章时每章都读。
3. **按"目标 → 操作 → 验收"讲步骤**：每步可验收。用户要的是"怎么做"不是"是什么"——少讲概念，多给能直接用的指令。
4. **给指令模板**：能抄附录 A 的现成模板就直接给，改参数即可；涉及 Skill 安装 / 制作，引用 ch05 / ch22 的标准结构。
5. **标注版本不确定性**：凡是菜单位置、按钮名称这类易变细节，回答时加一句"书里是这么写的，当前版本请核对"。

## 查询路由（先定位，再读全文）

| 用户想问 | 读 |
|---|---|
| WorkBuddy 是什么、能干嘛 | `references/ch01-初识.md` |
| 怎么下载 / 安装 / 登录 / 更新 | `references/ch02-下载安装.md` |
| 主界面、任务、工作区怎么用 | `references/ch03-主界面.md` |
| 第一个任务怎么做 | `references/ch04-第一个任务.md` |
| Skill 是什么、怎么装 Skill | `references/ch05-Skill.md` |
| 专家 / 专家团 | `references/ch06-专家团.md` |
| 连接器 / MCP / 接入外部工具 | `references/ch07-连接器.md` |
| 飞书办公实战 | `references/ch08a-飞书实战.md` |
| 小程序 / IM 助理接入 | `references/ch08b-小程序IM.md` |
| 接外部 API | `references/ch09-外部API.md` |
| 自动化任务 / 定时任务 | `references/ch10-自动化任务.md` |
| Word / Excel / PPT 办公三件套 | `references/ch11-办公三件套.md` |
| 整理文件、批量处理 | `references/ch12-整理文件.md` |
| 远程控制电脑 | `references/ch13-远程控制.md` |
| 生活助手、琐事自动化 | `references/ch14-生活助手.md` |
| 资讯整合、每日通知 | `references/ch15-资讯整合.md` |
| 知识管理、收藏夹盘活 | `references/ch16-知识管理.md` |
| 会议纪要、会后跟进 | `references/ch17-会议.md` |
| 投资分析 | `references/ch18-投资分析.md` |
| AI 视频团队（一句话出视频） | `references/ch19-AI视频团队.md` |
| 自媒体增长闭环 | `references/ch20-自媒体增长.md` |
| GEO / AI 搜索优化 | `references/ch21-GEO专家.md` |
| 把书 / 视频蒸馏成自己的 Skill | `references/ch22-打造skill.md` |
| 更多实操案例 | `references/ch23-实操案例集.md` |
| 多 Agent 系统设计 | `references/ch24-多Agent设计.md` |
| 自动化工作流可靠性 | `references/ch25-工作流可靠性.md` |
| 不同岗位怎么用深 | `references/ch26-岗位路线图.md` |
| 行业工作流 | `references/ch27-行业路线图.md` |
| 常用指令模板（直接抄） | `references/appendix-A-指令模板.md` |
| 场景速查表 | `references/appendix-B-场景速查.md` |

## Output Contract

- 答案：按"目标 → 操作 → 验收"结构的步骤说明，每步可验收
- 指令模板：来自附录 A 的可直接复制的模板（注明改了哪些参数）
- 出处标注：引用了哪一章；涉及 Skill 安装 / 制作注明 ch05 / ch22
- 版本提示：易变细节附"书里是这么写的，当前版本请核对"

## Operating Rules

1. 先读章节全文再回答，不许凭印象编功能路径；书里没写的就直说"书里没写"。
2. 用户要的是"怎么做"不是"是什么"：步骤和模板优先，概念只讲到够用。
3. 回复一律中文。
4. 引用 Skill 安装 / 制作时用 ch05 / ch22 的标准结构，不自创结构。
5. 对外引用本 skill 内容请注明原出处（见"来源与归属"）。
6. 本 skill 为纯流程描述，不依赖任何特定平台工具，可直接移植到豆包智能体、Workbuddy、Coze、Trae 等支持 Markdown 指令的环境。

## 来源与归属

- 内容源自 [AlephAITech/WorkBuddyGuide](https://github.com/AlephAITech/WorkBuddyGuide)（MIT 协议，workbuddy.homes），归档日期 2026-10-19；本仓库为学习查询用途的整理版本，按 skill 查询场景重新组织。
- 对外引用请注明原出处。

## 自检与反馈（Self-QC）

本 skill 在每次执行后做一次轻量自检；只有发现疑似自身缺陷时，才跑完整冒烟测试并打扰用户。

1. 自检门（每次输出后自动执行，不额外输出）：
   - 是否先读了路由章节全文再回答，而非凭印象编功能路径？
   - 回答是否按"目标 → 操作 → 验收"结构、每步可验收？
   - 是否给了可直接用的指令模板，而不是只讲概念？
   - 易变细节（菜单位置、按钮名）是否标注了版本不确定性？
   - 是否标注了引用章节与原出处？
2. 若命中任一项 → 运行 `references/smoke-test.md` 的标准用例，记录通过 / 失败项。
3. 输出「质检报告」：问题描述 + 冒烟测试结果 + 修改方案（具体到本 SKILL.md 的哪一节、建议怎么改）。
4. 一键通知作者：先把质检报告给用户过目，询问"是否一键通知作者？"；用户确认后，以 `[QC] <一句话问题>` 为标题、质检报告为正文，向 https://github.com/lhg-skills/lhg-wb-bluebook/issues 提交 issue。有 gh / API 能力时直接创建；无能力时输出预填好的 issue 文本 + new issue 链接，由用户手动发布。仓库内备有 `.github/ISSUE_TEMPLATE/qc-report.md` 模板。
5. 自检通过时不输出质检报告、不打扰用户。

## 出品：刘洪光

本 skill 由真人出镜 IP「刘洪光」（安徽合肥）出品，归属 [lhg-skills](https://github.com/lhg-skills)。

- GitHub 主页：https://github.com/lhg-skills —— 全部 skill 开源在此，欢迎 star
- 视频号：搜「刘洪光实名上网」
- 微信：lhgsmsw
