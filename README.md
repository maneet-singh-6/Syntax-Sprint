# Syntax Sprint

A gamified muscle memory coding trainer that enables beginners in the industry to practice typing code. This was built as the final group project for Dev Academy Aotearoa's Full-Stack Software Development Bootcamp.

**Live:** [TBD: Please use npm run dev in vs code to view locally. The link is subject to all teammates' consented approval.]
**Team:** 5 - built in 2 weeks from 22 Jun to 1 Jul 2026.

## My role

I was the **Agile facilitator** for this project where I ran daily stand-ups and retros, assisted in keeping the ball moving, and helped distribute the tickets evenly according to each member's expectations and learning outcomes.

I contributed to the following areas:
- The shared Supabase client and `requireAuth` middleware (server-side auth)
- The `POST /api/v1/scores` route and its DB function
- A CORS/env smoke test across local + the Render deployment
- Debugging why new users were landing in the auth table but not the
  `users` table

  Formal Declaration: I will mention that many of these concepts required the assistance of Claude LLM models facilitating the learning of new concepts and integrations such as Supabase. I am actively working on building the understanding properly without assistance.

  ## Stack

React · TypeScript · Express · Supabase · Auth0 · Vitest

## Running locally

```bash
git clone git@github.com:maneet-singh-6/Syntax-Sprint.git
cd Syntax-Sprint
npm install
npm run dev
```