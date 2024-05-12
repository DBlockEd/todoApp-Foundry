# TodoApp with Foundry

This is a simple TodoApp built on Ethereum using Foundry. Users can create, mark completed/uncompleted, and delete tasks on the Ethereum blockchain.


### Build

```shell
$ forge build
```

### Deploy

```shell
$ forge create --rpc-url <your_rpc_url> --private-key <your_private_key> src/todo.sol:TodoApp
```
