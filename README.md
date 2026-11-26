# Rare Air — free website

Everything runs in the browser: no server, no API key, no monthly cost.

- `index.html`: the game
- `answers.js`: the ranked answer list for each prompt (most common first, rarest last)

## Put it online for free with GitHub Pages (about 10 minutes)

1. Go to github.com and sign up for a free account. Try the username **rareair**. If it's free,
   your site address will be **https://rareair.github.io**. If it's taken, the address is
   `https://YOURNAME.github.io/rareair`.
2. Click **+ → New repository**.
   - With the `rareair` username: name the repository `rareair.github.io`.
   - With any other username: name it `rareair`.
   Make it Public and click Create.
3. On the new repository page click **uploading an existing file**. Drag in `index.html`,
   `answers.js` and this README, then click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, choose **main** and **/ (root)**, and click Save.
5. Wait 1–2 minutes, refresh that page, and your link appears at the top. Done.

To update the game later, upload the changed file to the repository again. The site refreshes by itself.

## Editing prompts and answers
Open `answers.js`. Each prompt has a list of answers. Put common answers near the start
and rare ones near the end; position sets the score. Put alternate spellings in one entry
separated by `|`, like `"t. rex|tyrannosaurus"`. To add a prompt, add a new line in the same format.
