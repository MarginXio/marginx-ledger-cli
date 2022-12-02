# Ledger Usage example

## 1. import key from ledger
```shell
fxdexd keys add testKey --ledger --keyring-backend test --algo eth_secp256k1  --account 1
```

## 2. list all imported keys
```shell
fxdexd keys list --keyring-backend test
```

## 3. retrieve key by name
```shell
fxdexd keys show testKey --keyring-backend test
```