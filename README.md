# FIO mainnet

This is the genesis file for the FIO Mainnet of https://github.com/fioprotocol/fio

## Genesis

```
{
  "initial_timestamp": "2020-03-24T00:00:00.000",
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
c3d82a6c50ce5887d4a86eec5e6043317b4a3043fdf27a502ab43438822e1e55
```

## P2P endpoints

```
p2p-peer-address = 34.232.117.155:9876
p2p-peer-address = fio.eu.eosamsterdam.net:9956
p2p-peer-address = fio.eosdac.io:6876
p2p-peer-address = fiopeer1.nodeone.io:6981
p2p-peer-address = peer.fio.alohaeos.com:9876
p2p-peer-address = peer1-fio.eosphere.io:9876
p2p-peer-address = fiomainnet.everstake.one:7770
p2p-peer-address = fio.eosrio.io:8122
```

## API endpoints

### History v1

```
http://34.232.117.155:8888
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
```
