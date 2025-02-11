# Bitcoin L1

Faster than lightning, programmable bitcoin.

- L1 Overview
  - [Testnet](https://subnets-test.avax.network/subnets/2YpN9N8PGmRfM4eiyCs5YBCKjPwRQxYBFDWW7yZ8PhPHAmiNH2)
- Block Explorers
  - [Testnet](https://testnet.bitcoinl1.net/)
- RPC URLs:
  - Testnet: `https://rpc.bitcoinl1.net/main/evm/132008` (chain id 132008)
- [Vavalon DEX](https://dex.vavalon.com)
- Faucet:
  - [BTC](https://build.bitcoinl1.net)

## Fuji Testnet

### Fuji L1 Info

| Bitcoin L1 Fuji |                                                                                              |
| :-------------- | -------------------------------------------------------------------------------------------: |
| L1 Name         |                                                                                   Bitcoin L1 |
| L1 Logo         | <img src="https://cdn.blockviper.com/bitcoinl1/BTCL1-Logo-Word-Icon-DARK.png" width="25%" /> |
| L1 ID           |                                         `2YpN9N8PGmRfM4eiyCs5YBCKjPwRQxYBFDWW7yZ8PhPHAmiNH2` |
| VM ID           |                                          `WFQQxaywkqeEoioDtaSqCM3C4PQkPVbCgbK8VseYGSK1j5VNP` |
| Chain Name      |                                                                           Bitcoin L1 Testnet |
| Chain Logo      | <img src="https://cdn.blockviper.com/bitcoinl1/BTCL1-Logo-Word-Icon-DARK.png" width="25%" /> |
| Blockchain ID   |                                         `21sMT9kcBoLjhKKN7qiNHMZqajubr7tb7uowAdXPfnBY6ihKFE` |
| Eth Chain ID    |                                                                                       132008 |
| RPC URL         |                                                  `https://rpc.bitcoinl1.net/main/evm/132008` |
| WS RPC URL      |      `wss://rpc1.bitcoinl1.net/ext/bc/21sMT9kcBoLjhKKN7qiNHMZqajubr7tb7uowAdXPfnBY6ihKFE/ws` |
| Explorer URL    |                                                                https://testnet.bitcoinl1.net |
| Description     |                                                                                   Bitcoin L1 |
| Site            |                                                                        https://bitcoinl1.net |

### Fuji L1 ERC-20 Tokens

| Symbol |                                                                                                                          Address | Decimals |                              Logo                              |     Description |
| -----: | -------------------------------------------------------------------------------------------------------------------------------: | -------: | :------------------------------------------------------------: | --------------: |
|    BTC |                                                                                                                           NATIVE |       18 | ![BTC logo](https://cdn.blockviper.com/bitcoinl1/bitcoin.png)  |         Bitcoin |
|   wBTC | [`0xde257b4C0c5C9AcF964B0605e6D6202EdCC33789`](https://testnet.bitcoinl1.net/address/0x21a352001166715294A54EDC637256Bc787B8a19) |       18 | ![wBTC logo](https://cdn.blockviper.com/bitcoinl1/bitcoin.png) | Wrapped Bitcoin |

### Bitcoin Token on Fuji

Bridged via ICM (formerly known as Teleporter)

|             Contract |                                                                                                                       Address |
| -------------------: | ----------------------------------------------------------------------------------------------------------------------------: |
| BTCb Fuji Mock ERC20 | [`0x6d3af0fb14c638df66fe97fa43130646c66da557`](https://testnet.snowtrace.io/token/0x6d3af0fb14c638df66fe97fa43130646c66da557) |

### Fuji Uniswap V2 Pairs

| Pair | Address |
| :--- | ------: |

### Fuji L1 Contracts

|                  Contract |                                                                                                                          Address |               Description |
| ------------------------: | -------------------------------------------------------------------------------------------------------------------------------: | ------------------------: |
|       TeleporterMessenger | [`0x253b2784c75e510dD0fF1da844684a1aC0aa5fcf`](https://testnet.bitcoinl1.net/address/0x253b2784c75e510dD0fF1da844684a1aC0aa5fcf) |       TeleporterMessenger |
|        TeleporterRegistry | [`0xde257b4C0c5C9AcF964B0605e6D6202EdCC33789`](https://testnet.bitcoinl1.net/address/0xde257b4C0c5C9AcF964B0605e6D6202EdCC33789) |       Teleporter Registry |
|         NativeTokenRemote | [`0x6F67Fe132079265FFe54A7474B2469DbF99cf3d8`](https://testnet.bitcoinl1.net/address/0x6F67Fe132079265FFe54A7474B2469DbF99cf3d8) |         NativeTokenRemote |
|           Balance Fetcher | [`0x3Ea2D2B253E850e0ab060c7BE95E6879D095e4CA`](https://testnet.bitcoinl1.net/address/0x3Ea2D2B253E850e0ab060c7BE95E6879D095e4CA) |           Balance Fetcher |
|               Multicall 3 | [`0x84E54e2B44eeA80e912A4Bc9c4f1E82699EDC044`](https://testnet.bitcoinl1.net/address/0x84E54e2B44eeA80e912A4Bc9c4f1E82699EDC044) |               Multicall 3 |
|               Multicall 2 | [`0xb0d2C62359015B57febAE280a99fCC40E1Cb7390`](https://testnet.bitcoinl1.net/address/0xb0d2C62359015B57febAE280a99fCC40E1Cb7390) |               Multicall 2 |
|                 Multicall | [`0x332644d50617ecB7f72b7CC5Bf51216E6bFAD0Bc`](https://testnet.bitcoinl1.net/address/0x332644d50617ecB7f72b7CC5Bf51216E6bFAD0Bc) |                 Multicall |
| UniswapInterfaceMulticall | [`0xB026eFA843D753bd7D6937355cE58d01c18D0682`](https://testnet.bitcoinl1.net/address/0xB026eFA843D753bd7D6937355cE58d01c18D0682) | UniswapInterfaceMulticall |
|         Uniswap v2 Router | [`0xe7dED06A2AFb574017b8fBe9C849329E9DA86852`](https://testnet.bitcoinl1.net/address/0xe7dED06A2AFb574017b8fBe9C849329E9DA86852) |            Vavalon Router |
|        Uniswap v2 Factory | [`0x7a88eD0640CAb21C9C6F97a1c71b280bA1883156`](https://testnet.bitcoinl1.net/address/0x7a88eD0640CAb21C9C6F97a1c71b280bA1883156) |           Vavalon Factory |
|                 BTCFaucet | [`0x302eB32d677642ea4E7c8AAbfA4FA846a02d1F98`](https://testnet.bitcoinl1.net/address/0x302eB32d677642ea4E7c8AAbfA4FA846a02d1F98) |                BTC Faucet |
|                 Forwarder | [`0xF9F784766Ea1DEcAef46350e075d52368b2B7625`](https://testnet.bitcoinl1.net/address/0xF9F784766Ea1DEcAef46350e075d52368b2B7625) |        EIP-2771 Forwarder |

## Run your own node

- Run an [Avalanche node](https://docs.avax.network/avalanche-l1s/avalanche-l1-nodes)
- Install [Avalanche CLI](https://github.com/ava-labs/avalanche-cli) on it
- Avalanche CLI Explorer [L1CLI.com](https://l1cli.com) (handy)

## Import and join an L1

#### Fuji:

- [Import the L1](https://docs.avax.network/tooling/guides/import-avalanche-l1) into Avalanche CLI
  - `avalanche blockchain import file ./l1s/bitcoinl1-testnet/export.json`
- [Join the L1](https://docs.avax.network/avalanche-l1s/deploy-a-avalanche-l1/fuji-testnet) with your node using Avalanche CLI
  - `avalanche blockchain join BitcoinL1`
- Reload AvalancheGo
  - `sudo systemctl restart avalanchego`
