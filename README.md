# Algorise — Digital Workforce

> *“We build tireless AI workers so humans can finally take real lunch breaks.”*

## 🍿 TL;DR

Algorise turns lean teams into **enterprise‑grade powerhouses** by shipping SaaS “digital employees” that plan, write and publish marketing content while you sleep. If that sentence made you whisper “finally”, keep reading.

## 🏗️ Architecture in 99 Seconds

| Layer          | Tech & Why We Love It                                                                                      |
| -------------- | ---------------------------------------------------------------------------------------------------------- |
| **Frontend**   | Next.js + React + TypeScript + Tailwind → instant UI dev happiness                                         |
| **Auth**       | Clerk → secure auth in 3 lines, OTPs not included                                                          |
| **Data**       | Supabase (Postgres) for relational stuff; Neo4j for graph queries                                          |
| **AI Spine**   | Python + FastAPI + LangChain + LangGraph + LangSmith → chain, orchestrate, observe                         |
| **Memory**     | RAG over Postgres vectors **and** Knowledge Graph (Neo4j) because remembering the boss’ dog’s name matters |
| **Deployment** | Docker everywhere; AWS for backend muscle; Vercel for frontend speedruns                                   |
| **CI/CD**      | GitHub Actions that yell (politely) when tests break                                                       |


## 👾 The Easter‑Egg Hiring Quest

1. **Fork** this repo (yes, it’s private; if you can’t see it, we already failed 🤦).
2. Create a branch called `hire-me-<your-name>`.
3. Pick **one** quest below and commit your fix/improvement:

| Quest                   | Rough Difficulty | Fame & Glory                                                                                                                         |
| ----------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `001-langgraph-pokemon` | ⭐                | Build a LangGraph agent that answers “Which Pokémon is super‑effective against water types?” using [pokeapi.co](https://pokeapi.co). |
| `002-fastapi-boost`     | ⭐⭐               | Make `POST /generate_posts` scream: bring latency under 200 ms (hint: async & batching).                                             |
| `003-ui-wow`            | ⭐⭐               | Re‑skin the calendar with Tailwind & shadcn/ui; dark‑mode mandatory.                                                                 |
| `004-rag-sharp`         | ⭐⭐⭐              | Bolt a vector‑RAG onto the docs folder so `GET /ask?question=` returns real answers with sources.                                    |

4. Add yourself to `humans.txt` with a one‑liner joke.
5. Open a PR. **Template appears automatically — fill it out, no essay required.**
6. Our Workers + one actual human will review within 48 h.

> Pro‑tip: sneaking a meme into your commit messages increases merge probability by 17 %.

## 🧰 Tech You Should Probably Like

* Python 3.12, FastAPI, Pydantic
* LangChain, **LangGraph**, LangSmith
* RAG, vector stores, **Neo4j** graphs
* Docker, AWS (ECS/Fargate, S3, Secrets Manager)
* Next.js 14 (App Router), React 19, TypeScript, Tailwind, shadcn/ui, Framer Motion
* CI with GitHub Actions
* A dash of dad‑joke energy

## 🎯 What Gets You Extra Points

* You’ve wrestled with AWS IAM and survived.
* You understand **why** we mix Postgres & Neo4j.
* You write tests before the caffeine hits.
* You leave code nicer than you found it.
* You ping us with a Loom or meme explaining your PR.

## 🙅 Stuff We Don’t Care About

* Fancy degrees — your code is your résumé.
* Location — our agents work 24/7, you don’t have to.
* Perfect English — comments in Pythonic pseudocode are fine.

## 🔒 Data & Privacy

We never train on your PR or any user data.

---

*Questions? Open an issue or support@algorise.co.uk
May the PRs be ever in your favour!*
