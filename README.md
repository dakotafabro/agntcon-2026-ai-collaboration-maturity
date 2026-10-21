# AI Collaboration Maturity: A Framework Beyond Engineering

**The companion repo for Dakota Fabro's AGNTCon 2026 talk: what it covers, a prompt to take your own snapshot, and a place to ask questions and keep the conversation going.**

Most AI maturity models measure how advanced your tools are. This talk looks at the relationship between a person and their tools instead, across three dimensions: how deeply you think with AI, how AI fits into your work, and how much you trust it with. A hobbyist and Hendrix can hold the same guitar; what emerges is not the same.

> [!NOTE]
> Questions don't need to wait for the end of the talk. Post them in [Discussions](../../discussions) during or after, in the room or on the livestream. Dakota answers there after the talk, and attendees are welcome to answer and discuss with each other.

## Take your snapshot

Paste the [snapshot prompt](snapshot-prompt.md) into ChatGPT or Claude with chat history turned on. It reads your last 3 months of conversations and places you on each dimension, with one growth nudge for your profession.

Using goose? [rp-why](https://github.com/dakotafabro/rp-why) measures your goose sessions directly: `/rp-why current`, `/rp-why baseline` (last 3 months) and `/rp-why compare`.

## Discussions

- **Questions:** ask anything from the talk. Anyone can answer; answers can be marked.
- **Discussion:** one thread per section of the talk, for conversation and ideas.
- **Self-assessments:** share where you landed and what surprised you. The form asks for levels and reflections, not your work.

Posts show your GitHub username. Share only what you're comfortable having public.

<details>
<summary>The three dimensions</summary>

**Cognitive Complexity** (Webb's Depth of Knowledge): how deeply you think with AI.
- DOK 1: recall and reproduction
- DOK 2: skills and concepts
- DOK 3: strategic thinking
- DOK 4: extended thinking

**Ways of Working:** how AI fits into your work. Not Yet, Occasional, Integrated, Embedded, Orchestrated. Each level has a fit question: is this level right for the work?

**Delegation Trust** (the Orchestra Model): how much autonomy you grant AI, and how skillfully you manage it. Solo, Duet, Ensemble, Chamber, Symphony, Virtuoso.

**Zones** come from how the three line up: Frontier, Growing, Bottlenecked, Thinking Ahead, Underutilizing, Overpowered, Efficient Executor.

</details>

<details>
<summary>rp-why's names and the talk's names</summary>

rp-why and the talk describe the same framework with some different names. Source: [`scripts/rp_why_core.py`](https://github.com/dakotafabro/rp-why/blob/01ccc9e/scripts/rp_why_core.py) at `01ccc9e`.

- **"TM tier" (Solo to Virtuoso)** in rp-why is the talk's **Delegation Trust** level. rp-why estimates it from session behavior: sub-agents, number of tools and prompt count.
- **rp-why has no Ways of Working question.** The snapshot prompt asks it.
- **Zones:** rp-why computes them from DOK and the tier only.
  - **Frontier, Thinking Ahead, Overpowered:** close to the talk's meaning.
  - **Underutilizing:** in rp-why, the highest tiers used for DOK 2 work. In the talk, low DOK with low trust.
  - **Growing:** in rp-why, one cell of the DOK and tier grid. In the talk, building on all three dimensions.
  - **Expected, Leveraging:** rp-why only. Leveraging is the high-tier, DOK 2 profile with compression of 10% or more: complexity that lives in the configuration.
  - **Bottlenecked, Efficient Executor:** talk only.

</details>

## Related

- [rp-why](https://github.com/dakotafabro/rp-why): the goose skill this framework started as
- [dakotafabro.dev](https://dakotafabro.dev)
- [LinkedIn](https://linkedin.com/in/dakotafabro)
