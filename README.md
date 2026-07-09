# DadStackRank ☕

**World's #1 Dad is taken.** Find out your actual number.

Inspired by ["An Honest Dad Ranking"](https://www.youtube.com/watch?v=HOl8NyPV6HI) from *The Rest Is Science* (Michael Stevens & Hannah Fry): rate yourself on an unmarked line — better yet, hand it to your kid — and get your honest rank among the world's ~1.5 billion dads (or ~2 billion moms). Then put the real number on a mug.

## How it works

- Your mark on the line is read as a percentile against an estimate of living dads/moms.
- The marker only has ~10,000 positions, so each position covers a bucket of ~150k parents; a deterministic hash of your position picks your exact spot in the bucket. Same mark → same rank, every time (and shareable via URL).
- "Order my mug" copies your rank text (e.g. `#457,723 DAD`) to the clipboard and opens [Zazzle's create-your-own mugs](https://www.zazzle.com/custom/mugs) — paste, pick a font, done.

## Stack

One file: `index.html`. No build, no dependencies, no analytics, no cookies.

## Deploy (GitHub Pages)

1. Merge to the default branch.
2. Repo **Settings → Pages → Source: Deploy from a branch**, pick the default branch, folder `/ (root)`.
3. Done — served at `https://<user>.github.io/Dadstackrank/`.
