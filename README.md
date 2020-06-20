## Ethereum wallet using an [ERC-20](https://en.wikipedia.org/wiki/ERC-20) smart contract.

A digital wallet app, developed in dart language and flutter framework. The idea is to help developers to understand how to build dApps using blockchain and associated technologies. This app can transfer tokens from one wallet to another, through an [ERC-20](https://en.wikipedia.org/wiki/ERC-20) Ethereum contract.


### What's being used

- Built in [Flutter](https://flutter.dev/docs/get-started/install) framework
- [Google ML Vision](https://firebase.google.com/docs/ml-kit) for QRCode scan.
- [Web3Dart](https://github.com/simolus3/web3dart) to interact with Ethereum blockchain
- [Flutter hooks](https://github.com/rrousselGit/flutter_hooks) to manage widget life-cycle.

Wallet |  Send tokens | Processing 
:-----:|:------------:|:------------:|
![Your wallet](https://faucet.clempe.dev/images/your-wallet.jpg)  |  ![Your wallet](https://faucet.clempe.dev/images/transfer-address.jpg) | ![Your wallet](https://faucet.clempe.dev/images/transfer-processing.jpg)



### Getting started

How to watch/build autogenerated files 

```bash
$ flutter packages pub run build_runner build   # to build 
$ flutter packages pub run build_runner watch   # to watch 
```

How to run the app

```bash
$ flutter pub get packages
$ flutter packages pub run build_runner build
$ flutter run
```

How to run tests
```bash
$ flutter test
```

### Wallet balance

For those who don't want to play with smart contracts yet, you can claim some test coins (tokens) and ether using the following links or check out [this repo](https://github.com/allanclempe/ether-wallet-contract) to understand how to deploy your own contract.

***Transfer test TOKENS to your wallet:***

After setting up your wallet, you will need some tokens to play with. Use the link below to transfer some tokens to your wallet.

[https://faucet.clempe.dev](https://faucet.clempe.dev)


***Transfer test Ether to your wallet***

Also to process transactions on the network, you will also need ETH to pay transaction fees, called gas. You also can claim some using the link below.

[https://faucet.ropsten.be/](https://faucet.ropsten.be/)

just be patient, the transaction might take a while to be processed. 

### The smart contract

Feel free to check out the smart contract used in this project [https://github.com/allanclempe/ether-wallet-contract](https://github.com/allanclempe/ether-wallet-contract)

---
dart wallet cryto flutter eth smart contracts - by [Allan Clempe](https://twitter.com/aclempe)