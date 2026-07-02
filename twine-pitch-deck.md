# Twine Pitch Deck

---

## Slide 1 — Cover

**Twine**
Ship your agent to mobile. Without building a mobile app.

### Speaker Notes
Start with the problem, not the product. Most agent developers are spending weeks building the wrong thing — a mobile frontend — instead of the agent itself. Twine is the answer to that. Keep this slide up briefly, let the headline land, and move on.

---

## Slide 2 — Problem

**To reach users on mobile, every agent developer faces the same fork.**

**Option 1 — Messaging apps (Telegram, WhatsApp, Slack)**
Fast to ship. But built for humans talking to humans, not agents.
- No progress updates or tool-call visibility
- No approval flows before actions are taken
- No rich UI — cards, forms, charts, timelines
- Agent output becomes a wall of unformatted text

**Option 2 — Build your own app**
Full control. But the frontend becomes the project.
- App store submission and review cycles
- Ongoing frontend maintenance
- Auth, security, push notifications
- Weeks of work before a single user interaction

**Either way, time is taken away from building your agent.**

### Speaker Notes
This is the moment to make the investor feel the pain. Every agent developer hits this fork. They want their agent in users' hands — on mobile, where users actually are — and they have exactly two options, both of which cost them the thing they can least afford: time on the agent. The messaging path is fast but broken — ask them if they've seen a founder demo where the agent output is just a wall of text in a Telegram thread. That's what limited UI looks like in practice. The build-your-own path sounds like control but it's a trap — app store alone can take weeks before rejection. The closing line is the key: either way, time is taken away from building your agent. That's the problem Twine solves.

---

## Slide 3 — Solution

**Twine is mobile infrastructure for agent developers.**

Connect your agent. Configure the UI it renders. Ship to your users.
You focus on the agent. Twine handles everything your users see.

What developers get:
- SDK to connect any agent
- UI component configuration — cards, forms, charts, approval flows
- Observability into how users interact with the agent

What your users get — without you building it:
- A polished mobile app
- Rich UI that matches your agent's output
- Approval flows and real-time progress updates
- End-to-end secure communication

### Speaker Notes
Lead with the infrastructure framing — this isn't a tool you try, it's a layer you build on. Twine doesn't touch the agent logic. What Twine does is sit between the agent and the user: it takes the agent's output and renders it into a polished mobile experience that the developer never had to build. The right column isn't a second audience — it's the outcome the developer is buying. Their users get a great experience; the developer gets none of the work that comes with building it. The closing line is the pitch in one sentence: you focus on the agent, we handle everything your users see.

---

## Slide 4 — Validation

**The workarounds are already everywhere.**

Developers are hacking around it today — Telegram bots, Slack apps, Streamlit, custom React frontends.

Open-source projects forming around the gap: AgentLabs, CopilotKit, MCP-UI, AG-UI, Google Opal.

Nobody has owned mobile. That's the gap.

### Speaker Notes
The market is already moving — just without a clear winner. Every one of these workarounds is a signal: developers know chat isn't enough, and they're patching around it however they can. The open-source projects are particularly telling — when engineers start building infrastructure around a problem, the problem is real. But none of these projects have owned mobile. That's the white space Twine is moving into.

---

## Slide 5 — Insight

**The interface matters as much as the agent.**

Useful agents research, compare, plan, book, monitor, trigger. Text can't carry all of that.

Your users need to:
- See what's happening, not just what happened
- Step in and control, not just watch
- Interact with rich UI, not parse a text reply

And developers need their users to have that experience — without spending weeks building it.

### Speaker Notes
This is the strategic bet. The model wars are real, but the interface layer is being ignored. A great agent with a bad interface will lose to a worse agent with a better one — every time. The three bullets aren't features, they're user needs that text alone can't meet. If your agent is booking a flight, the user needs to see the options, pick one, and approve the booking. A text reply can't carry that interaction. That's what Twine renders — and the developer gets that outcome without touching the frontend. Let the visual do the closing work, then move to the business model.

---

## Slide 6 — Business Model

**Developers pay to skip the mobile frontend.**

Monthly subscription — SDK, dev platform, and rendering layer instead of building it in-house.

What developers don't have to handle:
- App store submission and review cycles
- Ongoing frontend maintenance and observability
- Auth, security, and push notifications
- Building the polished mobile experience their users expect

Scales with the agent and workflow complexity.

### Speaker Notes
The value prop is time and focus. App store submission alone can take weeks — and that's before any rejections. Developers who choose Twine are buying back engineering time and redirecting it to the thing that actually matters: their agent. Their users still get a polished mobile experience — approvals, rich UI, secure comms — the developer just didn't have to build any of it. The subscription starts simple and scales as the agent grows in users and complexity. This is a developer-side subscription — the developer pays, not the end user.

---

## Slide 7 — Market

**Two fast-growing markets. Twine sits at the intersection.**

The agent market is exploding:
- AI agent market growing from $5.4B (2024) to $50B+ by 2030 — ~46% CAGR ¹
- 82% of enterprises planning agent integration within 3 years ²
- Vertical AI agents the fastest growing segment at 62.7% CAGR ³

Mobile is where users already are:
- Mobile app market at $235B today, growing to $750B+ by 2033 ⁴

Twine's position: as agents multiply, so does the need for a rich mobile UI layer. We're building that layer once, for every agent developer who doesn't want to build it themselves.

### References
1. Grand View Research — AI Agents Market Report, 2025
   https://www.grandviewresearch.com/industry-analysis/ai-agents-market-report

2. Nevermined — AI Agent Market Size Statistics, 2025
   https://nevermined.ai/blog/ai-agent-market-size-statistics

3. MarketsandMarkets — AI Agents Market Report, 2025
   https://www.marketsandmarkets.com/Market-Reports/ai-agents-market-15761548.html

4. SkyQuest — Global Mobile Application Market Report, 2025
   https://www.skyquestt.com/report/mobile-application-market

### Speaker Notes
Two tailwinds, one platform. The agent market is growing faster than almost any technology sector in history — 46% CAGR means it's nearly doubling every 18 months. Mobile is already the dominant computing surface — users spend an average of 4.9 hours a day on mobile apps. Every new agent product that wants to reach users in their daily life will eventually need a mobile frontend. Twine is building that layer once, so every agent developer doesn't have to build it separately. Note to presenter: references 4 and 5 in the original pointed to the same SkyQuest report — worth sourcing a second citation for the 4.9 hours stat before a technical investor asks.

---
