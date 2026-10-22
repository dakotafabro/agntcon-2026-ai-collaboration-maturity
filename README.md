# AI Collaboration Maturity: A Framework Beyond Engineering

**The companion repo for Dakota Fabro's AGNTCon 2026 talk: what it covers, a prompt to take your own snapshot, and a place to ask questions and keep the conversation going.**

Most AI maturity models measure how advanced your tools are. This talk looks at the relationship between a person and their tools instead, across three dimensions: how deeply you think with AI, how AI fits into your work, and how much you trust it with. A hobbyist and Hendrix can hold the same guitar; what emerges is not the same.

> [!NOTE]
> Questions don't need to wait for the end of the talk. Post them in [Discussions](../../discussions) during or after, in the room or on the livestream. Dakota answers there after the talk, and attendees are welcome to answer and discuss with each other.

**Slides:** [agntcon.dakotafabro.dev](https://agntcon.dakotafabro.dev)

## Take your snapshot

Paste the [snapshot prompt](snapshot-prompt.md) into ChatGPT or Claude with chat history turned on. It reads your last 3 months of conversations and places you on each dimension, with one growth nudge for your profession.

Using goose? [rp-why](https://github.com/dakotafabro/rp-why) measures your goose sessions directly: `/rp-why current`, `/rp-why baseline` (all your goose history) and `/rp-why compare`.

## Discussions

- **[Ask Me Anything](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/1):** ask anything from the talk. Anyone can answer; answers can be marked.
- **[Idea Share](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/3):** want to collaborate or get feedback? Start here.
- **[Self-Assessment Shareout](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/2):** share where you landed and what surprised you.
- **Add to the discourse,** one thread per question:
  - [What else should AI practitioners consider?](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/4)
  - [Where do you agree?](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/5)
  - [Where does it push your thinking?](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/6)
  - [What would you add or take away from the framework presented?](https://github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity/discussions/7)

Posts show your GitHub username. Share only what you're comfortable having public.

<details>
<summary>The three dimensions</summary>

**Cognitive Complexity** (Webb's Depth of Knowledge): how deeply you think with AI.
- DOK 1: recall and reproduction
- DOK 2: skills and concepts
- DOK 3: strategic thinking
- DOK 4: extended thinking

**Ways of Working** (Tool Maturity): how AI fits into your work. Not Yet, Occasional, Integrated, Embedded, Orchestrated. At every level, Tool Maturity asks one question: does the tool fit your skill and the task?

**Agentic Delegation Trust** (the Orchestra Model): how much autonomy you grant AI, and how skillfully you manage it. Solo, Duet, Ensemble, Chamber, Symphony, Virtuoso.

**Zones** come from where Cognitive Complexity and Agentic Delegation Trust meet: Frontier, Growing, Expected, Thinking Ahead, Underutilizing, Overpowered. One more to consider: high trust at DOK 2 when short prompts carry a lot, which rp-why calls Leveraging.

</details>

<details>
<summary>rp-why's names and the talk's names</summary>

rp-why and the talk describe the same framework with some different names. Source: [`scripts/rp_why_core.py`](https://github.com/dakotafabro/rp-why/blob/01ccc9e/scripts/rp_why_core.py) at `01ccc9e`.

- **"TM tier" (Solo to Virtuoso)** in rp-why is the talk's **Agentic Delegation Trust** level. rp-why estimates it from session behavior: sub-agents, number of tools and prompt count.
- **rp-why has no Ways of Working question.** The snapshot prompt asks it.
- **Zones:** the talk uses rp-why's grid of DOK and the tier.
  - **Leveraging:** rp-why's name for the high-tier, DOK 2 profile with compression of 10% or more: complexity that lives in the configuration. The talk calls it out as something to consider.

</details>

## Related

- [Slides](https://agntcon.dakotafabro.dev)
- [rp-why](https://github.com/dakotafabro/rp-why): the goose skill this framework started as
- [dakotafabro.dev](https://dakotafabro.dev)
- [usebpm.dev](https://usebpm.dev): the package manager rp-why installs from
- [LinkedIn](https://linkedin.com/in/dakotafabro)
