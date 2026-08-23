<img width="1920" height="735" alt="logo-punchline" src="https://github.com/user-attachments/assets/a7f16152-9815-4e83-aa42-5c98dd58cd2e" />


# Ryft: Solana Shadow Trading Bot 🚀

<!-- DOWNLOAD_BUTTONS_START -->
[![Download for Mac](https://img.shields.io/badge/Download%20for%20Mac-DMG-blue?style=for-the-badge&logo=apple)](https://github.com/buy-hodl-chill/Ryft/releases/download/v1.3.2/Ryft_1.3.2_aarch64.dmg)

[![Download for Windows](https://img.shields.io/badge/Download%20for%20Windows-EXE-blue?style=for-the-badge&logo=windows)](https://github.com/buy-hodl-chill/Ryft/releases/download/v1.3.2/Ryft_1.3.2_x64-setup.exe)
<!-- DOWNLOAD_BUTTONS_END -->








Join the [Telegram](https://t.me/ryft_trader) for updates!

Gmgm degen. Welcome to Ryft: a local-first Solana shadow trading bot built for people who want to move fast, mirror smart wallets, and keep their setup clean while hunting for godcandles. 🕯️📈

Ryft watches a leader wallet, detects eligible Solana buy and sell activity, and mirrors those moves across your own configured shadow wallets. You bring the alphas, Ryft brings the execution cockpit.

*Does this mean I have to trade on my computer instead of my phone?*
No! Just trade in Phantom, Jupiter or directly on Ray, and Ryft will simply follow your moves with the configured additional wallets you own.

<img width="2009" height="569" alt="screenshots" src="https://github.com/user-attachments/assets/2d5a4c53-4a7c-4489-b3cd-39943c657582" />
<sup>(Bigger screenshots below)</sup>


## Why This Is Amazing ✨

Ryft turns wallet watching into a real trading workflow. Instead of copy-pasting addresses, juggling tabs, and panic-clicking through swaps, you get a focused desktop app that helps you coordinate multiple shadow wallets from one local dashboard.

- 🧠 **Follow the wallet with the alphas**  
  Configure one leader wallet and let Ryft watch for eligible buy and sell triggers.

- 🫧 **Keep the bubble maps clean**
  Small randomized intervals and a separate billing wallet prevent your wallets from getting connected<sup>*</sup>.

- 👥 **Mirror trades across shadow wallets**  
  Create or import shadow wallets, tune their buy percentages, set reserves, and choose which wallets participate.

- 🔐 **Local-first key management**  
  Private keys stay in the local Rust service and are encrypted with a passphrase-derived XChaCha20-Poly1305 flow. No random cloud dashboard holding your bags.

- ⚡ **Built for Solana speed**  
  Mainnet execution can use direct Raydium-backed swaps, Jupiter Ultra, Jupiter Swap v1, and RPC fallback depending on your settings.

- 🛡️ **Safety rails for less chaos**  
  Set max spend per shadow wallet, max projected total buy size, minimum SOL reserves, blocklisted mints, retry behavior, and automatic pause-on-error.

- 📊 **A dashboard that actually shows the mission**  
  Track bot status, leader wallet, effective RPC, enabled wallets, total shadow SOL, open positions, fees, logs, and latest activity from one place.

## What It Does 🧩

Ryft is a Solana copy-trading command center:

1. You pick a leader wallet, yours or a solid trader's.
2. Ryft watches that wallet for eligible swap-shaped buys and sells.
3. Enabled shadow wallets mirror those actions using your configured sizing and safety limits.
4. The app tracks orders, per-wallet results, positions, fees, logs, balances, and execution status locally.
5. You stay in control with arm, disarm, pause, resume, wallet export, wallet withdrawal, and settings management.

That means less frantic tab-hopping and more time doing the important degen work: finding alphas before the timeline notices. 🫡

## Main Features 🔥

- 🟣 Solana leader wallet monitoring
- 🟢 Mirrored buy and sell execution
- 👜 Shadow wallet creation, import, editing, withdrawal, and export
- 🧾 Local database for settings, wallets, orders, positions, logs, and fees
- 🛰️ Helius RPC and websocket support
- 🔁 Configurable retries and delay timing
- 💸 Prepaid billing wallet support for successful shadow buy fees
- 🚫 Mint blocklist for tokens you do not want mirrored
- 🌗 Light, dark, and system theme support
- 📣 Live activity toasts from the local service

## Why Degens Love It 💎🙌

Because speed matters. Clarity matters. Local control matters. When the market starts printing godcandles, the last thing you want is a messy setup where every move requires manual babysitting.

Ryft gives you:

- **More signal**: watch the wallet that matters (yours or someone else's).
- **More control**: tune each shadow wallet like its own strategy.
- **More confidence**: caps, reserves, blocklists, retries, and pause controls.
- **More privacy**: local app, local storage, encrypted keys.
- **More vibes**: gmgm energy with real infrastructure underneath.

## The cost? 💲

Ryft charges the small amount of 2% of shadow wallets that succesfully bought.
We get that trading on Solana could be ruthless, so we decided not to charge anything for selling.

## Disclaimer ⚠️

Ryft is powerful software for high-risk crypto activity. It does not guarantee profit, does not magically detect rugs, and does not turn bad alphas into good ones. Mainnet trades can lose money, fail, slip, or execute differently than expected. Start small, and know what you are signing.

Bring your own risk management. The app brings the cockpit. 🚀

<sup>*</sup> If wallets are already connected, make sure to load new wallets up with fresh funds to start clean. Bubble map bots could still link your shadow wallets theoretically due to the short periods of time, or exact same buy amounts. There's no way to fully prevent that, Ryft just helps you with the obvious things.

<img width="200" alt="logo" src="https://github.com/user-attachments/assets/ea16ba4d-ff92-40d1-ba85-065344b0c91d" />

## Troubleshooting

### MacOS

If macOS displays a security warning when opening Ryft, follow these steps:

1. Download and open the application.
2. If you see a message stating that Ryft is from an unidentified developer, close the dialog.
3. Open System Settings → Privacy & Security.
4. Scroll down to the Security section.
5. Click Open Anyway next to the Ryft warning.
6. Confirm by clicking Open.

You only need to do this once. Future launches will open normally.

---

### Windows

If Windows Defender SmartScreen displays a warning:

1. Launch Ryft.
2. When the "Windows protected your PC" message appears, click More info.
3. Verify that the application name is Ryft.
4. Click Run anyway.

You only need to do this once. Future launches will typically open without additional prompts.

## Screenshots

<img width="1005" height="2145" alt="screenshots-full@0 5x" src="https://github.com/user-attachments/assets/e327ded9-8646-48fd-9ad3-4a483aa57497" />
