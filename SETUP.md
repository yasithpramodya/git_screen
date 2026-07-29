# Setup Instructions (2 minutes)

## 1. Create your special profile repo
GitHub shows this README on your profile only if you create a repo with
**the exact same name as your username**.

- Go to https://github.com/new
- Repository name: `yasithpramodya` (your real GitHub username)
- Make it **Public**
- Check "Add a README file"
- Create it

## 2. Replace the README
Delete the auto-created README.md in that repo and upload the `README.md`
from this package instead. Then **find-and-replace `yasithpramodya`** with
your actual GitHub username everywhere in the file (also update the
LinkedIn/Twitter/email/Instagram links).

## 3. Add the snake workflow
In that same repo, create the file:
```
.github/workflows/snake.yml
```
and paste in the contents of `snake.yml` from this package.

## 4. Run it once
- Go to the repo's **Actions** tab
- Click "Generate Snake Animation" → **Run workflow**
- Wait ~30 seconds, it will create a branch called `output` with the SVGs

## 5. Done!
Go back to your profile page (github.com/yasithpramodya) — you'll see the
colorful header, typing animation, stats cards, trophies, and the animated
snake eating your contribution graph 🐍

## Optional tweaks
- Change `theme=radical` in the stats/streak/trophy URLs to any of:
  `dark`, `tokyonight`, `dracula`, `merko`, `gruvbox`, `onedark`, `cobalt`
- Change the `skillicons.dev` icon list to match your actual stack
- Change the cron schedule in `snake.yml` if you want the snake to refresh
  more/less often (it doesn't need to run often — contributions update daily)
