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

[Supported Sources](#supported-data-sources) · [Install](#install) · [Usage](#usage) · [Demo](#demo) · [Detailed Install](INSTALL.md)

[**English**](README_EN.md) · [**中文**](README_ZH.md)

</div>

---

## Supported Data Sources

| Source | Description |
|--------|-------------|
| Video content | Bilibili/Douyin/RED/YouTube |
| Image+text posts | RED/Weibo/WeChat |
| Comment interactions | Comment style analysis |
| Fan feedback | Community style |
| Paste text directly | Manual input |

---

## Install

```bash
git clone https://github.com/yahao333/influencer.skill ~/.claude/skills/influencer
```

## Usage

In Claude Code, type:

```
/influencer
```

### Management Commands

| Command | Description |
|---------|-------------|
| `/influencer` | Invoke Influencer Skill creator |
| `/list-influencers` | List all created Influencer Skills |
| `/delete-influencer {slug}` | Delete specified Influencer Skill |

---

## Demo

> Input: `Knowledge sharing blogger, on Bilibili and RED, male STEM personality, rigorous but humorous, loves using analogies to explain complex topics, very down-to-earth in interactions`

**Scenario 1: Content Discussion**

```
User            ❯ I want to make an episode about AI for beginners

influencer.skill ❯ Good, first think about who your audience is.
                  Beginners or people with some foundation?
                  Once you know the audience, decide the angle.
                  The opening hook is crucial — if the first 3 seconds don't work, people scroll past.
```

**Scenario 2: Fan Interaction**

```
User            ❯ A fan said my recent content has been low quality

influencer.skill ❯ Don't panic yet, this is actually a good signal.
                  It means fans are watching you seriously,
                  so they feel let down when expectations aren't met.
                  You could do a poll to ask what they want to see,
                  to boost engagement.
```

---

<div align="center">

MIT License © [yahao333](https://github.com/yahao333)

</div>
