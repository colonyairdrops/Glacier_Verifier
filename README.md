# Glacier_Verifier Node by @ColonyAirdrops

- Follow Video: [Youtube](https://youtu.be/xda46PXs82g)
- Official Docs: [Here](https://docs.glacier.io/getting-started/glacier-nodes/run-testnet-nodes)

# Step-by-Step Guide

## Hardware Requirement
![image](https://github.com/user-attachments/assets/527a56a4-99a7-48c0-8007-c336e3456db0)

1. Create New Wallet
2. Visit [Faucet](https://docs.bnbchain.org/bnb-smart-chain/developers/faucet/#claim-tbnb-from-online-faucet) and get some tBNB in new wallet
3. Visit [Bridge](https://opbnb-testnet-bridge.bnbchain.org/deposit) and bridge tBNB from BNB testnet to opBNB testnet
4. Copy private_key of node wallet (without 0x)

## Run A Node
```console
docker run -d -e PRIVATE_KEY=$YOUR_PRIVATE_KEY --name glacier-verifier docker.io/glaciernetwork/glacier-verifier:v0.0.2
```
Make sure to take faucet before running

## Check Logs
```console
docker logs -f glacier-verifier
```

## Check Status
The online status of the verifier nodes on the testnet can be checked here: https://testnet.nodes.glacier.io/status

- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops
