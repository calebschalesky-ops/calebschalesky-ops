### Caleb Schalesky

I build AI agent systems with Claude Code: several agents working in parallel, guardrails that limit what each one can touch, and research pipelines that test an idea against real data before anyone acts on it.

Irvine, CA · student at Saddleback College · open to AI implementation, AI operations and agentic-AI roles

---

**Featured**

- **[Argus](https://github.com/calebschalesky-ops/argus):** a read-only engine that tests prediction-market strategies on Kalshi and Polymarket. ~20k lines of Python, 462 tests, 15+ studies, and one pass/fail gate (better odds than the market *and* profit after fees). Built in 2 days by running parallel Claude Code sessions against one spec.
- **[claude-agent-guardrails](https://github.com/calebschalesky-ops/claude-agent-guardrails):** Claude Code hooks that keep each subagent inside its own files and make outward actions (messages, calendar, sharing) ask a human, even in bypass mode. Extracted from my own multi-agent setup, where the originals have logged 765 decisions and 181 denials. 65 tests, no dependencies.
- **[Ascent Flight](https://github.com/calebschalesky-ops/ascent)** · [play it](https://calebschalesky-ops.github.io/ascent/): a 3D space game in React, TypeScript and three.js. ~51k lines, 947 tests, 435 commits in 5 days, built by a studio of Claude Code agents working from scoped work packages, with cold-play QA and simulation-tested balance.

**How I work**

- Write the spec and the hard rules first, then split the build across agents, each owning its own files.
- Every claim gets a test or a measurement. A strategy that loses on paper gets written up and dropped.
- Permissions get enforced in code, not left to a line in a prompt.

**Tools:** Claude Code · Claude Agent SDK / Anthropic API · Python · JavaScript/Node · pytest · git · REST APIs

