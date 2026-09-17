# How to push this as your GitHub profile README

GitHub shows a special README on your profile page if you have a **public repo named exactly the same as your username**.

## Steps

1. On GitHub, click **New repository**.
2. Name it exactly: `RishabhJain027`
3. Make it **Public**.
4. Don't add a README when creating it (you already have one here) — leave it empty.
5. Create the repo, then from this folder run:

```bash
cd RishabhJain027
git init
git add README.md
git commit -m "Add profile README"
git branch -M main
git remote add origin https://github.com/RishabhJain027/RishabhJain027.git
git push -u origin main
```

6. Go to `github.com/RishabhJain027` — your new README will appear at the top of your profile.

## Customizing

- Swap the GitHub stats theme (`tokyonight`) for another from [github-readme-stats themes](https://github.com/anuraghazra/github-readme-stats#themes) if you want a different look.
- Add pinned repos separately from your profile settings (Customize your pins) — those show below this README automatically.
- If you want a banner image instead of the typing SVG, drop an image into this folder and reference it with `![banner](./banner.png)` near the top of README.md.
