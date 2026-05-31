# Internship Interview Guide — Brazil 🇧🇷

A practical, no-BS guide to tech internship interviews based on real experiences.
Written by a student who went through the process, failed a lot, learned more, and eventually got in.

**Goal:** help you shorten your learning curve with honest, actionable information — the kind you
don't always find on international forums because hiring realities differ in Brazil.

Questions? Reach out on [LinkedIn](https://www.linkedin.com/in/amanda-fernandes-software-engineer/).

---

## How This Guide Works

Everything you need is right here. Company-specific sections link directly to my actual
project repositories so you can see real code, real structures, and real solutions.

---

## Table of Contents

- [Internship Types & Preparation Strategy](#internship-types--preparation-strategy)
- [Live Coding vs Take-Home Projects](#live-coding-vs-take-home-projects)
- [Study Plan (TL;DR)](#study-plan-tldr)
- [Behavioral Prep](#behavioral-prep)
- [Gen-AI Internships (New Trend)](#gen-ai-internships-new-trend)
- [Company Experiences](#company-experiences)
  - [Live Coding](#live-coding)
  - [Take-Home Projects](#take-home-projects)
- [A Note on Mental Health](#a-note-on-mental-health)

---

## Internship Types & Preparation Strategy

| Type | Duration | Typical Profile | Difficulty | Focus |
|------|----------|-----------------|------------|-------|
| Early-stage | 2 years | 3rd–4th semester (~2 years until graduation) | Moderate | OOP, Clean Code, SOLID, Big O, Hash Maps, Two Pointers, Arrays |
| Late-stage | 6 months | 7th–8th semester (close to graduation) | Higher | All above + Linked Lists, Stacks, Queues, Binary Trees, Graphs |

> **Underrepresented group programs** (women, Black, LGBTQIA+, PCD) often have slightly
> more accessible questions. Talk to people who went through them — ask directly.

**Probability-based prioritization:**

| Priority | Topics |
|----------|--------|
| High | Arrays, Strings, Hash Maps, Trees, Graphs, Linked Lists, Stacks/Queues |
| Medium | Heaps, Recursion, DP basics, Sorting |
| Low (don't obsess) | Tries, Bit Manipulation, Greedy, Interval Merging, Segment Trees |

---

## Live Coding vs Take-Home Projects

| | Live Coding | Take-Home |
|---|---|---|
| **Format** | Real-time problem solving | Project delivered within deadline |
| **AI tools** | Not allowed | Allowed — organization matters more than code |
| **What's evaluated** | Problem-solving process, communication, correctness | Architecture, clean code, testing, docs, Git history |
| **Key skill** | Explaining while coding under pressure | Delivering production-quality independently |

**Both require strong communication.** If the interviewer can't follow your reasoning,
the optimal solution won't save you.

---

## Study Plan

### The Numbers

| Metric | My Experience | Community Baseline |
|--------|---------------|-------------------|
| **Total prep time** | ~1 year (on and off) | 3–6 months focused is typical |
| **LeetCode problems** | ~200 | 150–200 is the sweet spot for most internship candidates |
| **Competitive programming** | ~50 | Optional — low ROI for standard interviews |
| **Advent of Code** | ~50 | Fun but not interview-optimized |
| **Theory study** | Significant (started from zero) | Depends on your CS foundation |

### My Timeline (The Honest Version)

I started from absolute zero — weak CS fundamentals, no competitive programming background,
nothing. So a huge chunk of my time wasn't just solving problems; it was learning the theory
behind them first. Big O, data structures from scratch, recursion that didn't make my brain crash.

I spent roughly **1 year** preparing, but it was far from balanced:

- During the semester: almost nothing. Classes drained me and I barely touched LeetCode.
- During breaks/holidays: full degenerate mode. 8–12 hours/day, 10+ problems daily, zero rest.

> **Do not do this.** By the end of every break I was mentally fried. Practically no rest.
> I don't recommend it. What I do recommend:

### What Actually Works (Based on Data & Experience)

**Pacing that sticks:**

- **Weekdays:** 1–2 problems/day consistently beats 10 problems on a random Saturday
- **Weekends/holidays:** 5–8/day max — beyond that, diminishing returns kick in hard
- **Theory days:** Reserve 1–2 days/week for concept study only, no solving

**Method:**

- Follow [Neetcode 250](https://neetcode.io/practice) in order — topic by topic, don't skip around
- 2–3 weeks per topic → mock interview on that topic → move to next
- Spaced repetition: redo the same problems after 1 week, then 2–3 weeks later

**Why consistency > cramming:**

LeetCode is a muscle. You don't build it with 10-hour leg days once a month — you build it with
steady, moderate training. People who solve 1–2 problems daily for 3 months consistently outperform
those who binge 100 problems in two weeks and burn out. This isn't my opinion; it's the most common
pattern among successful candidates on r/leetcode, Blind, and every interview prep community.

**Resources:** [Neetcode](https://neetcode.io) · [LeetCode](https://leetcode.com) · [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850) · [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)

### Difficulty Distribution

Don't waste too much time on Hard problems — they rarely show up in internships.

| Difficulty | Time Allocation | Why |
|------------|-----------------|-----|
| **Medium** | ~70% | These are the bread and butter of most interviews. Master them. |
| **Easy** | ~30% | Don't skip them — some are tricky and teach fundamental patterns you'll need for Mediums. |
| **Hard** | Minimal | Only touch these if you're genuinely curious or have extra time. Low ROI for internships. |

### How I Tackled Each Topic

For every new topic, I followed this order exactly (same as the Neetcode structure):

1. Solve **all Easy** problems first — build muscle memory for the pattern
2. Move to **Mediums** — apply the pattern to more complex scenarios
3. Only then touch **Hards** — and only the most relevant ones

This progression worked well because Easies gave me confidence and fluency before tackling
the difficulty level that actually matters. Adjust based on what makes sense for you.

> ⚠️ **Don't jump around randomly.** I tried solving random problems and it backfired — you end up
> facing techniques you've never seen, feel awful, and waste time. Stick to one topic at a time.
> Speaking from painful personal experience. 😅

> Competitive programming and Advent of Code were personal hobbies — high math focus,
> low ROI for standard interviews. Don't feel pressured.

**Resources:** [Neetcode](https://neetcode.io) · [LeetCode](https://leetcode.com) · [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850) · [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)

---

## Behavioral Prep

**Use STAR:** Situation → Task → Action → Result

1. List 5-7 stories from projects, university, hackathons, group work
2. Write them in STAR format (bullet points, not scripts)
3. Practice with AI or a buddy — aim for natural delivery, 2 min max per story
4. Cover categories: teamwork, conflict, failure, leadership, learning, pressure

**What they want:** self-awareness, ownership, growth mindset, clear communication.

---

## Gen-AI Internships (New Trend)

Companies are adding AI/ML questions even for SWE internships.

**Concepts to know:** RAG, MCP, guard rails, AI agents, orchestration, ML training basics,
fine-tuning, prompt engineering, LGPD/GDPR awareness.

**Daily tools to master:** GitHub Copilot / Cursor, ChatGPT / Claude, Perplexity.
Use them daily so they feel natural.

**You don't need:** deep math, training models from scratch, PyTorch expertise (unless role-specific).

---

## Company Experiences

### Live Coding

<details>
<summary>Amazon</summary>

- **Program:** [e.g., Amazon Mulheres 2025]
- **Duration:** 6-month internship
- **Format:** [e.g., OA + 1 technical round]
- **Topics:** [e.g., Trees, Hash Maps, Arrays — LeetCode Medium]
- **Tips:**
  - [Specific tip]
  - [Specific tip]
- **My solution repo:** [🔗 github.com/your/amazon-prep](https://github.com/your/amazon-prep)

</details>

<details>
<summary>Google</summary>

- **Program:** [e.g., Google Next Step 2026]
- **Duration:** 2-year internship
- **Format:** [e.g., 2 technical rounds]
- **Topics:** [e.g., Arrays, Strings, Graph traversal]
- **Tips:**
  - [Specific tip]
- **My solution repo:** [🔗 github.com/your/google-prep](https://github.com/your/google-prep)

</details>

<details>
<summary>Uber</summary>

- **Program:** [e.g., Uber Mulheres 2025]
- **Duration:** 2-year internship
- **Format:** [e.g., OA + 1 technical round]
- **Topics:** [e.g., Hash Maps, Two Pointers, OOP design]
- **Tips:**
  - [Specific tip]
- **My solution repo:** [🔗 github.com/your/uber-prep](https://github.com/your/uber-prep)

</details>

### Take-Home Projects

<details>
<summary>Artefact</summary>

- **Challenge type:** [e.g., Build a REST API]
- **Deadline:** [e.g., 7 days]
- **What they evaluated:** [e.g., code organization, tests, docs, Git history]
- **Tips:**
  - [Specific tip]
- **My project repo:** [🔗 github.com/your/artefact-challenge](https://github.com/your/artefact-challenge)

</details>

<details>
<summary>DTI</summary>

- **Challenge type:** [e.g., Full-stack app]
- **Deadline:** [e.g., 5 days]
- **What they evaluated:** [e.g., architecture, clean code, deployment]
- **Tips:**
  - [Specific tip]
- **My project repo:** [🔗 github.com/your/dti-challenge](https://github.com/your/dti-challenge)

</details>

<details>
<summary>Grupo Fácil</summary>

- **Challenge type:** [e.g., Feature implementation]
- **Deadline:** [e.g., 3 days]
- **What they evaluated:** [e.g., code quality, problem-solving]
- **Tips:**
  - [Specific tip]
- **My project repo:** [🔗 github.com/your/grupo-facil-challenge](https://github.com/your/grupo-facil-challenge)

</details>

<details>
<summary>iFood</summary>

- **Challenge type:** [e.g., Microservice + tests]
- **Deadline:** [e.g., 10 days]
- **What they evaluated:** [e.g., scalability, testing, documentation]
- **Tips:**
  - [Specific tip]
- **My project repo:** [🔗 github.com/your/ifood-challenge](https://github.com/your/ifood-challenge)

</details>

<details>
<summary>Stech</summary>

- **Challenge type:** [e.g., Algorithmic problem + report]
- **Deadline:** [e.g., 4 days]
- **What they evaluated:** [e.g., logic, explanation clarity]
- **Tips:**
  - [Specific tip]
- **My project repo:** [🔗 github.com/your/stech-challenge](https://github.com/your/stech-challenge)

</details>

---

## A Note on Mental Health

Interview prep is a marathon. The industry moves fast — AI tools change weekly, expectations shift,
and it's easy to feel behind.

**You're not.** Protect your energy:

- Focus on fundamentals over hype
- Use AI tools daily so they feel natural, not intimidating
- Don't try to know everything — nobody does
- Take breaks, touch grass, sleep properly
- Burnout costs more than skipping one study session

Every rejection is data. Every interview teaches something. Keep going.

**Good luck. You've got this.**
