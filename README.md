# Algorise · Engineering & Hiring README

Welcome to the **Algorise digital‑employee platform** codebase. This repo is intentionally light on source but heavy on 💡 *context* so you can decide whether you’d enjoy shipping here.

---

## 1. What We Build

We turn bleeding‑edge LLM tooling into SaaS "employees" that **plan, create and ship** work for real companies. HR is v1; the framework is built to roll out Finance, Ops & CS agents next.

---

## 2. The Stack (bird’s‑eye)

| Layer         | Primary Tools                                           |
| ------------- | ------------------------------------------------------- |
| Frontend      | Next.js, React, Tailwind, Clerk Auth                    |
| Backend       | Python, FastAPI, LangChain, **LangGraph** orchestration |
| Data          | Supabase (Postgres), Neo4j (Knowledge Graph)            |
| Infra         | Docker, AWS ECS / Lambda, Vercel for FE                 |
| Observability | LangSmith traces & eval, OTEL logs                      |

*(Deeper docs live in `/docs/TECH_STACK.md`)*

---

## 3. How We Work  

* **Remote & async‑first.** We default to PRs & RFCs over meetings.
* **Small, owner‑led squads.** “You build it, you run it.”
* **Bias to ship.** Thin vertical slices > grand rewrites.
* **Kindness & candour.** We separate ideas (debated hard) from people (treated well).

Perks: GBP‑benchmarked salary wherever you live, hardware budget, 2× year offsites, \$1k/yr learning stipend.

---

## 4. Application Flow

1. Pick **one** of the technical challenges below (or surprise us with something cooler).
2. Fork this repo, drop your code in `/candidate/<github‑handle>`.
3. Open a PR describing your approach (max 500 words). We’ll review & schedule a 45‑min chat.

No whiteboard questions, no brain‑teasers.

---

## 5. Technical Challenges (choose 1)

| # | Challenge                           | What We’re Looking For                                                                                                                                                       |
| - | ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 | **LangGraph "ContentCritic" Agent** | A minimal agent that accepts raw post text & returns a JSON of `tone`, `sentiment`, `flagged = bool`. Use LangGraph DSL + a single GPT‑4 call. Include unit tests.           |
| 2 | **FastAPI Mini‑Service**            | Build `/healthz` (200 OK) & `/v1/tasks/{id}/run` (POST) that kicks off a dummy async job and streams JSON logs via Server‑Sent Events. Typed with Pydantic v2, fully tested. |
| 3 | **React Timeline Component**        | Replicate the basic task timeline from our product screenshot using TypeScript + Tailwind. Mobile‑first, a11y considered.                                                    |
| 4 | **Neo4j Data Ingest**               | Write a script that ingests a small CSV into a Neo4j graph & exposes a Cypher query showing the 3‑hop neighbourhood for a given node.                                        |

Spend **≤6 hours**. Real‑world trade‑offs welcomed—call them out in the README of your submission.

---

## 6. FAQ

**Q — Is this paid?**
For now, no. We keep tasks small; if it ever grows we’ll compensate.

**Q — Deadline?**
None. Apply when it suits—good engineering talent is worth the wait.

**Q — I use Windows!**
Code must build in a Unix‑like environment (Dockerfile counts), but develop however you like.

---

## 7. License & Privacy

Your submission stays **private**; we will never ship or train models on it without consent. See `DATA_PRIVACY.md` for the boring legal bits.

Looking forward to reading your PR! ✌️
