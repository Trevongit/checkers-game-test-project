# Checkers · Buzz test game

Tiny two-player checkers so we can exercise **Buzz Projects + a team room + git**.

Open `index.html` in a browser. Red moves first. Jumps are mandatory.

## Buzz map

| Piece | Where |
| --- | --- |
| Talk | `#checkers-game-test-room` |
| Project card | Projects → **checkers-game-test-project** |
| Git | https://github.com/Trevongit/checkers-game-test-project |
| Kept claims | only if you later want a forum — not required for this test |

Chat is never a tool grant. Human first in the room.

## Why Desktop said “Repository access failed”

The Buzz project was announced **without a clone URL**. Desktop then tried the relay’s own git path (`/git/<your-pubkey>/checkers-game-test-project`). That repo was never pushed, so git answered **401**.

Fix: attach this **public** GitHub URL to the existing announcement (you must do this as **open121**, the project owner):

```text
https://github.com/Trevongit/checkers-game-test-project.git
```

Then Retry on the project page. Public GitHub clones in Desktop without extra credentials.

## Local

```bash
cd ~/PROJECTS/checkers-game-test-project
# open index.html
```
