# Deployed Bridge Addresses

Last verified: 2026-03-26
Applies to: `9197b09`
Networks: Sepolia (L1) ↔ Fluent testnet (L2)
Source of truth: `deployments/testnet/l1.json` + `deployments/testnet/l2.json`

Current deployment: **Sepolia (L1)** ↔ **Fluent testnet (L2)**.

Source: `deployments/testnet/l1.json`, `deployments/testnet/l2.json`.

---

## Sepolia (L1)

| Contract | Address |
|----------|---------|
| **NitroVerifier** | `0xB40f6f3Dd7ac010323E431928064bB8318bD0233` |
| **Rollup** (proxy) | `0x6473D94D54bEa36211560Bae7C5b3d4B292721a3` |
| Rollup (impl) | `0x61E21bd0163696d7D93d3BEE7B153FE1112e7Dbe` |
| **L1FluentBridge** (proxy) | `0x8B000ab0D2572E62377D6B6dEd7d4A5C9434E250` |
| L1FluentBridge (impl) | `0x72534145CcB1246356413bD6bdDC5C4E8bA9d6e6` |
| **ERC20TokenFactory** (proxy) | `0xF7ee76557bfDc3e019B401b043729D4602cD31CE` |
| ERC20TokenFactory (impl) | `0x276869cb03c1000719c247fF9478F3d7Dd927C98` |
| UpgradeableBeacon | `0x72DD7D37719f868b1d45A09f86c621563f9b6987` |
| ERC20PeggedToken (impl) | `0xFaf24dE9574e21f44c833ffaf5E799B96Cc34C2b` |
| **ERC20Gateway** (proxy) | `0x8D6849d1Fd008986EE78CeC5f8CeD8B971F291aC` |
| ERC20Gateway (impl) | `0xF286514354dBAd867600558D4f58611D479bf055` |
| **NativeGateway** (proxy) | `0x88C24633dfA2a8aEa501d0C9d771E4288ff601E7` |
| NativeGateway (impl) | `0x75Ca447C66f42b7945d2823c7880d55160DB6487` |
| MockERC20 (test token) | `0x2201126B50513A1C41d214c9e65A6f013E8054B8` |

- **Chain ID:** 11155111
- **RPC:** https://ethereum-sepolia-rpc.publicnode.com
- **Explorer:** https://sepolia.etherscan.io

---

## Fluent testnet (L2)

| Contract | Address |
|----------|---------|
| **L1BlockOracle** | `0x58B1cCEd2b3A326edFFc21A2eb2a5fB7BC3F54B9` |
| **L2FluentBridge** (proxy) | `0xE72C7eEA6B69998B9a34C4049c56D7D07bBEFB03` |
| L2FluentBridge (impl) | `0x93E656737dFbC3acD2E151CD857E288734439dD6` |
| **UniversalTokenFactory** (proxy) | `0x7e0FFe7D72BA981ec0C4ba607e508f723e0dCE98` |
| UniversalTokenFactory (impl) | `0x1e83891B6D2632DE6AF0AC58aac468099B8aef0A` |
| **ERC20Gateway** (proxy) | `0x1e6A15E8667D20faaA7552eb5D5816Cc9a68Da89` |
| ERC20Gateway (impl) | `0x032323291b40358AC04538856d3F2FC434670dCa` |
| **NativeGateway** (proxy) | `0xf72d447eca5D99019CDe18f976cfBF0a3cD126c0` |
| NativeGateway (impl) | `0xe2D8C8bd6B97Ae04658A8a0777E26DB264b20050` |
| Pegged token (precompile) | `0x0000000000000000000000000000000000520008` |

- **Chain ID:** 20994
- **RPC:** https://rpc.testnet.fluent.xyz/
- **Explorer:** https://testnet.fluentscan.xyz/

---

## JSON sources

- **L1:** `deployments/testnet/l1.json`
- **L2:** `deployments/testnet/l2.json`

---

## Governance (per chain)

| Contract | L1 Address | L2 Address |
|----------|-----------|-----------|
| Gnosis Safe | TBD | TBD |
| Normal Timelock (24h) | TBD | TBD |
| Emergency Timelock (1min) | TBD | TBD |
