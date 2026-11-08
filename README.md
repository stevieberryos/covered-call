# Covered Call Calculator (iPhone web app)

A one-screen calculator: enter your cost, price, IV, days to expiry and minimum monthly premium, and it tells you which call strike to sell (strike + premium ≥ your cost) or the price to wait for. Works offline once installed.

## Put it on GitHub Pages (about 5 minutes, all from your phone)

1. Sign in at github.com and tap **+ → New repository**. Name it `covered-call`, set it to **Public**, tap **Create repository**.
2. On the new repo page tap **uploading an existing file**. Unzip the package in the Files app, then select all 7 files (no folders) and upload them.
3. Tap **Commit changes**.
4. Go to **Settings → Pages**. Under *Branch*, pick `main` and `/ (root)`, tap **Save**.
5. Wait about a minute. Your app is at `https://YOUR-USERNAME.github.io/covered-call/`.

## Install on your iPhone

1. Open that link in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Open it from the new icon. It runs full-screen and works without signal.

Your inputs are saved per ticker on the phone.

## Updating later

Replace `index.html` in the repo, then change `cc-v1` to `cc-v2` in `sw.js` so phones pick up the new version. Close and reopen the app twice.

Note: a public repo means anyone with the link can open the calculator. It contains no personal data; your numbers stay on your phone.

Black-Scholes estimates only. Not financial advice.
