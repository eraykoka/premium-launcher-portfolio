# Publish to GitHub

This folder is a **local git repo** with an initial commit. It is not linked to GitHub yet (`gh` was not authenticated in the generator environment).

## Create public portfolio repo

```powershell
cd C:\Users\KOKA\Desktop\portfolio\premium-launcher
gh auth login
gh repo create premium-launcher-portfolio --public --source=. --remote=origin --push `
  --description "Portfolio showcase for Premium Launcher — docs & media only. Proprietary source not included."
```

## Important

- Do **not** push the private `Premium Launcher` source tree.
- Do **not** upload installers/EXEs that embed proprietary binaries into the portfolio repo.
- Replace AI mock gallery frames (`01-home.png` …) with real product screenshots when ready (same filenames).

## Suggested GitHub About blurb

> Commercial Windows Minecraft launcher — profile isolation, mod health, secure updates, studio-depth UI. Portfolio docs only; source is proprietary.
