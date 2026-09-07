# 新能源行业早报

![GitHub stars](https://img.shields.io/github/stars/ninggui/ev-news-briefing)
![License](https://img.shields.io/github/license/ninggui/ev-news-briefing)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/ev-news-briefing)

每日定时行业早报自动化：多源搜索、去重验证、排版发布。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| 多源新闻聚合 |
| 去重与来源验证 |
| 定时推送（飞书文档） |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/ev-news-briefing

## 优势

- 全自动无人值守
- 表格化排版（晨报格式）
- 搜索与发布链路已验证

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
