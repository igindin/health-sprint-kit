# Health Sprint Kit

A small, friendly kit for building your **own** personal health system through
**Claude Code / Codex** — no GUI to learn, your data stays on your machine.

> **Start here:** open **[start page](https://igindin.github.io/health-sprint-kit/)**
> (the 15-minute start). You don't need a WHOOP or 20 years of scans — an iPhone
> and one question is enough.

## What's in here
- **[index.html](index.html)** — the one-page start guide (also live above).
- **[HANDOUT.md](HANDOUT.md)** — the same, in markdown.
- **[homework/c1.md](homework/c1.md)** — the first homework (gather one source + pick one question).
- **[templates/](templates/)** — `about-me`, file `naming-convention`, the data `layers` model.
- **[registry.yaml](registry.yaml)** — the catalog of skills the `/kit` loader installs.

## How it works (what goes where)
1. **Data** — what you already have: Apple Health export, a lab PDF, notes, calendar.
2. **Skills** — one skill per area (sleep, labs, cycle, recovery, tracking).
3. **Agents** — deep-research + a hypothesis / critic / safety consilium.
4. **Your system** — Today, insights with a confidence label, daily actions.

Data → skills → agents → your system. Keeping the layers separate is what keeps
it honest instead of one big pile.

## The engine
This kit runs on **OpenHealth** — the open-source, local-first health engine:
**https://github.com/igindin/openhealth** (MIT). Clone it, run `make setup`, then
say `/kit` and what you want.

## The rules
- **Thinking partner, not a doctor.** No diagnoses. Medical decisions go to a
  clinician. Anything alarming → stop and seek care.
- Every meaningful number carries a **confidence label (C1–C5)**; low confidence
  is phrased as a question.
- **Don't copy any skill blindly** — a repo may be over-engineered for you or
  built for a different goal. Adapt it to yours.
- **Local-first** — nothing is uploaded; real data and keys stay on your machine.

Built for the AI Mindset Health Sprint. OpenHealth is early and rough in places —
that's fine. You're building *yours*.
