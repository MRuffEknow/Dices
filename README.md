# 🎲 1-4-24

A browser dice game you can host on GitHub Pages — no build step, just `index.html`.

**House rules:** everyone puts $1 in the pot each round. Roll a die off the table and it's another $1 in the pot.

## How to play

- Roll **six dice**. After every roll you must **keep at least one** die, then roll the rest, until all six are kept.
- To qualify you need a **1** and a **4** among your kept dice.
- Your score is the total of the **other four** dice. The best possible hand is 1-4-6-6-6-6 = **24**.
- A die that flies off the table costs the shooter $1, and that roll doesn't count. The odds are adjustable, and there's a button for real-life spills.
- High score wins the pot. Ties or no qualifiers carry the pot over to the next round.

Players, money and the pot are saved in your browser (`localStorage`).

## Publish on GitHub Pages

1. Merge this branch into `main`.
2. In the repo go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. The game will be live at `https://<your-username>.github.io/Dices/` in a minute or two.

To try it locally, just open `index.html` in a browser.
