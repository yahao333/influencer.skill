<div align="center">

# influencer.skill

> *"Content is king, but engagement is empire."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://python.org)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

Every influencer has their unique content style, their signature hooks,
the way they engage with comments, their brand voice,
and the specific energy they bring to every post.

**Preserve content wisdom and style — welcome to cyber-immortality!**

<br>

Provide source materials (videos, posts, comments, chat logs, self-descriptions)
plus your understanding of their content style,
and get an **AI Skill that carries their creator essence**

[数据来源](#支持的数据来源) · [安装](#安装) · [使用](#使用) · [效果示例](#效果示例) · [详细安装说明](INSTALL.md)

[**English**](README_EN.md) · [**中文**](README_ZH.md)

</div>

---

## 支持的数据来源

| 来源 | 说明 |
|------|------|
| 视频内容 | B站/抖音/小红书/YouTube |
| 图文笔记 | 小红书/微博/公众号 |
| 评论互动 | 评论区风格分析 |
| 粉丝反馈 | 粉丝社群风格 |
| 直接粘贴文字 | 手动输入 |

---

## 安装

```bash
git clone https://github.com/yahao333/influencer.skill ~/.claude/skills/influencer
```

## 使用

在 Claude Code 中输入：

```
/influencer
```

### 管理命令

| 命令 | 说明 |
|------|------|
| `/influencer` | 调用 Influencer Skill 创建器 |
| `/list-influencers` | 列出所有已创建的 Influencer Skill |
| `/delete-influencer {slug}` | 删除指定 Influencer Skill |

---

## 效果示例

> 输入：`知识分享型博主，B站，小红书都有，理工男，说话严谨但幽默，喜欢用类比解释复杂概念，互动很接地气`

**场景一：创作讨论**

```
用户      ❯ 我想做一期关于AI的科普

influencer.skill ❯ 好，先想清楚你的受众是谁。
                  是给小白看还是给有点基础的看？
                  确定受众后再定选题角度。
                  开场hook很重要，前三秒不行人就划走了。
```

**场景二：粉丝互动**

```
用户      ❯ 有粉丝说我最近内容水了

influencer.skill ❯ 先别急，这是个好信号。
                  说明粉丝在认真看你，
                  才会有期待落空的感觉。
                  可以做个投票问问他们想看什么，
                  顺便刷一波互动。
```

---

<div align="center">

MIT License © [yahao333](https://github.com/yahao333)

</div>
