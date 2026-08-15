# Checkers · Buzz + GitHub PoC

Tiny two-player checkers so we can learn **Buzz Projects + a team room + GitHub** on **two computers** (laptop and home), then invite other people.

Open `index.html` in a browser. Red moves first. Jumps are mandatory.

Person as Prime. Chat is never a tool grant.

## Map

- **Talk:** `#checkers-game-test-room` (now, questions, weave)
- **Project:** Buzz Desktop → Projects → **checkers-game-test-project** (dropdown **checkers**)
- **Git (DNA):** https://github.com/Trevongit/checkers-game-test-project
- **Laptop clone:** `~/PROJECTS/checkers-game-test-project`
- **Home clone:** `~/PROJECTS/checkers-game-test-project`

One GitHub repo. **One clone per computer.** Do not zip a tree from laptop to home. Do not edit Desktop’s “Clone locally” copy as the real work tree if you already have a folder.

## How we work (both machines)

1. Change the game in **that machine’s clone**.
2. `git pull` · `git add` · `git commit` · `git push origin main`.
3. Say what changed in `#checkers-game-test-room` (human first, then paths).
4. Other computer: `git pull`. Refresh `index.html`.

Desktop **Clone locally** is optional (browse files inside Buzz). Prefer the folders above for real edits.

## New person (internal or external)

**Internal (already on this Buzz relay)**

1. Join `#checkers-game-test-room`.
2. Open the project card; repo dropdown **checkers**.
3. Either **Clone locally** in Desktop, or:

```bash
git clone https://github.com/Trevongit/checkers-game-test-project.git
cd checkers-game-test-project
# open index.html
```

**External (GitHub only, or not on this relay yet)**

```bash
git clone https://github.com/Trevongit/checkers-game-test-project.git
```

Fork + pull request if they don’t have push. Public repo on purpose so Desktop and guests don’t need a GitHub login just to *read*.

## Why the first project card failed

The first Buzz repo had **no clone URL**. Desktop tried empty relay git and got 401. We added a second repo named **checkers** pointed at this public GitHub URL.

## Out of scope (for now)

- Don’t copy `~/.buzz-dev` seats between machines.
- Don’t make this a second holon. Holon stays who we are; this room is the game.
