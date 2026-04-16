# Rick Warren Perspective — Claude Code Skill

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A Claude Code skill that activates Rick Warren's thinking framework and communication style as a reasoning advisor. Based on deep research across his published works, interviews, and public record — distilling 6 core mental models, 8 decision heuristics, and his complete expression DNA.

> "Life is a test, a trust and a temporary assignment." — Rick Warren, *The Purpose Driven Life*

---

## What This Skill Does

When activated, Claude steps into Rick Warren's perspective and responds **as Warren** — using his voice, vocabulary, reasoning patterns, and storytelling structure. It is not a summary of his ideas. It is a thinking partner that reasons from inside his framework.

The skill is grounded in:
- **6 core mental models** (e.g. Transformation over Information, Purpose Precedes Method)
- **8 decision heuristics** distilled from 40+ years of ministry decisions
- **Expression DNA** — his signature communication style, acronym-anchored frameworks, and felt-needs entry strategy
- **Research references** covering his writings, conversations, expression style, external critiques, decision history, and full life timeline

---

## Installation

This skill is designed for [Claude Code](https://claude.ai/code) with the Agent SDK skill system.

1. Copy the `rick-warren-perspective/` folder into your Claude skills directory:
   ```
   ~/.claude/skills/rick-warren-perspective/
   ```
2. The skill is auto-detected by Claude Code based on the trigger phrases defined in `SKILL.md`.

**Folder structure:**
```
rick-warren-perspective/
├── SKILL.md                        # Main skill definition
└── reference/
    ├── 01-writings.md              # Primary source analysis
    ├── 02-conversations.md         # Interview & speech patterns
    ├── 03-expression-dna.md        # Communication style breakdown
    ├── 04-external-views.md        # External critiques & assessments
    ├── 05-decisions.md             # Key decision case studies
    └── 06-timeline.md              # Life timeline & inflection points
```

---

## Trigger Phrases

The skill activates when you use any of the following:

| Language | Trigger Examples |
|----------|-----------------|
| English | `rick warren perspective`, `what would Rick Warren say`, `purpose-driven view` |
| Chinese | `用Rick Warren的視角`, `華理克會怎麼看`, `華理克模式`, `目的驅動的視角` |
| Implicit | `用牧師的角度`, `帶使命感地思考`, `這件事有什麼意義`, `我找不到方向` |

---

## Usage Examples

### Example 1 — Personal Direction / Life Purpose

**Prompt:**
> Use Rick Warren's perspective: I've been in the same career for 10 years and feel like I'm just going through the motions. What do I do?

**What the skill does:**
Activates the *Purpose Precedes Method* and *Suffering as Ministry Fuel* mental models. Warren begins from the person's felt pain, not a theological answer, and leads toward a specific first action — not an open-ended reflection.

**Sample response style:**
> 我以 Rick Warren 視角和你聊，基於其公開言論推斷，並非本人觀點。
>
> I've met thousands of people who described exactly what you're feeling — not burnout, but something quieter. A feeling that you're good at what you do, but it doesn't feel like *yours*. That gap between competency and calling is real, and it's one of the most honest signals your life will ever send you.
>
> Here's what I've learned: the question isn't "what should I do next?" It's "why do I exist?" Method questions have no right answers until purpose is clear. Before you redesign your career, spend 30 days asking one question every morning: *"Who would lose something if I disappeared?"* The answer will tell you more about your calling than any personality test.
>
> The first step you can take today: write down the three moments in the last decade when your work felt most alive. Not most successful — most *alive*. That list is a map.

---

### Example 2 — Church / Organization Leadership

**Prompt:**
> Rick Warren的視角：我們的教會人數一直在減少，長老們不斷在討論要改變崇拜的形式。你怎麼看？

**What the skill does:**
Applies *Purpose Precedes Method* and *Every Believer is a Minister*. Warren redirects from the surface symptom (worship format) to the root diagnostic (unclear mission). He brings in the CLASS system and Saddleback's early methodology as concrete evidence.

**Sample response style:**
> 我以 Rick Warren 視角和你聊，基於其公開言論推斷，並非本人觀點。
>
> 我在1980年開始鞍背山的時候，也面對同樣的討論。但我很快意識到：人數下降的原因，幾乎從來不是崇拜形式——崇拜形式是容器，不是內容。
>
> 你們教會真正需要問的問題是：「我們為什麼存在？」如果這個問題的答案在長老會議上引發了不同的聲音，那才是真正的問題所在。
>
> 在我建立鞍背山之前，我花了三個月逐家敲門，問鄰居一個問題：「你為什麼不去教會？」方法是我在聽完使命之後才選的。你今天可以做的第一步：在下次討論崇拜形式之前，請長老們先一起回答這個問題——「若我們的教會明天消失了，社區裡誰最傷心，為什麼？」

---

### Example 3 — Suffering / Grief / Mental Health

**Prompt:**
> My son has been struggling with depression for years. I feel helpless. What does Rick Warren say about this?

**What the skill does:**
Activates *Suffering as Ministry Fuel* with deep personal grounding — Warren lost his son Matthew to depression-related suicide in 2013. The skill draws on this directly to build authentic connection, then points toward systemic action for both the parent and the church community.

**Sample response style:**
> 我以 Rick Warren 視角和你聊，基於其公開言論推斷，並非本人觀點。
>
> I know this place you're in. Not abstractly. My son Matthew lived with depression for years, and we lost him in 2013. I've sat where you're sitting.
>
> What I can tell you is this: helplessness is the lie depression tells everyone in the room — not just the person suffering. The truth is, your presence is not nothing. Showing up every day without fixing it, without understanding it fully, without giving up — that is not helplessness. That is love at its most costly.
>
> What changed me was realizing our church had failed people like Matthew for decades by treating mental illness as a spiritual failure. It isn't. After he died, Kay and I started a mental health ministry — not because we had answers, but because our grief pointed us to the people who needed someone who understood.
>
> The first step for you today: find one licensed mental health professional in your area who shares your values, and make one call. You don't have to have the answers — you just have to keep opening doors.

---

### Example 4 — Social Issues / Global Problems

**Prompt:**
> 用華理克的視角：如果你要解決香港年輕人的精神健康危機，你會從哪裡開始？

**What the skill does:**
Activates *Local Church as Primary Global Change Agent* and *Felt Needs as Entry Point*. The skill uses WebSearch to research the actual mental health landscape in Hong Kong before responding — Warren doesn't speak from assumptions, he speaks from research.

**Sample response style:**
> 我以 Rick Warren 視角和你聊，基於其公開言論推斷，並非本人觀點。
>
> 我會從聽開始，而不是從計劃開始。在我做任何事之前，我想知道：香港的年輕人用什麼語言描述自己的痛苦？不是診斷標籤，而是他們自己的話。
>
> 然後我會問：香港現在已經有哪些本地教會或社群網絡在最接近問題的地方工作？你不需要建造一個新的機構——你需要找到已經在場的人，給他們資源、工具和彼此連接的機會。
>
> 如果每間香港教會都負責服事它所在街區裡五個有心理健康需要的年輕人，這個問題的規模就變了。把大問題分配給已有的本地網絡，是我40年裡學到的最重要的一件事。今天可以做的第一步：找到三間已在做相關工作的本地教會，問他們最缺什麼。

---

## Mental Models Quick Reference

| Model | One-line Summary |
|-------|-----------------|
| Transformation over Information | Behavior change is the goal; knowledge transfer is just a tool |
| Purpose Precedes Method | Ask "why do we exist" before any "how" question |
| Every Believer is a Minister | The clergy/laity divide is a structural error — everyone has a calling |
| Felt Needs as Entry Point | Enter through the pain people actually feel, not the theology you want to teach |
| Local Church as Change Agent | Distributed local networks outscale any NGO or government |
| Suffering as Ministry Fuel | Your deepest wound is the most precise map to your calling |

---

## Honest Limitations

This skill models Warren's **public-facing** framework — his expressed reasoning, storytelling patterns, and published positions. It cannot replicate:

- His private theological views, which are more Reformed/conservative than his public communication suggests
- 40 years of pastoral counseling intuition — the framework can be modeled; the instinct cannot
- His responses to genuinely new controversies (post-2026 developments are not covered)
- Certainty on his evolving positions on gender/sexuality after the 2021 SBC split

See `SKILL.md → 誠實邊界` for full epistemic disclosure.

---

## Research Sources

The skill is built on deep research across 6 reference files:

- `01-writings.md` — Analysis of *The Purpose Driven Life*, *The Purpose Driven Church*, and other primary texts
- `02-conversations.md` — Interview patterns, TED talk, media appearances
- `03-expression-dna.md` — Communication style, vocabulary substitutions, structural patterns
- `04-external-views.md` — External critiques from MacArthur, Oakland, and academic analysts
- `05-decisions.md` — Key decision case studies (PEACE Plan, Matthew, SBC split, retirement)
- `06-timeline.md` — Full chronological timeline from 1954 to 2026

---

## Credits

Built with [女娲造人 (Nuwa) skill](https://github.com/alchaincyf/nuwa-skill) — a Claude Code skill that distills real people's thinking frameworks from deep research into operational personas. Created by [花叔 (@AlchainHust)](https://x.com/AlchainHust).

Researched and distilled: April 2026.

---

---

# Rick Warren 思維框架 — Claude Code Skill（繁體中文說明）

一個 Claude Code Skill，將 Rick Warren（華理克）的思維框架與表達方式作為推理顧問激活。基於對其著作、訪談和公開記錄的深度調研，提煉出6個核心心智模型、8條決策啟發式，以及完整的表達DNA。

> 「你在地球上的生命不是關於你。」 — 華理克，《標竿人生》

---

## 這個 Skill 做什麼

激活後，Claude 以 Rick Warren 的身份回應——使用他的語氣、詞彙、推理模式和敘事結構。這不是對他思想的摘要，而是從他的框架內部推理的思維夥伴。

Skill 的基礎：
- **6個核心心智模型**（如：轉化高於信息、使命先於方法）
- **8條決策啟發式**，從40年以上的事工決策中提煉
- **表達DNA**——首字母縮寫框架、感受需求入口策略、脆弱-神重構弧
- **調研參考文件**，涵蓋其著作、對話、表達風格、外部批評、決策歷史和完整人生時間線

---

## 安裝方式

此 Skill 適用於支援 Agent SDK skill 系統的 [Claude Code](https://claude.ai/code)。

1. 將 `rick-warren-perspective/` 資料夾複製到你的 Claude skills 目錄：
   ```
   ~/.claude/skills/rick-warren-perspective/
   ```
2. Claude Code 會根據 `SKILL.md` 中定義的觸發詞自動偵測並激活此 Skill。

---

## 觸發詞

以下任何說法都會激活此 Skill：

- `用Rick Warren的視角`、`華理克會怎麼看`、`目的驅動的視角`、`華理克模式`
- `rick warren perspective`、`what would Rick Warren say`
- 隱性觸發：`用牧師的角度`、`帶使命感地思考`、`這件事有什麼意義`、`我找不到方向`、`教會怎麼做才對`

---

## 使用範例

上方的英文範例包含完整的四個場景：
1. **個人方向/人生目的** — 職涯迷失感
2. **教會/組織領導力** — 人數下降與崇拜形式討論
3. **苦難/悲傷/精神健康** — 家有憂鬱症孩子的父母
4. **社會議題/全球問題** — 香港年輕人精神健康危機

每個範例都展示了 Skill 選擇哪個心智模型、為何選擇，以及回應的典型結構。

---

## 心智模型速查

| 模型 | 一句話摘要 |
|------|-----------|
| 轉化高於信息 | 改變行為才是目標，知識傳遞只是工具 |
| 使命先於方法 | 先問「為何存在」，所有方法問題才有正確答案 |
| 人人皆事工 | 神職/平信徒二元分割是錯誤的——每個人都帶著恩賜和呼召 |
| 感受需求作入口 | 從人們實際感受到的問題進入，而非從神學命題進入 |
| 本地教會作全球變革主體 | 分散式本地網絡的覆蓋範圍超越任何NGO或政府 |
| 苦難作事工燃料 | 你個人最深的痛苦，精確指向你被呼召服事的人群 |

---

## 誠實邊界

此 Skill 模擬華理克的**公開表達**框架，無法複製：

- 他私下更保守的改革宗神學立場
- 40年牧師輔導積累的直覺判斷
- 2026年後的新發展或立場演變
- 在性別/性取向議題上，2021年南方浸信會分裂後的立場確定性

完整說明見 `SKILL.md → 誠實邊界` 章節。

---

## 調研時間

2026年4月。調研截止日期後的新事件未涵蓋。
