# Digital Marketing Certificate Site

## Run Locally
Double-click `start.bat` or run in PowerShell:
```powershell
.\serve.ps1
```
Then open [http://localhost:8080](http://localhost:8080) in your browser.

## Deploy to Vercel
Static site (no build step). Deploy to Vercel:
1. Push this folder to GitHub, import in Vercel (Framework: Other, no build command), or run `vercel` here.
2. `vercel.json` serves the `public/` folder.

Tuning name/date position on the certificate: see the `drawFit(...)` calls in `public/index.html`.

