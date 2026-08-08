# Publish updates for premium-launcher-portfolio

```powershell
gh auth login
cd "C:\Users\KOKA\Desktop\Github Design\portfolios\premium-launcher"
git add -A
git commit -m "Polish portfolio README and recruiter framing"
git remote remove origin 2>$null
git remote add origin https://github.com/erayakbayy/premium-launcher-portfolio.git
git push -u origin HEAD:main

gh repo edit erayakbayy/premium-launcher-portfolio `
  --description "Commercial Windows Minecraft launcher — profiles, Skin Studio, mod health, secure updates. Docs & media only." `
  --homepage "https://github.com/erayakbayy/premium-launcher-updates/releases" `
  --add-topic minecraft --add-topic launcher --add-topic windows --add-topic desktop-app --add-topic python --add-topic portfolio --add-topic product
```

Do **not** push the private `Premium Launcher` source tree.
