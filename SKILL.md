---
name: 蓝皮书
description: WorkBuddy 实战蓝皮书知识库——腾讯 WorkBuddy 从入门到工作系统的 28 章中文指南。当用户问"workbuddy 怎么…""/"@蓝皮书"被提及 / 需要查 WorkBuddy 的 Skill、连接器、自动化、案例做法时使用。先读本文件的"查询路由"定位章节，再读 references/ 下对应全文。
version: 1.0.0
---

# 蓝皮书（WorkBuddy 实战知识库）

## 这是什么

WorkBuddy 是腾讯的全场景职场 AI 智能体工作台，定位不是"回答问题"而是**交付结果**：
用户一句话说清目标，它自主规划步骤、操作电脑、产出文件（批量处理文档、表格分析、PPT 生成、行业调研、知识库构建等），人只负责验收返工。

三句核心心法（全书地基）：
1. **Skill 是扩展 WorkBuddy 的方式**：WorkBuddy 本体负责理解任务和编排执行；Skill 是一组可复用的说明+脚本+参考资料，告诉它某类任务怎么做、调什么工具、交付什么格式（Anthropic 开放标准，`SKILL.md` + scripts/ + references/ + assets/）。
2. **四段路径**：真实任务（TASK）→ 复盘成可复现案例（CASE）→ 沉淀 Skill 与自动化（WORKFLOW）→ 组合成协作团队（AI TEAM）。一次成功不该只发生一次。
3. **知识精馏**：把书/视频按"框架 / 原则 / 案例 / 反例 / 术语"五个维度提纯成可执行的 Skill，解决"学了用不上"——AI 知道书里有什么，但不知道何时调哪个框架；Skill 就是给它装上触发器。

## 查询路由（先定位，再读全文）

| 用户想问 | 读 |
|---|---|
| WorkBuddy 是什么、能干嘛 | `references/ch01-初识.md` |
| 怎么下载/安装/登录/更新 | `references/ch02-下载安装.md` |
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
| 把书/视频蒸馏成自己的 Skill | `references/ch22-打造skill.md` |
| 更多实操案例 | `references/ch23-实操案例集.md` |
| 多 Agent 系统设计 | `references/ch24-多Agent设计.md` |
| 自动化工作流可靠性 | `references/ch25-工作流可靠性.md` |
| 不同岗位怎么用深 | `references/ch26-岗位路线图.md` |
| 行业工作流 | `references/ch27-行业路线图.md` |
| 常用指令模板（直接抄） | `references/appendix-A-指令模板.md` |
| 场景速查表 | `references/appendix-B-场景速查.md` |

## 回答规范

1. 先按路由找到章节，**读完全文再回答**，不要凭印象编功能路径（WorkBuddy 版本迭代快，菜单位置以书为准，拿不准就说"书里是这么写的，当前版本请核对"）。
2. 给步骤时按书里的"目标 → 操作 → 验收"结构讲，每步可验收。
3. 用户要的是"怎么做"，不是"是什么"——多给指令模板（附录A 有现成的），少讲概念。
4. 涉及 Skill 安装/制作，引用 ch05 / ch22 的标准结构。

## 来源

内容源自 AlephAITech/WorkBuddyGuide（MIT 协议，workbuddy.homes），归档日期 2026-10-19。
本 skill 为学习查询用途的整理版本；对外引用请注明原出处。
