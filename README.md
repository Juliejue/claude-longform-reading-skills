# Claude Longform Reading Skills

三个面向 Claude / Agent Skills 的中文长文精读教练：AI、人文艺文、Crypto 社会学。

专为 INFP 式深度吸收、灵感共振、哲思延展与行动落地设计的精读助手。

Three Chinese-first Claude/Agent Skills for deep longform reading across AI, art & culture, and crypto sociology.

These skills are designed for INFP-like readers, creators, and thinkers who do not want a quick summary, but want an AI reading partner that can patiently replace the original reading process: reconstruct the argument, preserve texture, explain concepts, weave in bilingual highlights, and turn big ideas into concrete personal practices.

## Skills

| Skill | Best for | Reading lens |
| --- | --- | --- |
| `ai-longform-reading-coach` | AI essays, frontier technology writing, product philosophy, papers, newsletters | Human-AI relationship, cognition, mental models, product philosophy |
| `art-culture-reading-coach` | Art criticism, culture essays, exhibition texts, design/media criticism, humanities writing | Aesthetic texture, philosophy, bilingual close reading, creative resonance |
| `crypto-longform-reading-coach` | Web3 essays, DAO/protocol writing, governance, ownership economy | Social experiments, incentive design, public goods, decentralization philosophy |

## What Makes Them Different

- No shallow summaries: the skills are explicitly designed to deep-read, not compress.
- Substitute reading: they assume the user may not read the original article.
- INFP resonance: they keep philosophical, psychological, ethical, aesthetic, and emotional meaning in the reading process instead of flattening everything into information.
- Bilingual close reading: English highlights are woven into the Chinese explanation.
- Collection curation first: when given a newsletter or article collection, the agent first creates an inspiration menu and asks the user which piece to read.
- Active batching: if the article is long, the agent stops at a natural point and asks the user to continue.
- Actionable ending: each reading ends with concrete habits, prompts, workflow tactics, or social mechanisms.

## Installation

Copy any skill folder into a compatible skills directory, keeping the folder name and `SKILL.md` together.

For example, install one skill:

```text
ai-longform-reading-coach/
└── SKILL.md
```

Or install all three:

```text
claude-skills/
├── ai-longform-reading-coach/
│   └── SKILL.md
├── art-culture-reading-coach/
│   └── SKILL.md
└── crypto-longform-reading-coach/
    └── SKILL.md
```

Each skill is independent and can be installed separately.

## Example Prompts

AI longform:

```text
请使用 ai-longform-reading-coach 精读这篇 AI 长文。
我不读原文，请替我完整吸收思想、逻辑链、人机关系和可落地的思维黑客。
[paste article or link]
```

Art and culture:

```text
请使用 art-culture-reading-coach 精读这篇艺文文章。
请保留语言质感、英文高光、哲学脉络和可转化为写作灵感的部分。
[paste article or link]
```

Crypto:

```text
请使用 crypto-longform-reading-coach 精读这篇 Web3 长文。
不要分析币价或投资机会，只分析机制、激励、治理和社会实验。
[paste article or link]
```

More examples are in [`examples/`](examples/).

## Not Financial Advice

The crypto skill is not for investment advice. It intentionally ignores price, K-line, and trading noise unless those details reveal a deeper mechanism or incentive structure.

## License

MIT License. You can copy, modify, and share these skills.
