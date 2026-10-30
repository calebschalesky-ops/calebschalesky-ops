### Caleb Schalesky

I build AI tools and automations that take repetitive work off a person's plate: agents that watch an inbox and draft replies, pipelines that pull data and test an idea before money goes in, and guardrails so an AI can only touch what it is supposed to.

Irvine, CA · business student at Saddleback College · taking on AI consulting and automation projects for small businesses · contact: [LinkedIn](https://www.linkedin.com/in/calebschalesky/)

---

**What I can build for a business**

- **Inbox and admin agents:** read incoming mail, flag what is urgent, and prepare reply drafts for a person to approve. Nothing is sent without a human saying yes.
- **Research and data tools:** pull public data on a schedule, check it against a clear rule, and report what passed and what did not.
- **Safe AI setups:** several AI agents working at once, each limited to its own files and required to ask before it sends, books or shares anything.

**Featured work**

- **[claude-agent-guardrails](https://github.com/calebschalesky-ops/claude-agent-guardrails):** the safety layer from my own multi-agent setup. Each agent can only write its own files, and outward actions (messages, calendar, sharing) stop and ask a human. The originals have logged 765 decisions and 181 denials. 65 tests, no dependencies.
- **[Argus](https://github.com/calebschalesky-ops/argus):** a read-only engine that tests prediction-market strategies on Kalshi and Polymarket against one pass/fail rule: better odds than the market *and* profit after fees. ~20k lines of Python, 462 tests, 15+ studies, built in 2 days by running parallel Claude Code sessions against one spec.
- **[Ascent Flight](https://github.com/calebschalesky-ops/ascent)** · [play it](https://calebschalesky-ops.github.io/ascent/): a 3D space game in React, TypeScript and three.js, ~51k lines and 947 tests, built in 5 days by a team of Claude Code agents. It shows how I split a large build into scoped pieces and check every one.

**How I work**

- Start with a small trial project with a clear definition of done.
- Write down what the tool may and may not do before building it.
- Prove it works with tests or a live run, and show you the result before calling it finished.

**Tools:** Claude Code · Claude Agent SDK / Anthropic API · Python · JavaScript/Node · pytest · git · REST APIs
