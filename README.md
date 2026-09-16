# FAIRCROSS ($FAIRCROSS)

Sealed launch venue on Robinhood Chain: new meme tokens launch through five-minute sealed windows, every buyer crosses at one price.

Static site, no build. Open `index.html`.

## Settings
At the top of the first `<script>` at the bottom of `index.html`:

- `window.CONTRACT` — contract address
- `window.TWITTER` — X link
- `window.BUY_URL` — buy link (buttons stay inactive while empty)
- `window.WC_PROJECT_ID` — WalletConnect / Reown project id (cloud.reown.com); enables QR connect for Robinhood Wallet and phone wallets

## Wallet
Connect wallet (EIP-6963 + WalletConnect via `assets/wc.js`), Robinhood Chain 4663 is added automatically. Sealed orders are gasless `personal_sign` intents stored in the browser.
