# FIO *Net

This repository contains various items pertaining to the FIO blockchain, its configuration, the location of historical and runtime state information, and api endpoints.

While this README contains a summary of most of that data, i.e. p2p endpoint data, individual files for that data are also version controlled and will be the most of date. For instance, see bp_data/mainnet_endpoints.json.

## Chain ID
```
21dcae42c0182200e93f954a074011f9048a7624c6fe81d3c9541a614a88bd1c
```
The chain id of the FIO blockchain may be validated using the get_info api call, specifically https://fio.blockpane.com/v1/chain/get_info.

## Genesis

This is the genesis file for the FIO Mainnet of https://github.com/fioprotocol/fio

```
{
  "initial_timestamp": "2020-03-25T00:00:00.000",
  "initial_key": "FIO7PptcpF7ai1LDgT9CvxukZ7nzM5cdeFVVDdTZeSNZLdcjYxUdk",
  "initial_configuration": {
    "max_block_net_usage": 1048576,
    "target_block_net_usage_pct": 1000,
    "max_transaction_net_usage": 524288,
    "base_per_transaction_net_usage": 12,
    "net_usage_leeway": 500,
    "context_free_discount_net_usage_num": 20,
    "context_free_discount_net_usage_den": 100,
    "max_block_cpu_usage": 200000,
    "target_block_cpu_usage_pct": 2000,
    "max_transaction_cpu_usage": 150000,
    "min_transaction_cpu_usage": 100,
    "max_transaction_lifetime": 3600,
    "deferred_trx_expiration_window": 600,
    "max_transaction_delay": 3888000,
    "max_inline_action_size": 4096,
    "max_inline_action_depth": 4,
    "max_authority_depth": 6,
    "max_ram_size": 34359738368
  }
}
```

## Snapshots

```
https://snapshots.eosphere.io
https://fio.snapshots.eossweden.org
https://snap.blockpane.com
```

## Endpoints
### MainNet
#### P2P
```
p2p-peer-address = fio.eu.eosamsterdam.net:9956           # EOS Amsterdam (bp@eosamsterdam)
p2p-peer-address = fio.eosdac.io:6876                     # eosDAC (bp@thedac)
p2p-peer-address = peer-fio.nodeone.network:9874          # NodeOne (fionodeonebp@nodeone)
p2p-peer-address = peer.fio.alohaeos.com:9876             # Aloha EOS (bp@alohaeos)
p2p-peer-address = peer1-fio.eosphere.io:9876             # EOSphere (bp@eosphere)
p2p-peer-address = peer2-fio.eosphere.io:9877             # EOSphere (bp@eosphere)
p2p-peer-address = fio.eosrio.io:8122                     # EOS Rio (br@eosrio)
p2p-peer-address = fio.acherontrading.com:9876            # Acheron Trading (bp@acherontrading)
p2p-peer-address = fiop2p.eos.barcelona:3876              # eosBarcelona (bp@eosbarcelona)
p2p-peer-address = p2p.fio.detroitledger.tech:1337        # Detroit Ledger Technologies/EOS Detroit (eosio@detroit)
p2p-peer-address = p2p.fio.zenblocks.io:9866              # ZenBlocks (bp@zenblocks)
p2p-peer-address = p2p.blockpane.com:9876                 # Blockpane (bp@blockpane)
p2p-peer-address = p2p.fio.genereos.io:9876               # GenerEOS (bp@genereos)
p2p-peer-address = fio.greymass.com:49876                 # Team Greymass (bp@greymass)
p2p-peer-address = fio.eosusa.news:9886                   # EOSUSA (bp@eosusa)
p2p-peer-address = p2p.fioprotocol.io:3856                # Foundation for Interwallet Operability
p2p-peer-address = p2p.fio.eosargentina.io:1984           # EOS Argentina (fio@eosargentina)
p2p-peer-address = fio.cryptolions.io:7987                # CryptoLions (bp@cryptolions)
p2p-peer-address = peer.fio-mainnet.eosblocksmith.io:5090 # Blocksmith (blocksmith@blocksmith)
p2p-peer-address = p2p.fio.services:9876                  # Gandalf (gandalf@grey)
p2p-peer-address = peer.fio.currencyhub.io:9876           # CurrencyHub (bp@thecurrencyhub)
p2p-peer-address = fiop2p.eoscannon.io:6789               # EOSCannon (bp@eoscannon)
p2p-peer-address = fio.eosdublin.io:9976                  # eosDublin (bp@eosdublin)
p2p-peer-address = fio.guarda.co:9976                     # Guarda Wallet (bp@guardaw)
p2p-peer-address = p2p.fiosweden.org:9376                 # sw/eden (bp@fiosweden)
p2p-peer-address = p2p1.fio.greeneosio.com:9876           # GreenEOSIO (bp@greeneosio)
p2p-peer-address = fiop2p.ledgerwise.io:25877             # Ledgerwise (bp@ledgerwise)
p2p-peer-address = fio-bp.dmail.co:7676                   # dmail.co (bp@dmaildotco)
```

#### API
```
https://fio.blockpane.com
https://fio.eu.eosamsterdam.net
https://fio.eosdac.io
https://api-fio.nodeone.network:8344
https://fio.eosphere.io
https://fio.eosrio.io
https://fio.acherontrading.com
https://fio.eos.barcelona
https://api.fio.detroitledger.tech
https://api.fio.alohaeos.com
https://fio.greymass.com
https://fio.genereos.io
https://fio.eosusa.io
https://fio.eosargentina.io
https://fio.cryptolions.io
https://fio-mainnet.eosblocksmith.io
https://api.fio.currencyhub.io
https://fio.eosdublin.io
https://api.fiosweden.org
https://api.fio.greeneosio.com
https://api.fio.services
https://fio.eostribe.io
https://fio-bp.dmail.co
https://api.fio.blocksindia.com 
```

#### History - v1
```
https://api.fio.detroitledger.tech
https://fio.greymass.com
https://fio.eosphere.io
https://api.fiosweden.org
https://fio.eosphere.io
https://fio.blockpane.com
```

#### History - Hyperion/v2
```
https://hyperion.fio.detroitledger.tech
https://api.fiosweden.org
https://fio.eosphere.io
https://fio.cryptolions.io
```

### TestNet
#### P2P
```
p2p-peer-address = peer.fiotest.alohaeos.com:9876 # Aloha EOS (alohaeos@fiotestnet)
p2p-peer-address = fio-testnet.eosphere.io:9876
p2p-peer-address = p2p.blockpane.com:3856
p2p-peer-address = testnet.fio.eosdetroit.io:1337
p2p-peer-address = testnet.fioprotocol.io:1987
p2p-peer-address = fiotestnet.everstake.one:7770
```

#### API
```
https://fiotestnet.blockpane.com
https://fiotestnet.greymass.com
https://test.fio.eosusa.io
https://api.fiotest.alohaeos.com
https://api.fiotest.currencyhub.io
https://testnet.fioprotocol.io
https://api.testnet.fiosweden.org
https://fio-test.eos.barcelona
https://fiotestnet.ledgerwise.io
https://fio-testnet.eosblocksmith.io
https://fio-bp.dmail.co:7777
```
