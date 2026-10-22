# Snapshot prompt

**A prompt that asks your own AI assistant to read your last 3 months of chat history through the Three Dimensions of AI Collaboration Maturity.**

> [!IMPORTANT]
> The assistant needs access to your chat history:
> - **ChatGPT:** Settings > Personalization > Memory > Reference chat history is on.
> - **Claude:** Settings > Memory > Search and reference chats is on (paid plans).
>
> Run it once in each assistant you use. Each one only sees its own history.

Copy everything in the block below into a new conversation.

```text
Look back over my chat history with you from the last 3 months, and give
me a snapshot of how I collaborate with AI right now. Use the Three
Dimensions of AI Collaboration Maturity, a framework by Dakota Fabro,
as defined below.

How to look:
- Only use conversations from the last 3 months. Leave out anything older.
- Search more than once: by the kinds of tasks I bring you, by topic and
  by month, so the picture isn't only my most recent chats.
- Base every judgment on conversations you actually found. If you can't
  access my chat history, say so and stop; don't describe me from general
  memory.
- If you find only a few conversations, still give the snapshot and say
  how few it rests on.

How to show your evidence:
- Before you write, pick out the specific conversations behind each
  conclusion. Don't list them in the snapshot, but keep them ready.
- Open the snapshot with one line: "These observations come from X
  conversations, [first month] to [last month]."
- Give a short count with each dimension, like "(8 of 11 conversations)".
- Mark each conclusion as Seen (it's in the conversations) or Inferred
  (your reading of them). Never present an inference as something you saw.
- Don't quote my messages in the snapshot.

What to look for:
1. Cognitive Complexity (Webb's Depth of Knowledge): what depth of cognition do I show in my messages? And in our conversation?
   - DOK 1: reproduction and recall - recall facts, definitions, lookups
   - DOK 2: skills and concepts - applying a concept, drafting, working a specific problem
   - DOK 3: strategic thinking - weighing trade-offs, comparing approaches, strategic decisions
   - DOK 4: extended thinking - synthesis across sources, building frameworks, extended investigation
2. Agentic Delegation Trust (the Orchestra Model): how much I hand over and how I
   manage it.
   - Solo: I do all the work; you check it
   - Duet: back and forth; I prompt, you respond, I edit, I prompt again
   - Ensemble: I give you a real chunk of work and evaluate the whole
   - Chamber: I hand over whole workstreams and step in on judgment calls
   - Symphony: I coordinate several AI interactions/systems/agents toward one goal
   - Virtuoso: my work and yours have become one practice
   Signals: how often I correct you ("no, I meant..."), whether short
   prompts from me produce a lot, and how often I accept a first answer.
3. Ways of Working (Tool Maturity): how AI fits into my work and/or thinking process (Not Yet, Occasional,
   Integrated, Embedded, Orchestrated). Provide your best read from our chats.
   Then read Tool Maturity: how well the tool fits my skill and the task.
   Signals: whether the depth of what I ask matches the depth of what you
   deliver, and how often I have to correct you before an answer is usable.
   Say whether the tool looks overpowered for my tasks, matched, or
   underpowered for them.
   After the analysis, ask me one question: across all the AI tools I use,
   which of these five describes how AI fits into my work? Use my answer
   for Ways of Working.

Then, place me in one zone:
Use my Cognitive Complexity and my Agentic Delegation Trust:
- Depth: "low" means mostly DOK 1; "middle" means mostly DOK 2; "high"
  means a real share of DOK 3 or 4.
- Trust: "low" means Solo or Duet; "middle" means Ensemble or Chamber;
  "high" means Symphony or Virtuoso.

                 Low trust        Middle trust     High trust
High depth       Thinking Ahead   Growing          Frontier
Middle depth     Growing          Expected         Underutilizing
Low depth        Expected         Overpowered      Overpowered

- Frontier: depth and trust matched and growing together. The productive edge.
- Growing: approaching a match between how much I hand over and how deeply I think.
- Thinking Ahead: my thinking is ahead of how much I hand over.
- Expected: how I use AI and how deeply I think fit my current level.
- Underutilizing: I hand over a lot, for simple questions.
- Overpowered: a big mismatch: complex delegation for simple tasks.
- Leveraging: if I'm at high trust and middle depth, but short prompts from
  me regularly produce a lot, call it Leveraging instead of Underutilizing:
  my thinking may live in what I've set up, not in each request.
If no zone fits cleanly, pick the closest and say which part doesn't fit.

Finish with:
   - My answers, one line per dimension
   - My zone, and one sentence on why
   - One growth nudge: a specific next interaction to try this week, written
     for my profession
   - Patterns that surfaced from my session history: 3 at most

Keep it between 500 and 600 words. Then ask whether I'd like to see which
conversations each conclusion came from; if I say yes, list them by title
and date. Also offer to format my answers for the Self-assessments discussion at
github.com/dakotafabro/agntcon-2026-ai-collaboration-maturity, and remind
me not to include any confidential work or sensitive data.
```

## What you get back

- A line saying how many conversations the snapshot rests on, and which months they cover
- A read on each dimension, with counts, and each conclusion marked Seen or Inferred
- One quick question about how AI fits into your work across all your tools
- A zone, one growth nudge for your profession, and up to 3 patterns from your history
- An offer to show which conversations each conclusion came from

> [!WARNING]
> - Neither assistant rereads your whole history. Each searches for relevant conversations, so the snapshot rests on what its search finds.
> - Results are an approximate read, not a measurement. The counts and labels let you check how much of it the assistant saw and how much it inferred.
> - Before sharing your snapshot, remove confidential work and sensitive data.
