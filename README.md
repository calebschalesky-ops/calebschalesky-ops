### Caleb Schalesky

I build AI tools and automations that take repetitive work off a person's plate: agents that answer inquiries and draft replies, an editor that turns raw phone footage into a finished video, and guardrails so an AI can only touch what it is supposed to.

Irvine, CA · business student at Saddleback College · taking on AI consulting and automation projects for small businesses · contact: [LinkedIn](https://www.linkedin.com/in/calebschalesky/)

---

**What I can build for a business**

- **Inquiry and booking agents:** draft a reply to every new inquiry from the business's own prices and schedule, flag anything it can't answer, log every inquiry and draft follow-ups. Nothing is sent without a human saying yes.
- **AI video editing:** describe the edit in plain words and get back a finished video with captions, plus short vertical clips. Nothing is posted for you.
- **Safe AI setups:** several AI agents working at once, each limited to its own files and required to ask before it sends, books or shares anything.

**Featured work**

- **[Front Desk](https://github.com/calebschalesky-ops/front-desk):** an inquiry and booking agent for gyms, studios and coaches. It drafts replies with the right class, time and price, and plain code checks every price, time and link in a draft against the owner's info page before it is saved. A made-up price becomes a flag, not a draft. 46 tests.
- **[Hermes](https://github.com/calebschalesky-ops/hermes-editor):** an AI video editor. You give it raw clips and a brief like "under 40 seconds, open on the intro", and it writes an edit decision list, cuts the takes, levels the audio to -14 LUFS, adds captions and cuts vertical shorts. Ask for a change in plain words and it re-cuts. 41 tests.
- **[claude-agent-guardrails](https://github.com/calebschalesky-ops/claude-agent-guardrails):** the safety layer from my own multi-agent setup. Each agent can only write its own files, and outward actions (messages, calendar, sharing) stop and ask a human. The originals have logged 765 decisions and 181 denials. 65 tests, no dependencies.

**Just for fun**

<table>
<tr>
<td width="46%">
<a href="https://calebschalesky-ops.github.io/ascent/"><img src="https://github.com/calebschalesky-ops/ascent/raw/main/docs/flight.jpg" alt="Ascent Flight, in flight near Earth" width="100%"></a>
</td>
<td>

### [Ascent Flight](https://github.com/calebschalesky-ops/ascent)

A 3D space game set across the Solar System. Build a pilot, pick one of seven peoples, fit a ship and fly from a training flight up to fleet battles.

Built in 5 days by a team of AI coding agents, each with its own job: engine, balance, content, art and QA. I set the vision and the bar for done.

`React` `TypeScript` `three.js` · ~51k lines · 947 tests

[![Play it in your browser](https://img.shields.io/badge/%E2%96%B6%20Play%20it-in%20your%20browser-0b1d3a?style=for-the-badge)](https://calebschalesky-ops.github.io/ascent/)

</td>
</tr>
</table>

**How I work**

- Start with a small trial project with a clear definition of done.
- Write down what the tool may and may not do before building it.
- Prove it works with tests or a live run, and show you the result before calling it finished.

**Tools:** Claude Code · Claude Agent SDK / Anthropic API · Python · JavaScript/Node · pytest · git · REST APIs
