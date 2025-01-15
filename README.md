# Bitcoin L1

Faster than lightning, programmable bitcoin.

- L1 Overview
  - [Testnet](https://subnets-test.avax.network/subnets/2mKPswfF36XrXZgk3tn9jjntXK3Yhk2SfDbkoBC1wB932Zyc1w)
- Block Explorers
  - [Testnet](https://testnet.bitcoinl1.net/)
- RPC URLs:
  - Testnet: `https://rpc.bitcoinl1.net/main/evm/132008` (chain id 132008)
- [Vavalon DEX](https://dex.vavalon.com)

## Fuji Testnet

### Fuji L1 Info

| Bitcoin L1 Fuji |                                                                                              |
| :-------------- | -------------------------------------------------------------------------------------------: |
| L1 Name         |                                                                                   Bitcoin L1 |
| L1 Logo         | <img src="https://cdn.blockviper.com/bitcoinl1/BTCL1-Logo-Word-Icon-DARK.png" width="25%" /> |
| L1 ID           |                                          `ie1wUBR2bQDPkGCRf2CBVzmP55eSiyJsFYqeGXnTYt2r33aKW` |
| VM ID           |                                          `kLPs8zGsTVZ28DhP1VefPCFbCgS7o5bDNez8JUxPVw9E6Ubbz` |
| Chain Name      |                                                                           Bitcoin L1 Testnet |
| Chain Logo      | <img src="https://cdn.blockviper.com/bitcoinl1/BTCL1-Logo-Word-Icon-DARK.png" width="25%" /> |
| Blockchain ID   |                                          `eNzydku7iCYZ4vG4uEGAQRsqDUy3R7myiJtGee54GKi6H1eHi` |
| Eth Chain ID    |                                                                                       132008 |
| RPC URL         |                                                  `https://rpc.bitcoinl1.net/main/evm/132008` |
| WS RPC URL      |                                                    `wss://wsock.bitcoinl1.net/ext/bc/BTC/ws` |
| Explorer URL    |                                                                https://testnet.bitcoinl1.net |
| Description     |                                                                                   Bitcoin L1 |
| Site            |                                                                        https://bitcoinl1.net |

### Fuji L1 ERC-20 Tokens

| Symbol |                                                                                                                         Address | Decimals |                              Logo                              |     Description |
| -----: | ------------------------------------------------------------------------------------------------------------------------------: | -------: | :------------------------------------------------------------: | --------------: |
|    BTC |                                                                                                                          NATIVE |       18 | ![BTC logo](https://cdn.blockviper.com/bitcoinl1/bitcoin.png)  |         Bitcoin |
|   wBTC | [`0xb693180ad3A4049eaB26453CCfF1b30517D2acd2`](https://testnet.snowscan.xyz/address/0xb693180ad3A4049eaB26453CCfF1b30517D2acd2) |       18 | ![wBTC logo](https://cdn.blockviper.com/bitcoinl1/bitcoin.png) | Wrapped Bitcoin |

### Bitcoin Token on Fuji

Bridged via ICM (formerly known as Teleporter)

|             Contract |                                                                                                                       Address |
| -------------------: | ----------------------------------------------------------------------------------------------------------------------------: |
| BTCb Fuji Mock ERC20 | [`0xb693180ad3A4049eaB26453CCfF1b30517D2acd2`](https://testnet.snowtrace.io/token/0xb693180ad3A4049eaB26453CCfF1b30517D2acd2) |

### Fuji Uniswap V2 Pairs

| Pair | Address |
| :--- | ------: |

### Fuji L1 Contracts

|                  Contract |                                                                                                                          Address |               Description |
| ------------------------: | -------------------------------------------------------------------------------------------------------------------------------: | ------------------------: |
|       TeleporterMessenger | [`0x253b2784c75e510dD0fF1da844684a1aC0aa5fcf`](https://testnet.bitcoinl1.net/address/0x253b2784c75e510dD0fF1da844684a1aC0aa5fcf) |       TeleporterMessenger |
|        TeleporterRegistry | [`0x6e0153CccEE18ADFfE4537A0D88EC3746C83825C`](https://testnet.bitcoinl1.net/address/0x6e0153CccEE18ADFfE4537A0D88EC3746C83825C) |       Teleporter Registry |
|         NativeTokenRemote | [`0xECe5Fa5d777322801163bEb40CdE02548eFEEFbd`](https://testnet.bitcoinl1.net/address/0xECe5Fa5d777322801163bEb40CdE02548eFEEFbd) |         NativeTokenRemote |
|           Balance Fetcher | [`0x7Ac0eb6e22D27A3eCe36c517E86E73551803C532`](https://testnet.bitcoinl1.net/address/0x7Ac0eb6e22D27A3eCe36c517E86E73551803C532) |           Balance Fetcher |
|               Multicall 3 | [`0x54AE1aA458E999f1d46b3c1e656356F5B587A0a0`](https://testnet.bitcoinl1.net/address/0x54AE1aA458E999f1d46b3c1e656356F5B587A0a0) |               Multicall 3 |
|               Multicall 2 | [`0xF0B202c9EfFE774483f73884acCFBB23874DB8a1`](https://testnet.bitcoinl1.net/address/0xF0B202c9EfFE774483f73884acCFBB23874DB8a1) |               Multicall 2 |
|                 Multicall | [`0xAea50D5b34c4210E13170f2AeEECA04748D80fb3`](https://testnet.bitcoinl1.net/address/0xAea50D5b34c4210E13170f2AeEECA04748D80fb3) |                 Multicall |
| UniswapInterfaceMulticall | [`0x704c6e74A3d38829D77Bc366B4494567e5D363f4`](https://testnet.bitcoinl1.net/address/0x704c6e74A3d38829D77Bc366B4494567e5D363f4) | UniswapInterfaceMulticall |
|         Uniswap v2 Router | [`0x37dcb5c7B05535FE23f10124734D2012C9006A6b`](https://testnet.bitcoinl1.net/address/0x37dcb5c7B05535FE23f10124734D2012C9006A6b) |            Vavalon Router |
|        Uniswap v2 Factory | [`0x33d8d3848E2e8b938373D93d01bB6D4d68Bcb5b3`](https://testnet.bitcoinl1.net/address/0x33d8d3848E2e8b938373D93d01bB6D4d68Bcb5b3) |           Vavalon Factory |

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
