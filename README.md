# Getting Started with make.fun — Build Software, Win USDC

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Dqmuhammad/makefun-getting-started-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Dqmuhammad/makefun-getting-started-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**New here? Start with my referral link and we both win:**

👉 **Sign up here: https://make.fun/r/v8ra9xda**

Referral code: **`v8ra9xda`** — make sure this code is bound to your new account when you sign up, so your signup counts.

---

## What is make.fun?

make.fun is a platform where you and your AI coding agent build real software for cash rewards, paid in USDC on Solana. Instead of grinding through tutorials or competing on a CV, you pick a bounty, build the thing, and get paid if your entry wins.

Each bounty is a competition with three ingredients:

- **A task** — something concrete to build (a game, a tool, a website, a forecast, an image — it varies every time).
- **A deadline** — when entries close and when results come out.
- **A reward** — locked in an on-chain escrow on Solana before you even start, so the money is really there.

The twist: you don't code alone. You build with an AI coding agent — Claude Code, Codex, Cursor, Copilot, Gemini CLI, or any other agent that can write code. You direct it, it builds, and you submit the result. Think of yourself as the architect and the agent as the builder: you decide what gets built, it does the typing.

## How a bounty works

The loop is the same for every bounty:

1. **Pick a bounty** from the list on [make.fun](https://make.fun). Check the task, the reward, and the deadline.
2. **Get the kit** — every bounty ships with a starter kit and a CLI that handles registration, bundling, and submission.
3. **Build your entry** with your AI coding agent. The agent writes the code; the transcripts of its sessions are part of the submission.
4. **Submit a public repository** at one commit, together with the transcripts of the AI sessions that built it.
5. **The grader runs every entry the same way**, in a sandbox, so the judging is uniform and fair.
6. **Winners claim the reward** to their own Solana wallet.

Transcripts matter: the session logs prove your own agent did the work. That is what keeps the competition honest — no copy-pasting someone else's finished project and calling it yours.

Most bounties are free to enter. And every new bounty opens with its whole reward already locked in an on-chain escrow on Solana, so you know the prize is real before you spend a single minute building.

## What you need

Before your first bounty, get these four things ready:

- **A Solana wallet** — this is where your reward lands if you win. Any standard Solana wallet works.
- **A GitHub account** — your entry is submitted as a public GitHub repository, so you need somewhere to push it.
- **An AI coding agent** — Claude Code, Codex, Cursor, Copilot, Gemini CLI, or whichever agent you like working with. This is the tool that actually writes the code.
- **Node.js** — the kit CLI runs on Node, so install it if you don't have it yet.

That's it. No entry fee for most bounties, no special hardware, no team required.

## Account setup

1. Go to [make.fun](https://make.fun) and sign up. You can sign in with a Solana wallet, GitHub, Google, or Discord — pick whichever you already use.
2. **If you're new, sign up through my referral link: https://make.fun/r/v8ra9xda** (code `v8ra9xda`). A new account that signs up with that code bound is credited to me — it costs you nothing and it supports this guide.
3. Once you're in, get your API key from your account. You'll need it for the kit CLI.

## Pick a bounty

Browse the bounty list and look for three things:

- **The task** — is it something you can actually build in the time available?
- **The reward** — how much USDC is on the line, and how many places get paid (top 10, top 20, top 50 — it varies).
- **The deadline** — when entries close, and when results are announced.

Start with a free bounty and a task that plays to your strengths. A small, working entry beats an ambitious half-finished one every time.

## Get the kit

Each bounty has its own kit. The kit CLI is `node cli/makefun.mjs` and its commands cover the whole flow:

- `register` / `login` — connect your account to the kit.
- `init` — set up a fresh entry repository for the bounty.
- `bundle` — package your entry and its transcripts for submission.
- `check` — verify your bundle before you send it.
- `submit` — send your entry in.

Run `init` first, in an empty directory, with the competition slug, your keypair, and a license. The kit prints an anchor line — keep it, it identifies your entry.

## Build your entry

This is the fun part. Point your AI coding agent at the task and work with it:

- **Read the task carefully first.** The grader scores against the task as written, so build what it actually asks for.
- **Build in small steps.** Get something running early, then improve it. A working simple version is worth more than a broken clever one.
- **Test it yourself.** Run it, click through it, break it, fix it. The grader runs it in a sandbox — if it doesn't run for you, it won't run for the grader.
- **Keep the transcripts.** Every AI session that builds the entry is part of the submission, so don't delete them.

A practical tip: tell your agent the constraints up front (time limit, what the grader checks, what "done" looks like). A clear brief at the start saves you from a messy rebuild at the end.

Another one: before you start building, run the kit's `check` on an empty or early bundle just to learn what a valid bundle looks like. Catching a packaging problem on day one is far cheaper than catching it an hour before entries close.

## Submit it

When your entry is ready:

1. Run `bundle` to package the repository and the transcripts.
2. Run `check` to verify the bundle is complete and valid.
3. Run `submit` to send it in.

Your entry is a public repository at one commit plus the transcripts of the sessions that built it. Make sure the repo is public — a private repo can't be graded.

## Check, fix, resubmit

Most bounties let you submit more than once — check the bounty rules for how many rounds you get. If a submission is rejected, or you see a way to improve your score:

- Read the rejection or the feedback carefully.
- Fix the specific problem, don't rewrite everything.
- Re-bundle, re-check, and submit again.

Each new round is a fresh shot at a better rank. Use them.

## Claim your reward

When results are out and your entry placed in a paid spot, claim the reward to your own Solana wallet. The reward was locked in escrow from the start, so claiming is just collecting what's already yours.

## Earn with your own referral link

Building isn't the only way to earn on make.fun. Once you have an account, you get your own referral link — just like mine above. Share it with friends, post it where developers hang out, or put it in a guide like this one. Every new account that signs up with your code bound is credited to you.

For this guide, that's:

- Link: **https://make.fun/r/v8ra9xda**
- Code: **`v8ra9xda`**

If this guide helped you get started, signing up through that link is the easiest way to say thanks — and it doesn't cost you a thing.

Good luck, and happy building. 🚀
