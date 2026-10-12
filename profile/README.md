<p align="center">
  <a href="https://tryfolio.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/hero-dark.png">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/hero-light.png">
      <img alt="Folio. The world is your portfolio. Buy and sell tokenized US stocks with USDC on Solana. Built for the Solana Seeker." src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/hero-light.png" width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://tryfolio.io"><b>Try Folio</b></a>
  &nbsp;·&nbsp;
  <a href="https://tryfolio.io"><b>Get Folio for Android</b></a> <sub>(Solana dApp Store listing coming soon)</sub>
  &nbsp;·&nbsp;
  <a href="https://x.com/try_folio"><b>Follow @try_folio</b></a>
</p>

<p align="center">
  <img alt="Solana dApp Store: coming soon" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-solana-dapp-store.svg" title="Coming soon">
  <a href="https://solanamobile.com"><img alt="Solana Seeker" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-solana-seeker.svg"></a>
  <a href="https://tryfolio.io"><img alt="Android" src="https://img.shields.io/badge/Android-204C3B?logo=android&amp;logoColor=F7F8F4"></a>
</p>

<p align="center">
  <a href="https://tryfolio.io/chatgpt"><img alt="Use Folio in ChatGPT" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-chatgpt.svg"></a>
  <a href="https://solana.com"><img alt="Solana" src="https://img.shields.io/badge/Solana-204C3B?logo=solana&amp;logoColor=F7F8F4"></a>
  <a href="https://kotlinlang.org"><img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-204C3B?logo=kotlin&amp;logoColor=F7F8F4"></a>
</p>

<p align="center">
  <a href="https://docs.solanamobile.com"><img alt="Mobile Wallet Adapter" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-mobile-wallet-adapter.svg"></a>
  <a href="https://privy.io"><img alt="Privy" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-privy.svg"></a>
  <a href="https://www.circle.com/usdc"><img alt="USDC" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/badge-usdc.svg"></a>
</p>

<!-- demo-video: a demo thumbnail linking to the video goes here once the video exists -->

## What is Folio

**Folio is a brokerage for the world: buy and sell tokenized US stocks with USDC on Solana, from an Android app built for the Solana Seeker.**

- **Any amount, in dollars.** Type $50 and Folio works out the fraction of a share, from one USDC balance.
- **Powered by blockchain. Felt by no one.** Privy gives you a self-custodied wallet when you sign in. No wallet to set up, no gas to pay.
- **Every cost before you confirm.** The amount, the shares and every fee sit on one review screen.

## How it works

1. **Sign in.** Privy creates your embedded Solana wallet in the same step.
2. **Add USDC.** Deposit from a wallet on your phone, Seeker Wallet included, with the amount filled in.
3. **Buy in dollars.** Pick a stock, choose an amount, review the fees, confirm. Sell the same way.

**Season 0** is Folio's paper-trading contest: build a portfolio of tokenized US stocks with paper USDC and see how it stacks up against other players, with no real money at stake.

## Screens

<table>
  <tr>
    <td align="center" width="25%"><img alt="Folio portfolio screen" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/screen-portfolio.png" width="200"></td>
    <td align="center" width="25%"><img alt="Folio explore screen" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/screen-explore.png" width="200"></td>
    <td align="center" width="25%"><img alt="Folio buy review screen" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/screen-buy-review.png" width="200"></td>
    <td align="center" width="25%"><img alt="Folio deposit screen" src="https://raw.githubusercontent.com/ECS-Folio/.github/main/profile/assets/screen-deposit.png" width="200"></td>
  </tr>
  <tr>
    <td align="center"><b>Portfolio</b><br>Your total, every account and every holding on one screen.</td>
    <td align="center"><b>Explore</b><br>Find a US stock or ETF and see today's move at a glance.</td>
    <td align="center"><b>Review</b><br>Shares, fees and the total in dollars before you buy.</td>
    <td align="center"><b>Deposit</b><br>Add USDC from the wallets already on your phone.</td>
  </tr>
</table>

## Why Seeker

On a Solana Seeker, Folio talks to the phone's own wallet through Mobile Wallet Adapter. Seeker Genesis verification runs through the Seed Vault: you sign with the Seeker wallet, Folio shows your `.skr` name and sponsors your account setup. Deposits open Seeker Wallet, Phantom or Solflare with the amount filled in, and SKR trades in the same app as your stocks. Folio's fee payer co-signs every trade and covers network fees and rent; your wallet authorises every instruction.

## Built with

- **Kotlin and Jetpack Compose** for the native Android app
- **Solana Mobile Wallet Adapter** and the **Seed Vault** for Seeker signing
- **Privy** for sign-in and the embedded, self-custodied Solana wallet
- **USDC on Solana** as the cash balance
- **xStocks** tokenized stocks, priced across on-chain markets with **Jupiter** routing

Folio is a **Clock In** hackathon entrant.

## Milestones

| Date | Milestone |
| --- | --- |
| 2026-09-27 | First tagged Android build (0.2.4) |
| 2026-09-28 | Deposit from a wallet on the phone (Android 0.2.8) |
| 2026-10-02 | Cross-chain funding screens (Android 0.2.15) |
| 2026-10-03 | Home screen widgets for a single stock and the portfolio (Android 0.2.22) |
| 2026-10-05 | [tryfolio.io](https://tryfolio.io) blog opens with "Hello, world" |
| 2026-10-07 | Fifteen real-money transactions across every transfer direction, receipts exact to the unit |
| 2026-10-12 | Android 0.2.56 tagged |

## Repositories

| Repository | What it holds | Visibility |
| --- | --- | --- |
| [`stock-app`](https://github.com/ECS-Folio/stock-app) | Folio: the shipping app (Android, server, web, landing) | Private |
| `folio` | Folio: Solana consumer brokerage for tokenized equities (rebuild, Oct 2026) | Private |
| `folio-old` | Folio, Brokerage for the World: mobile-first consumer brokerage UI over tokenized equities on Solana | Private |
| [`.github`](https://github.com/ECS-Folio/.github) | This organization profile | Public |

## Trust

Stock positions on Folio are tokenized stocks issued by xStocks that track the price of the underlying share, and your holdings are self-custodied through Privy. Read the [disclosures](https://tryfolio.io/disclosures/) and [security](https://tryfolio.io/security/) pages. Investing involves risk, including loss of the money you invest.

---

<p align="center">
  <a href="https://tryfolio.io">tryfolio.io</a> &nbsp;·&nbsp; <a href="https://x.com/try_folio">@try_folio on X</a>
  <br>
  <sub>Folio is built by ECS Folio.</sub>
</p>
