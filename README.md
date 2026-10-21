### Hi, I'm Sai Rakshith Muda

**I build AI agents, and the tools that keep them honest.**

AI engineer and founder of VitalMaa. B.S. Computer Science, Penn State '26. Open to AI engineering roles.
[rakshithmuda22.github.io](https://rakshithmuda22.github.io) · [LinkedIn](https://www.linkedin.com/in/sai-rakshith-muda-09341a1b4/) · rakshithmuda@gmail.com

#### What I'm building

| Project | What it does | Proof |
|---|---|---|
| [**Belay**](https://github.com/rakshithmuda22/belay) | Open-source firewall for AI agents. Checks every tool call from Claude Code or any MCP client against a policy before it runs, including order-aware rules like "tests must pass before `git push`". `pip install agentbelay` | 114 tests · in a prompt-injection test with a local model, 8/8 runs leaked a planted fake key without it, 0/8 with it |
| [**agentspec**](https://github.com/rakshithmuda22/agentspec) | Deterministic, pytest-style contracts for LLM agent tool calls: ordering, budgets, forbidden tools, argument rules, approval gates. `pip install llm-agentspec` | 173 tests · ~2.7 µs per live check |
| [**agentprobe**](https://github.com/rakshithmuda22/agentprobe) | GitHub Action that enforces architecture rules on every PR and catches behavior changes with differential property tests. No LLM. | 149 tests · v1.0.0 · [blocked a real PR](https://github.com/rakshithmuda22/agentprobe/pull/1) |
| [**stacktrace-time-machine**](https://github.com/rakshithmuda22/stacktrace-time-machine) | Sentry error → GitHub GraphQL blame on the crash line at the deployed release SHA → the PR that last wrote it → Slack. | Named the bug-introducing PR in 80% of 223 real crashes (12 OSS projects) · 115 tests |
| [**informalid**](https://github.com/rakshithmuda22/informalid) | A Claude tool-use interview that turns a cash-only worker's answers into a validated financial profile and screens it against 10 Indian government schemes. | 127 tests · scheme rules sourced from PIB |
| [**codesage**](https://github.com/rakshithmuda22/codesage) | Four concurrent LLM reviewers that post inline PR comments on the exact changed lines. | 136 tests |

Also: [Documind](https://github.com/rakshithmuda22/Documind) (RAG over PDFs with a measured retrieval eval) and [Job-Assistant](https://github.com/rakshithmuda22/Job-Assistant) ([live demo](https://job-assistant-g8dd.onrender.com)).

#### How I work

I design the system, build it with AI coding agents, and verify it like I don't trust it. Every repo has a test suite in CI, and every number in a README comes from a command you can run yourself.

**VitalMaa** is my startup: an AI health companion for Indian families that speaks English, Hindi and Telugu (Flutter, Supabase, Sarvam AI). Private, in development; happy to walk through it.
