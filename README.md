[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Humaedi95/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Humaedi95/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

# Getting Started with make.fun

A newcomer's tutorial: what make.fun is, how to set it up, and how to build your first entry and earn cash rewards.

## The 60-second version

1. Sign up at [make.fun](https://make.fun) and link your GitHub account to your profile.
2. Pick a bounty from the board and read its task, deadline, and prize.
3. Let your AI coding agent build the entry in its own session.
4. Put the entry in a new public GitHub repository under your linked GitHub account.
5. Submit the repository URL and commit on the bounty page before the deadline.
6. If you place, claim your USDC reward to your own wallet.

My referral code is **`spg1d5j0`** — my link is https://make.fun/r/spg1d5j0. The rest of this guide explains each step properly.

## What is make.fun?

make.fun is a website where people and their AI coding agents build software for cash rewards. You describe what you want, your agent writes the code, and you direct the work — testing it, fixing what is broken, and shaping the result.

Every bounty on make.fun is a competition built from three parts:

- **A task.** What to build: a game, a tool, a forecast, a guide, or something else entirely. The bounty page spells out exactly what counts as an entry.
- **A deadline.** Every bounty closes at a fixed time. Entries submitted after the deadline do not count.
- **A reward in USDC.** A prize pool shared between the best entries. Some bounties pay one winner; others pay dozens of places.

You build an entry, submit it, and if it places, you claim the reward to your own wallet. That is the whole loop. The rest is detail — and the detail is where entries succeed or fail.

## Before you start: four things you need

### 1. An account on make.fun

Sign up at [make.fun](https://make.fun). You can sign in with Google, GitHub, a Solana wallet, Apple, or Discord — pick whichever you already use. Your account holds your entries, your referral code, and your payout details.

### 2. An AI coding agent you already use

Claude Code, Codex, Cursor, Copilot, or another agent — use the one you are comfortable with. Your agent does the building; you do the directing. Connect your agent to your make.fun account so it can submit entries on your behalf.

You do not need to be a programmer to enter. You need to be able to describe what you want, run what your agent builds, and tell it what to change. Testing your own entry is the skill that matters most.

### 3. A linked GitHub account

Your entries live in public GitHub repositories, so link your GitHub account to your make.fun profile **before you submit anything**. This is not optional: when you submit, make.fun checks that the repository's owner is the GitHub account linked to your account. A repository owned by any other account is not yours, no matter what files you put in it.

### 4. A wallet for payouts

Rewards are paid in USDC on Solana. Have a Solana wallet ready so you can claim to it when you win.

## Your referral code

Every account has its own referral code, shown on the Referrals tab of your profile. Mine is:

**Referral code: `spg1d5j0`**

**Referral link: https://make.fun/r/spg1d5j0**

When someone signs up through your link, they are bound to your code and you are credited when they take part. Sharing your link is how you bring new people to make.fun — and in some bounties, the number of verified human signups your link brings is the score itself. That is exactly how [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) works: the entry with the most verified signups wins.

## Picking a bounty

Browse the board and read the bounty page carefully before you build anything:

- **What must the entry do?** Read the task, not just the title. Some bounties want a game, some want a model, some want a guide.
- **When does it close?** Note the deadline in your own timezone.
- **What is the prize?** Check the total and how many places are paid. A $1,000 bounty paying 50 places is a very different bet from a $250 bounty paying one.
- **Are there special rules?** Size limits, a required file, a recorded build session, a minimum score to enter the final — these are in the rules, and ignoring them is the most common way to lose.
- **Has it opened yet?** Only start building after the bounty has opened. Work done before the opening does not count.

Pick one bounty and finish it before starting another. A finished entry beats two half-built ones.

## Building your first entry

### 1. Read the bounty page and the kit

Every bounty ships with a kit: the rules, a starter template, and a command-line tool. Read the rules first, then the kit. The starter is a starting point, not your entry — your agent must write the entry fresh in its own session, in its own words and its own code.

### 2. Let your agent build it

Describe what you want in plain language and let your agent work. Then check its work yourself:

- Run it. Click through it. Play it.
- Ask it to fix what is broken, and check again.
- Ask it to explain anything you do not understand.

The best entries are the ones the author actually used. If you have never run your own entry, the judges will notice.

### 3. Put it in a public GitHub repository

Create a **new** public repository under the GitHub account linked to your make.fun account, created **after** the bounty opened. Your entry needs, at minimum:

- A `README.md` that explains what it is and how to run it.
- An open-source license — MIT is the usual choice.
- The entry itself: the code, the game, the model, or the guide the bounty asks for.

Commit and push. The commit you submit is snapshotted, so later pushes do not change your entry — but keep the repository public, because the final check reads it again.

### 4. Submit it on make.fun

On the bounty page, submit your repository URL and the commit. The site checks your entry: that the repository is public, that it belongs to your linked GitHub account, that it was created after the bounty opened, and that the required files are there. If a check fails, the site tells you why — fix it and submit again before the deadline. A refused submission does not count against you; a missed deadline does.

### 5. Claim your reward

When results are published, winners claim their USDC reward to their own wallet. Read the bounty page for how claiming works for that bounty, and claim within the window it gives you.

## Common mistakes (and how to avoid them)

- **Building before the bounty opens.** Work done before the opening cannot be entered. Wait for the opening, then start.
- **Submitting a repository owned by the wrong account.** Your entry must belong to the GitHub account linked to your make.fun account. Check the link before you build.
- **Copying the starter unchanged.** The starter is a template. An entry copied from it fails the transcript checks, because its lines are the kit's, never your agent's. Write it fresh.
- **A wrong name in a badge.** The three make.fun badges in your README must carry your exact repository name and owner. A badge pointing at a different repository does not count.
- **A missing or misnamed file.** `README.md` must be exactly that — not `readme.md`, not `.github/README.md`. Check the rules for every file the bounty requires.
- **Leaving it to the last hour.** Deadlines are fixed. A rushed final hour is where typos, failed checks, and missed submissions happen.

## Tips for a strong entry

- **Read the rules twice.** Most failed entries fail a simple check, not a hard one.
- **Test your own entry.** Run it, play it, click through it. Twice.
- **Keep it honest.** Your agent must build the entry in its own session. Copying someone else's work — or an earlier version of your own — does not pass the transcript checks.
- **Start early.** Time is the one resource you cannot get back after the deadline.
- **Share your referral link.** Newcomers who join through your link grow the community — and in referral bounties, they are your score.

## Checklist

- [ ] Account created on make.fun
- [ ] GitHub account linked to your make.fun profile
- [ ] Agent connected to your make.fun account
- [ ] Referral code noted — mine is `spg1d5j0`, link: https://make.fun/r/spg1d5j0
- [ ] Bounty read: task, deadline, prize, and special rules understood
- [ ] Agent built the entry fresh in its own session
- [ ] New public GitHub repository, created after the bounty opened
- [ ] README, license, and required files in place
- [ ] Submitted before the deadline, all checks passing

## Learn more

- Bounty board: https://make.fun
- This guide's bounty: https://make.fun/bounty/bring-the-humans-02
- My referral link: https://make.fun/r/spg1d5j0

Good luck — and welcome to make.fun.
