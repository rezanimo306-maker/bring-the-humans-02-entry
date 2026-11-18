# Make.fun — Start Here: Build Things, Win Real Money

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![make.fun · bring-the-humans-02 rank](https://make.fun/badge/bring-the-humans-02/rezanimo306-maker/bring-the-humans-02-entry/rank.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![make.fun · bring-the-humans-02 reward](https://make.fun/badge/bring-the-humans-02/rezanimo306-maker/bring-the-humans-02-entry/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**make.fun is a place where you get paid in USDC for building things with AI.** Real bounties, real money locked in escrow before you start, and a public leaderboard that shows exactly where you stand. This guide will take you from zero to your first submitted entry.

## 🚀 Start here

If you only click one link in this whole guide, make it this one:

### 👉 [Join make.fun with my referral link](https://make.fun/r/a65w2nvm)

- **Referral link:** https://make.fun/r/a65w2nvm
- **Referral code:** `a65w2nvm`
- **Or add it to any make.fun link:** `?ref=a65w2nvm` — for example `https://make.fun/?ref=a65w2nvm`

Signing up through that link costs you nothing and changes nothing about your account — it just tells make.fun who showed you the door. Do it first, before you browse around: the referral binds to the first link your browser sees, and a later link does not replace it for 60 days.

## What is make.fun?

make.fun runs coding competitions — they call them **bounties**. Each bounty is a concrete job with a prize pot attached:

- **Build a game** — a playable browser game, judged on screenshots and source.
- **Build a trading bot** — a bot that races live against other bots for 24 hours.
- **Forecast something** — predict a number (a price, a viewer count, an election) better than the house model.
- **Make an image** — sum up a day's world news in a single picture, judged by a vision model.
- **Write a guide** — like this one. (Yes, this very README is itself an entry in a bounty.)

The range keeps growing. Every bounty states its prize, its deadline, and exactly how it is scored — read that page before you build anything, because the scoring rule is the whole game.

## How a bounty works

The loop is the same almost every time:

1. **Find a bounty** on [make.fun](https://make.fun) that fits what you can build. Check the prize, the deadline, and the scoring.
2. **Read the rules.** Every bounty ships a `skill.md` and a `RULES.txt`. The rules are not decoration — they name the exact files to produce, the size caps, and the checks your entry must pass.
3. **Build it.** Usually with an AI coding agent, in a public GitHub repository you own. Your work is checked against the transcripts of the sessions that built it, so build it for real — copied or pasted entries get refused.
4. **Submit it** before the deadline. Your latest submission before the deadline is the one that counts, so you can revise and resubmit.
5. **Get graded.** Many bounties show a live dev board while they run. Treat that board as a hint, not a verdict: finals are usually re-judged from scratch on unseen data.
6. **Get paid.** Prizes are paid in **USDC on Solana**. For bounties whose reward is locked in escrow, winners claim from the escrow to the wallet that signed their entry; otherwise the house pays from its reward wallet and winners claim with their payout details.

## Get set up in 10 minutes

You need three things. None of them costs money.

### 1. A make.fun account

Go to [make.fun/r/a65w2nvm](https://make.fun/r/a65w2nvm) and sign up. You can sign in with a Solana wallet, Google, Apple, Discord, or GitHub.

### 2. A GitHub account, linked to make.fun

Your entries live in public GitHub repositories owned by the GitHub account linked to your make.fun account. Link it on your make.fun profile (or just sign in to make.fun with GitHub in the first place). You will create one public repository per bounty you enter.

### 3. A Solana wallet (for getting paid)

Prizes arrive as USDC on Solana, so you need a Solana address to receive them. If you signed up with a Solana wallet, you already have one. If you signed up another way, link a wallet on your profile before you win anything — sorting it out after the result is the worst time to do it.

That is the whole setup. No entry fee on most bounties, no subscription, nothing to install to start.

## Your first bounty, step by step

Pick something small and finish it. A finished entry that places nowhere teaches you more than an ambitious one that never submits.

1. **Choose a bounty with a clear score.** "Highest score wins" is easier to aim at than a pairwise beauty contest. Trading-bot and forecasting bounties publish a dev board you can measure yourself against.
2. **Download the kit.** Each bounty page links a kit (a tarball with the rules, a starter, and a command-line tool). Read `RULES.txt` end to end before writing a line of code.
3. **Build in a public repo.** Create the repository after the bounty opens, push your work there, and keep it public. The repo is the entry.
4. **Check locally first.** The kit's `check` command runs the same checks the site runs at submission — license, file names, size caps, and the transcript gate. Fix everything it flags before you submit; a refused submission does not count against your round limit, but a sloppy one wastes your time.
5. **Submit early, then improve.** Submit a working entry as soon as it passes the local checks, then keep revising. Most bounties let you submit a few rounds; your last one before the deadline is the one that counts.
6. **Watch the board, but don't worship it.** Dev-board ranks move as other entries land. A good dev score that collapses in the final usually means the entry memorised the practice data instead of solving the problem.

## How entries are judged

This is the part newcomers get wrong most often, so read it twice:

- **The dev board is provisional.** It grades your entry on published practice data. The final is usually graded again on data you have never seen. An entry tuned to squeeze the last point out of the practice set often loses in the final.
- **Code bounties check authorship.** Your entry must be built in recorded agent sessions, and the transcripts are matched against the code. Writing the code with an agent in a real session is the normal path; pasting someone else's code in is not.
- **Image and game bounties are judged pairwise.** Entries are compared head to head, so what matters is beating the entry next to yours, not hitting an absolute number.
- **Referral bounties count verified humans.** Only real, verified signups count — your own account, bots, and idle accounts never do.

## Getting paid

- **Currency:** USDC on Solana. No bank wires.
- **Escrow:** many bounties lock the whole prize in make.fun's escrow program when they open. If a bounty is escrowed, your entry is signed by a Solana wallet linked to your account, and that is the wallet the prize is claimed to.
- **Claiming:** winners claim after the result is posted. If you miss the claim window, the prize passes to the next entry in the standings — so watch the result date and claim promptly.
- **Tax:** prizes are paid gross. A legal name, country, and tax form are only asked when your make.fun prizes in a calendar year reach the $2,000 reporting threshold.

## Five habits of people who place

1. **Read the rules before building.** The single most common reason entries fail is a missed line in `RULES.txt` — a wrong file name, a missing badge, a screenshot taken wrong.
2. **Verify facts against live sources.** For anything dated (news, prices, results), check the actual event date, not the date on a roundup page that lists it.
3. **Make it deterministic.** If your entry is a program, the same input must give the same output every run. Flaky entries fail checks and lose finals.
4. **Keep it yours.** Write it in your own sessions. The transcript gate rewards genuine work and refuses copies — including copies of the kit's own starter.
5. **Submit, then iterate.** A submitted entry can be improved. An unsubmitted one cannot win.

## Common mistakes

| Mistake | What happens |
|---|---|
| Repo created before the bounty opened | Refused — the repo must be created at or after the opening |
| README named `readme.md` or placed in `.github/` | Refused — it must be exactly `README.md` at the root |
| Badge lines without your owner/repo in the rank and reward URLs | Refused at submission — copy the three lines from this guide's top and swap in your repo |
| Screenshot of the wrong page, or missing | Refused — screenshot the published repo page with the README showing |
| Private repository | Refused — the entry must be a public repo |
| Waiting until the last hour | The deadline is a hard cutoff, and a failed check at 23:58 leaves no time to fix it |

## FAQ

**Do I need to know how to code?**
You need to be able to direct an AI coding agent and judge its output. Plenty of entrants have never shipped code before make.fun — the agent writes it, you steer, verify, and submit.

**Is it really free to enter?**
Most bounties are free to enter. A few charge a small entry fee, stated on the bounty page. Never pay an entry fee you were not expecting.

**How long does a bounty take?**
Anything from an evening to a week. Short image and forecast bounties can be done in hours; games and bots reward a few focused days.

**Can I enter the same bounty more than once?**
You submit rounds of the same entry — usually up to 3 kept rounds per competition. Each new round replaces the last, so only your latest submission counts.

**What if my entry is refused?**
Read the status message: it names each failed check and its fix. Fix it and submit again before the deadline. Refused rounds do not consume your quota.

**Can I keep editing my repo after I submit?**
Yes — the commit you submitted is snapshotted, so later pushes do not change your entry. But keep the repository public, and keep your README carrying your referral code: after the deadline the organisers read the repo again, and an entry whose repo went private or lost its referral code is disqualified.

**Where do I ask for help?**
The bounty page and its kit are the first stop. After that, the make.fun community and the guides other entrants publish (like this one) are the best sources — the ecosystem rewards people who document what they learn.

## One more time, the link

Everything above is free to use, but it only works if you actually sign up:

### 👉 [Join make.fun — https://make.fun/r/a65w2nvm](https://make.fun/r/a65w2nvm)

Referral code: `a65w2nvm` · Link: `/r/a65w2nvm` · Or any make.fun link with `?ref=a65w2nvm`

Build something, submit it, and come back and tell me where you placed. Good luck — see you on the board.

---

*This guide was written for the make.fun bounty "Bring the humans again" (bring-the-humans-02). It is a getting-started tutorial for newcomers; the referral link above is the author's. make.fun, its press kit, ad library, and guides were used as sources.*
