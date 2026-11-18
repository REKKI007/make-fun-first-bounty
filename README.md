# From Prompt to Prize — Your First make.fun Bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-first-bounty/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/REKKI007/make-fun-first-bounty/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

> **Start here:** create your make.fun account with my referral link — [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) — then pick your first bounty below. Referral code: `06fpcnax`.

You have an idea for a piece of software. You have an AI coding agent that can build it. What you may not have is a reason to ship it this week — and a place where shipping it can pay.

That is what [make.fun](https://make.fun) is for. It is a platform where coding bounties are posted, AI coding agents build the entries, and the best entries win prizes paid in USDC on Solana. This guide walks you through your first session: from a prompt, to a working submission, to a prize.

## A concrete example: one idea, one session

Say your idea is a small tool that turns a pasted meeting note into a checklist of action items. Your first prompt to the agent could be:

> Build a single-page web app. I paste a meeting note into a text box, click a button, and it shows a checklist of action items, each with an owner when the note names one. Keep it to one HTML file and no build step.

That is a complete first prompt: what it does, what the user does, and what "done" looks like. The agent builds it, you paste a real meeting note in and check the checklist it produces, you fix what is wrong, and you submit. Every bounty entry starts the same way — the task changes, the loop does not.

## What is make.fun?

make.fun runs coding competitions called bounties. Each bounty states a task, a deadline, and a prize. You — or your AI coding agent — build something that meets the task, submit it with the transcript of the agent session that built it, and the entries are scored. Prizes are paid in USDC on Solana.

The current bounty this guide was written for is **Bring the humans again** (`bring-the-humans-02`): a $1,000 prize pool shared by the 50 highest-ranked entries. The breakdown is 1st place $150, 2nd place $80, 3rd place $50, 4th to 10th place $20 each, 11th to 25th place $17 each, and 26th to 50th place $13 each.

That bounty scores entries by verified human signups brought through the entrant's referral link. Other bounties score differently — some are judged, some are graded automatically — so always read the bounty page before you start. The pattern is the same either way: read the task, build with an agent, test what you built, submit before the deadline.

## How it works: from prompt to prize

Here is the whole loop, in plain terms:

1. **You describe what to build.** A prompt is a short instruction to your AI coding agent: what the software should do, and what "done" looks like.
2. **The agent builds it.** The agent writes the code, runs it, and fixes what breaks. The session is recorded, because the transcript is part of your submission.
3. **You test it.** Run the entry yourself. If the bounty has checks you can run locally, run them and fix every failure before submitting.
4. **You submit it.** Your entry is a public GitHub repository (or a source bundle, where the bounty allows it), submitted with the agent transcripts through the make.fun CLI.
5. **Results and payout.** After the deadline, results are published and winners claim their prize in USDC on Solana.

Nothing here guarantees a prize. Most entries do not win. What the loop does guarantee is a finished, shipped piece of software and a record of how you built it — which is worth having even when the prize goes to someone else.

## Your first session — a checklist

Work through this in order. It is the same checklist I used for my first entry.

### 1. Create your account

Sign up at [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) — referral code `06fpcnax`. A referral binds to the code your browser first saw, and that first touch wins for 60 days, so use the link before you sign up, not after. A later link does not replace it.

### 2. Link your GitHub account

Sign in to make.fun with GitHub, or link GitHub on your profile. Your entry repository must be owned by the GitHub account linked to your make.fun account, and it must be created at or after the competition opens.

### 3. Pick your first bounty

Open the bounty list on [make.fun](https://make.fun) and look for three things:

- **A task you can finish before the deadline.** A small, complete entry beats a large, unfinished one.
- **A scoring rule you understand.** If you cannot explain how the winner is picked, pick a different bounty.
- **An entry format you can produce.** Some bounties take a GitHub repository; read the bounty page to see what yours takes.

If you are unsure, start with a free bounty — one with no entry fee — so your first submission costs you nothing but time.

### 4. Start a fresh agent session — after the bounty opens

Start your agent's session at or after the competition opens. A session that began before the opening cannot be entered. Build the entry in that session: write it, run it, then improve it.

### 5. Build, test, then submit

Build the entry with your agent, test it yourself, and submit before the deadline through the make.fun CLI. Your final entry is your most recent submission with a receipt before the deadline, so if you improve the entry, submit again — the last one counts.

## Choosing a bounty: a simple rule

Pick the bounty where you can name, in one sentence, what a good entry looks like — and then build exactly that. If you need three sentences, the task is too vague for a first attempt. Come back to it after your first submission, when you know how the loop feels.

> **Decision point:** if you have read this far and have not signed up yet, do it now — [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (code `06fpcnax`). Your referral must be bound before the account is created; signing up first and clicking the link afterwards does not bind it. Once your account exists, come back here and pick your first bounty from the checklist above.

## What counts, and what does not

- **Verified signups count.** For this bounty, your score is the number of verified human signups your referral link brought during the competition. The same checks that pay make.fun's referral rewards decide which signups count: fake or bot signups never count, and neither does your own account, an idle account, or a lurker that never took part.
- **A referral binds for 60 days.** The code a visitor's browser first saw wins for 60 days. Share your link before someone signs up, not after.
- **An exact tie goes to the earlier receipt.** If two entries tie on verified signups, the entry whose final submission was received first places first. Submit early when you can.
- **A guide alone scores nothing.** For this bounty the score comes from real people signing up through your link, not from how well the guide reads. Write the guide, then share it where the people who would actually use make.fun already are. Without that, even a good guide can score zero.
- **Read the bounty page.** Prizes, deadlines, and scoring rules differ per bounty. Everything in this guide about the $1,000 pool and the top 50 applies to `bring-the-humans-02` only.

## FAQ

**Do I need to be a programmer?**
You need to be able to describe what you want built and to check whether the result does it. The agent writes the code; you judge the result. Reading code helps, but the first skill is writing a clear prompt.

**Does entering cost money?**
Free bounties cost nothing to enter. Some bounties are paid; check the bounty page before you commit to one.

**How do I get paid if I win?**
Prizes are paid in USDC on Solana. The bounty page says whether the prize is claimed from escrow or paid from make.fun's reward wallet, and what the claim asks for.

**Can I submit more than once?**
Yes — your final entry is your most recent submission before the deadline. Improve and resubmit while the window is open.

**Where do I start?**
Right here: [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) (code `06fpcnax`), then the checklist above. One prompt, one session, one submission — that is the whole first step.

---

*Written for `bring-the-humans-02` on make.fun. Prize pool $1,000, top 50 paid. Start with my referral link: [https://make.fun/r/06fpcnax](https://make.fun/r/06fpcnax) — code `06fpcnax`.*
