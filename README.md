# Metehan İzal

I build payment and DeFi infrastructure, mostly around USDC and mostly for people who never wanted to touch crypto in the first place.

Two things I keep coming back to: letting someone pay with the card already in their pocket, and making an autonomous agent handle money without being able to run off with it.

### Troia

Cross-border settlement for Turkish cardholders. A shopper pays in lira with an ordinary Troy card, the merchant receives USDC, and nobody in the flow holds a wallet or learns what a seed phrase is.

It has been rebuilt three times as the ground moved:

| | chain | state |
|---|---|---|
| [Troia](https://github.com/Foreveranka/Troia) | Stellar | current, [docs](https://troia-docs.vercel.app) |
| [troia-arc](https://github.com/Foreveranka/troia-arc) | Arc | Arc mainnet went down in July 2026 |
| Troia-Monad-First | Monad | the first version |

### [Helm](https://github.com/Foreveranka/helm-arc)

A marketplace for agent-managed USDC vaults on Arc. Anyone launches a fund, an autonomous agent runs the strategy, and the contract gives that agent no way to send money to an arbitrary address. Investors hold an ERC-4626 share token that tracks real profit and loss.

The founder uploads the bot they say they run, the browser hashes it, and the vault seals that hash on chain, so a quiet swap later shows up as a version bump. Live on Arc testnet: [helm-arc.vercel.app](https://helm-arc.vercel.app)

### dotcombubble

A bonding-curve launchpad, currently on Stellar. Tokens graduate into a real pool with structurally locked liquidity. Private for now.

### Also here

[Haven](https://github.com/Foreveranka/Haven), an earlier real estate NFT auction on Ethereum.

---

Solidity, Rust and Soroban, TypeScript. Foundry for testing, and a habit of writing the attack before writing the fix.
