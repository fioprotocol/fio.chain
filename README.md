# FIO.Chain

This repository contains bootstrap information for FIO Chain.

# Mainnet

## Chain ID
```
21dcae42c0182200e93f954a074011f9048a7624c6fe81d3c9541a614a88bd1c
```

## Endpoints
### P2P
* [https://fio.antelope.tools/endpoints](https://fio.antelope.tools/endpoints) (verified + easy copy)
* [https://bpmonitor.fio.net/nodes?type=seed](https://bpmonitor.fio.net/nodes?type=seed)

### API
* [https://bpmonitor.fio.net/nodes](https://bpmonitor.fio.net/nodes) (Verified, scored and includes description of services, e.g. V1 History and Hyperion)
* [https://fio.antelope.tools/nodes](https://fio.antelope.tools/nodes) (Verified and includes description of services, e.g. V1 History and Hyperion)

# Testnet
## Chain ID
```
b20901380af44ef59c5918439a1f9a41d83669020319a80574b804a5f95cbd7e
```

## Endpoints
### P2P
* [https://fio-testnet.antelope.tools/endpoints](https://fio-testnet.antelope.tools/endpoints) (verified + easy copy)
* [https://bpmonitor.fio.net/nodes?chain=Testnet&type=seed](https://bpmonitor.fio.net/nodes?chain=Testnet&type=seed)

### API
* [https://bpmonitor.fio.net/nodes?chain=Testnet](https://bpmonitor.fio.net/nodes?chain=Testnet) (Verified, scored and includes description of services, e.g. V1 History and Hyperion)
* [https://fio-testnet.antelope.tools/nodes](https://fio-testnet.antelope.tools/nodes) (Verified and includes description of services, e.g. V1 History and Hyperion)

# Genesis
This is the genesis file for the FIO Mainnet.

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
