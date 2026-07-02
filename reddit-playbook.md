# Reddit Outreach Playbook — Idea Validation

**Goal:** Validate the agent-to-mobile pain point (Telegram wall-of-text vs. build-your-own-app) with agent developers on Reddit before writing code.
**Target:** Comment on 10–15 threads → DM the ones who engage → clear signal on whether this pain is real and unsolved.

**Note:** reddit.com blocks automated fetching/search tools — all research below must be done manually in the Reddit search bar, not via a search agent.

---

## Where to Look

**Subreddits:** r/AI_Agents, r/LocalLLaMA, r/LangChain, r/AutoGPT, r/ChatGPTCoding, r/SaaS (agent-tagged posts), r/indiehackers

**Search terms to run in each subreddit's search bar** (sort by "New" or "Top — past month"):

| Query | Signal |
|---|---|
| `telegram bot` | Devs who shipped one as a mobile stopgap |
| `streamlit` | Same, for internal/demo UIs |
| `mobile app` agent | Directly asking about mobile distribution |
| `approval flow` OR `human in the loop` | Hit the no-approval-UI wall |
| `frontend` agent | Pain-point posts, not tutorials |
| `MCP-UI` OR `AG-UI` OR `CopilotKit` | Already evaluating open-source workarounds |

**Tier 1 signal:** a post describing an actual build — a Telegram/Slack/Streamlit wrapper, an app store rejection story, or "how do people ship agents to mobile." Reference it by name. Don't paraphrase into something it wasn't.

---

## The Sequence

### 1. Comment first (public, on their thread)
Low-friction reaction, not a pitch. Reference their specific workaround.

> Went through the same fork building [our thing] — Telegram was fast but the output was a wall of text, and a real app felt like weeks before a single user touched it. Curious if that's still where you landed, or did you find something in between?

### 2. DM only if they reply to the comment
Never DM cold off a public post without engaging first — most subreddits ban unsolicited solicitation DMs.

> Hey — saw your post about [their specific workaround]. I'm poking at the same problem: agents that need mobile UI (progress updates, approvals, rich output) without the dev sinking weeks into app store + frontend work. Does that match the wall you hit, or was it something else entirely?

### 3. Branch on their DM reply

**Pain confirmed, still unsolved:**
> What's it costing you right now — time, or did you just decide not to bother with mobile yet?

**They built a workaround already:**
> What made you pick [Telegram/Streamlit/custom] over the alternatives? Curious what tipped it.

**They ask what you're building:**
> Working on a way to connect an agent, configure the UI it renders, and ship to mobile without building the app yourself. Would that have changed your decision?

Only reveal the idea when they ask — this is validation, not a pitch.

---

## What to Track

For each conversation, note:
- Did they mention mobile/UI pain unprompted, or only after you raised it?
- Current workaround: Telegram / Streamlit / custom app / nothing?
- What broke or got expensive about their current approach?
- Would they pay for this, or would they rather build it themselves?

---

## Rules

- Check each subreddit's self-promo rules before DMing anyone.
- Comment publicly first; only DM if they engage.
- Disclose you're building something if asked directly — no stealth marketing.
- Skip any thread where you can't find a real, specific signal — don't send the generic version just to hit volume.
- No links, no product name, in the first comment or DM.
