---
title: Bridge to Near
icon: ":bridge_at_night:"
order: 1
---

# 🌉 Bridge to Near

<style>
  .badges > * {
    display: flex;
    gap: 0.5rem;
  }
</style>

There are many ways to bridge to Near, but all of them have their pros and cons.
This guide helps you understand which bridging solution is best suited to your needs.

-----

### From Solana via RocketX

:::badges
[!badge variant="success" text="Gas Topup: :white_check_mark:"]
[!badge variant="warning" text="ETA: 5min"]
[!badge variant="success" text="Fees: low (bridge & swap)"]
:::

- Directly convert your SOL from Solana to NEAR on Near via [RocketX](https://app.rocketx.exchange/swap/SOLANA.solana/NEAR.near/0.0061?from=Solana&to=NEAR%20Protocol&mode=w).

-----

### From Solana via TokenBridge

:::badges
[!badge variant="danger" text="Gas Topup: :no_entry:"]
[!badge variant="success" text="ETA: 15s"]
[!badge variant="warning" text="Fees: very low (bridge) & medium (swap)"]
:::

- Convert your SOL on Solana to SOL.w (Wormhole wrapped SOL) on Near via [TokenBridge](https://tokenbridge.app/).
- Swap SOL.w to NEAR via [Ref Finance](https://app.ref.finance/#22.contract.portalbridge.near|near)

-----

### From EVM via Ref Finance

:::badges
[!badge variant="danger" text="Gas Topup: :no_entry:"]
[!badge variant="success" text="ETA: 40s - 4min"]
[!badge variant="success" text="Fees: very low (bridge) & low (swap)"]
:::

- Send USDC via [Ref Finance bridge aggregator](https://app.ref.finance/bridge) to Near.
- Swap USDC to NEAR via [Ref Finance](https://app.ref.finance/#17208628f84f5d6ad33f0da3bbbeb27ffcb398eac501a31bd6ad2011e36133a1|near).

-----

### From EVM via Stargate Finance v1

:::badges
[!badge variant="success" text="Gas Topup: :white_check_mark:"]
[!badge variant="success" text="ETA: 40s - 4min"]
[!badge variant="success" text="Fees: very low (bridge) & low (swap)"]
:::

- Send USDC from various LayerZero compatible EVMs to Aurora via [Stargate Finance](https://stargate.finance/bridge).
- Swap USDC to wNEAR via [Trisolaris](https://trisolaris.io/).
- Send wNEAR from Aurora to Near via [Rainbow Bridge](https://rainbowbridge.app/).

-----

### From EVM via Stargate Finance v2

:::badges
[!badge variant="danger" text="Gas Topup: :no_entry:"]
[!badge variant="success" text="ETA: 40s - 4min"]
[!badge variant="success" text="Fees: very low (bridge) & low (swap)"]
:::

- Send USDC from various LayerZero compatible EVMs to Aurora via [Stargate Finance](https://stargate.finance/bridge).
- Send USDC from Aurora to Near via [Rainbow Bridge](https://rainbowbridge.app/).
- Swap USDC to NEAR via [Ref Finance](https://app.ref.finance/#17208628f84f5d6ad33f0da3bbbeb27ffcb398eac501a31bd6ad2011e36133a1|near).

-----

### From Ethereum via Rainbow Bridge

:::badges
[!badge variant="danger" text="Gas Topup: :no_entry:"]
[!badge variant="danger" text="ETA: 2min - 20min"]
[!badge variant="danger" text="Fees: high (bridge) & low (swap)"]
:::

- Send any ERC-20 or native ETH from Ethereum to Near via [Rainbow Bridge](https://rainbowbridge.app/).
- Swap your tokens to NEAR via [Ref Finance](https://app.ref.finance/#|near).
