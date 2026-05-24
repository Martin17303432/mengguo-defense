# Cute Fruit Defense

**Cute Fruit Defense** is a lightweight browser game where you protect a cozy orchard by matching fruit on a 6x6 board. Swap fruit, trigger match-3 combos, charge attacks, and stop cute little enemies before they reach your orchard base.

The game is built as a single static web page, so it can be hosted easily on GitHub Pages and played on desktop or mobile browsers.

## Play Online

If this project is published with GitHub Pages, the game link will look like this:

```text
https://your-github-username.github.io/your-repository-name/
```

For this repository, the expected URL is:

```text
https://martin17303432.github.io/mengguo-defense/
```

If the game does not work inside WeChat or another in-app browser, open the link with Safari, Chrome, Edge, or your phone's default browser.

## Gameplay

- Swap two adjacent fruit tiles on the 6x6 board.
- Match 3 or more identical fruit in a row or column to clear them.
- Clearing fruit attacks the enemies moving toward the orchard.
- Stop enemies before they reach the orchard base.
- Complete each level to earn coins and unlock progress.
- Use coins to upgrade your orchard and abilities.

## Fruit Effects

- Strawberry: basic attack
- Orange: area explosion
- Watermelon: high damage
- Blueberry: slows enemies
- Banana: grants bonus coins

## Items

- Bomb Fruit: clears a large area of the board and damages all enemies.
- Frozen Juice: freezes all enemies for 3 seconds.
- Sunshine Candy: instantly grants coins and energy.

## Features

- 6x6 match-3 board
- Chain reactions and score popups
- Enemy waves moving from right to left
- 10 levels with increasing difficulty
- Boss level
- Coins, upgrades, and limited-use items
- Local save data with `localStorage`
- Responsive layout for desktop and mobile
- No backend required

## Local Play

You can play the game by opening:

```text
index.html
```

If your browser blocks local files, start the local preview server:

```powershell
node server.mjs
```

Then open:

```text
http://127.0.0.1:4188/index.html
```

## Project Files

- `index.html`: the complete game, including HTML, CSS, and JavaScript.
- `server.mjs`: optional local preview server. It is not required for GitHub Pages.
- `README.md`: project description and usage notes.

## Save Data

The game stores progress in the browser with `localStorage`, including:

- highest unlocked level
- coins
- upgrade levels
- item counts
- high score

Clearing browser site data will reset the save.

## Deployment With GitHub Pages

1. Upload `index.html` and `README.md` to your GitHub repository.
2. Open the repository settings.
3. Go to **Pages**.
4. Set **Source** to `Deploy from a branch`.
5. Select branch `main` and folder `/ root`.
6. Save the settings.

After GitHub finishes deploying, share the GitHub Pages URL with friends.
