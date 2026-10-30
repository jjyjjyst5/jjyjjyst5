## Hi, I'm Jeff Yingling

Hardware engineer working at the integration layer between AI and physical systems. 15+ years taking hardware from concept to production (PCB, FPGA, firmware, and the integration work between them), and lately building AI systems with Claude Code: agents, MCP servers, and full applications.

Based in Bellingham, WA · [LinkedIn](https://www.linkedin.com/in/jeffrey-yingling-78bab02a)

Most of my code lives in private repos. Source is available on request.

---

### Kwik Kiwi - pickleball round-robin scheduler

**[Try it live](https://quick-kiwi-round-robin.vercel.app)** · React, TypeScript, Supabase, Vercel · 530+ unit tests plus Playwright end-to-end tests

Builds round-robin schedules that maximize partner and opponent variety. For mixed doubles with prime-power player counts, a Galois field construction guarantees every man partners with every woman exactly once; otherwise simulated annealing searches partnerships and court groupings together. Runs offline on one phone, or as a public tournament players join by QR code.

<p>
  <img src="images/kiwi-splash.jpg" width="170" alt="Kwik Kiwi splash screen">
  <img src="images/kiwi-rounds.png" width="170" alt="Round view with court cards and scoring">
  <img src="images/kiwi-analytics.png" width="170" alt="Schedule optimality scores">
</p>

<img src="images/kiwi-partner-matrix.png" width="440" alt="Partner frequency matrix, all ones">

*8 men, 8 women, 8 rounds: every man partners every woman exactly once.*

<details>
<summary>More screenshots</summary>
<br>
<p>
  <img src="images/kiwi-roster.png" width="170" alt="Pasted roster with automatic gender sorting; uncertain names flagged">
  <img src="images/kiwi-leaderboard.png" width="170" alt="Live leaderboard">
</p>
<img src="images/kiwi-optimality-ring.png" width="480" alt="Schedule optimality breakdown">
</details>

### Samantha - AI medical receptionist

**[See the demo](https://samantha-medical.com/)**

<img src="images/samantha-home.png" width="480" alt="Samantha website">

A voice agent for medical practices that answers after hours, steps in when the front desk is busy, and follows up with referred patients to get visits booked. I built it as a solo founder: a HIPAA-compliant voice pipeline with telephony, custom tool calls, and validation. Built with Gemini LLMs, Azure telephony, and Python, developed with Claude Code.

### Job Huntress - AI job search agent

A local-first job search agent. It discovers listings directly from company ATS feeds (Greenhouse, Lever, Ashby, Workable), filters them with free code-side rules, then scores fit against my resume and preferences with an LLM. It tailors application materials and drives guided applications in my own browser with Playwright. It never submits anything without my click.

- Per-task model routing: Claude through a Claude Code subscription, Gemini, or local Ollama
- Python, FastAPI, React, SQLite, Playwright; 100+ tests

### Experiments

- **Imagine Idea Gen** - a multi-agent pipeline that generates marketing ideas from a seed idea, with a Creative Director agent judging each one against the business owner's taste. A prototype built around a founder's request (TypeScript monorepo, Postgres, job queue).

---

**How I build:** Claude Code on feature branches with Git and GitHub, tests alongside the code, and end-to-end checks before I call something done.
