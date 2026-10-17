# 🎲 Ship, Captain & Crew

A browser dice game you can host on GitHub Pages — no build step, just `index.html`.

**House rules:** everyone puts $1 in the pot each round. Roll a die off the table and it's another $1 in the pot.

## How to play

- Each player gets up to **3 rolls** of five dice.
- You need a **6 (Ship)**, then a **5 (Captain)**, then a **4 (Crew)**, in that order. They lock automatically.
- The two leftover dice are your **cargo**; their total is your score. Keep it or re-roll the cargo with any rolls left.
- No crew after three rolls = no score.
- A die that flies off the table costs the shooter $1, and that roll doesn't count. The odds are adjustable, and there's a button for real-life spills.
- High cargo wins the pot. Ties or no qualifiers carry the pot over to the next round.

Players, money and the pot are saved in your browser (`localStorage`).

## Publish on GitHub Pages

1. Merge this branch into `main`.
2. In the repo go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. The game will be live at `https://<your-username>.github.io/Dices/` in a minute or two.

To try it locally, just open `index.html` in a browser.
