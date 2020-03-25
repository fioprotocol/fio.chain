# FIO mainnet

This is the genesis file for the FIO Mainnet of https://github.com/fioprotocol/fio

## Genesis

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

## Chain ID
```
21dcae42c0182200e93f954a074011f9048a7624c6fe81d3c9541a614a88bd1c
```

## P2P endpoints

```
p2p-peer-address = 34.232.117.155:9876
p2p-peer-address = fio.eu.eosamsterdam.net:9956 # (bp@eosamsterdam)
p2p-peer-address = fio.eosdac.io:6876 # eosDAC (bp@thedac)
p2p-peer-address = fiopeer1.nodeone.io:6981 # NodeOne (fionodeonebp@nodeone)
p2p-peer-address = peer.fio.alohaeos.com:9876 # Aloha EOS (bp@alohaeos)
p2p-peer-address = peer1-fio.eosphere.io:9876
p2p-peer-address = fiomainnet.everstake.one:7770
p2p-peer-address = fio.eosrio.io:8122
p2p-peer-address = fio.acherontrading.com:9876
p2p-peer-address = fio.eos.barcelona:3876 # eosBarcelona (bp@eosbarcelona)
p2p-peer-address = p2p.fio.eosdetroit.io:1337 # EOS Detroit (eosio@detroit)
p2p-peer-address = p2p.fio.zenblocks.io:9866 # ZenBlocks
p2p-peer-address = fio.blockpane.com:9876 # Blockpane (not a producer)
p2p-peer-address = fio.greymass.com:49876 # Greymass (bp@greymass)
p2p-peer-address = fio.eosusa.news:9886 # EOSUSA (bp@eosusa)
p2p-peer-address = p2p.fioprotocol.io:3856  # Foundation for Interwallet Operability
p2p-peer-address = p2p.fio.eosargentina.io:1984 # EOS Argentina (fio@eosargentina)
```

## API endpoints

### History v1

```
http://34.232.117.155:8888
http://api.fio.eosdetroit.io
https://fio.greymass.com
```

### Hyperion

```
TBD
```

### EOSIO API

```
https://fio.eu.eosamsterdam.net
https://fio.eosdac.io
http://fioapi.nodeone.io:6881
https://fio.eosphere.io
https://fio.eosrio.io
https://fio.acherontrading.com
https://fio.eos.barcelona
https://api.fio.eosdetroit.io
https://fio.zenblocks.io
https://api.fio.alohaeos.com
https://fio.greymass.com
https://fio.eosusa.news
https://fio.eosargentina.io
```
