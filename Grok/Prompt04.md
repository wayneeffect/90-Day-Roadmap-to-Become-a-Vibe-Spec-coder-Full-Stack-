**Here’s a practical 90-day roadmap to become a proficient Vibe/Spec coder (Full-Stack).** It balances pure “vibe” speed (natural-language prompting + iteration on outcomes) with “spec” discipline (structured plans as the source of truth) while building real full-stack skills.

**Assumptions**: 10–20 hours/week. You have basic computer literacy. No prior coding required (but experience accelerates everything). Focus stack: **Next.js + TypeScript + Tailwind + Supabase (or Prisma + Postgres) + Vercel**. Primary tools: **Cursor** (daily driver), **Claude Code**, plus Lovable/Bolt/v0 for rapid prototyping.

**Core principles throughout**:
- Always review AI output (read diffs, run the code, understand it).
- Document prompts/specs and your process.
- Ship publicly (GitHub + live URLs).
- Mix vibe (explore fast) → spec (lock in structure) → implement → iterate.

### Days 1–30: Foundations + Tool Fluency + First Vibe Projects
**Goal**: Get comfortable directing AI, understand basic web architecture, and ship 2–3 simple full-stack apps.

**Week 1 – Setup & Mental Model**
- Install Cursor, Claude (or Claude Code), Git, Node.js, and a GitHub account.
- Learn the vibe workflow: describe → generate → run → feedback → refine.
- Crash course (via AI explanations + short tutorials): HTML/CSS basics, JavaScript/TypeScript fundamentals, how the web works (client/server, HTTP, APIs), Git basics (clone, commit, push, branches).
- **Deliverable**: Personal landing page or simple portfolio scaffold deployed to Vercel. Document every prompt.

**Week 2 – Pure Vibe Practice**
- Build a Todo app (CRUD) entirely via prompting in Cursor or Lovable/Bolt.
- Add basic UI polish with Tailwind (prompt for components).
- Practice reading generated code and fixing issues by describing symptoms.
- **Deliverable**: Deployed Todo app + short write-up of what worked/broke.

**Week 3 – Full-Stack Intro**
- Add a backend/database layer (Supabase Auth + tables or simple Next.js API routes + SQLite/Postgres).
- Practice connecting frontend ↔ backend via AI prompts.
- Learn basic deployment (Vercel + environment variables).
- **Deliverable**: Todo app with persistent data and simple auth (login/signup).

**Week 4 – Spec Foundations + Second Project**
- Learn to write lightweight specs: user stories, data models, API endpoints, acceptance criteria, non-goals.
- Rebuild or enhance a project starting from a written spec, then hand it to the AI.
- **Deliverable**: Second project (e.g., personal notes app, simple habit tracker, or weather dashboard with API integration) built vibe → spec hybrid. Public GitHub repo + live demo.

**End of Month 1 Checkpoint**: You can ship a basic full-stack app from idea to live URL using AI as the primary coder, and you understand enough code to catch major problems.

### Days 31–60: Hybrid Mastery + Complex Features
**Goal**: Own end-to-end features reliably. Combine vibe exploration with solid specs. Master auth, databases, and real integrations.

**Week 5–6 – Deepen the Stack**
- Next.js App Router, server/client components, TypeScript patterns.
- Database design (schemas, relations, migrations) via Supabase or Prisma.
- Auth flows (email, OAuth if possible), protected routes, role basics.
- Practice writing detailed specs (entities with types, API contracts, edge cases).
- **Project**: Task/project management app (Kanban-style) with users, tasks, statuses, and basic filtering.

**Week 7 – Tool Fluency & Debugging**
- Master Cursor Composer/agent mode and Claude Code for multi-file work.
- Learn context management (rules files, @codebase, structured prompts).
- Debugging discipline: describe symptoms, request tests, verify diffs.
- Add basic error handling, loading states, and form validation.
- **Deliverable**: Polish the task app; add one external integration (e.g., email notifications or calendar).

**Week 8 – Second Substantial Project + Spec Discipline**
- Start every feature with a short written spec → review → AI implementation → human verification.
- Introduce payments (Stripe test mode) or file uploads if relevant.
- Git best practices (meaningful commits, PRs even if solo).
- **Deliverable**: New project (e.g., simple SaaS-like tool: invoice generator, bookmark manager with tags/search, or internal dashboard). Fully deployed with auth + data persistence. Document the vibe → spec process.

**End of Month 2 Checkpoint**: You can take an idea, write a clear spec, generate most of the code with AI, debug/refine it, and ship a multi-user full-stack app. Portfolio has 3–4 live projects.

### Days 61–90: Production Quality + Portfolio + Job/Freelance Readiness
**Goal**: Build production-minded apps, harden skills, and package yourself as a Vibe/Spec coder.

**Week 9–10 – Advanced Features & Quality**
- Testing basics (unit/integration with AI help; run and fix failing tests).
- Security awareness (common AI pitfalls: injection, auth bypass, secrets).
- Performance, accessibility, and basic observability (logs, simple monitoring).
- CI/CD intro (GitHub Actions for deploy/test).
- **Project**: Capstone — a more complete app (e.g., multi-user SaaS MVP with dashboard, CRUD, auth, one paid feature or AI integration like summarization). Use strict spec-first for core architecture, vibe for UI polish and iteration.

**Week 11 – Polish & Documentation**
- Refine all projects: better UX, error states, responsive design, README with setup + architecture notes.
- Write case studies: problem → your vibe/spec process → tech decisions → outcome → what you learned about AI limitations.
- Create a personal site that showcases projects + process (built with the same tools).
- Practice explaining architecture and trade-offs without looking at code.

**Week 12 – Launch & Positioning**
- Publicly share projects (GitHub, LinkedIn/X, Product Hunt if relevant).
- Contribute small fixes or open-source vibe-coded examples.
- Optional: Freelance-style practice (rebuild a real small client request or clone a simple product feature under time pressure).
- Prepare stories for interviews: “Here’s how I used vibe for speed and spec for reliability on Project X.”
- **Final Deliverables**:
  - 4–6 polished, deployed full-stack projects (at least 2 with auth + database + real features).
  - Clear GitHub profile and personal site.
  - Documented process notes or short blog posts on vibe vs. spec workflows.
  - Ability to go from idea → working live app in hours/days while maintaining quality.

### Ongoing Habits (All 90 Days)
- Daily/near-daily tool use (even 30–60 min).
- Always ask AI to explain its code and suggest tests.
- Track what AI does well vs. where it fails (architecture, edge cases, security).
- Review one “senior-level” open-source PR or well-structured repo weekly.
- Join communities (relevant Discord/X/Reddit) and share progress.

**Expected Outcome by Day 90**: You can independently ship production-viable full-stack applications using a hybrid Vibe/Spec approach, with a public portfolio that demonstrates both speed and engineering judgment. This is competitive for junior/mid AI-assisted or full-stack roles, freelance gigs, or internal “AI-native builder” positions. Continue iterating projects and deepening system design afterward.

Adjust pace based on your background—experienced developers can compress the foundations and go deeper on specs, testing, and architecture. Consistency and shipping beat perfection. Start today with Cursor + a simple idea.
