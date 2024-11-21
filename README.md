# Glacier_Verifier Node by @ColonyAirdrops

Follow Video: 

# Step-by-Step Guide to Run Fizz Node

## Hardware Requirement
![image](https://github.com/user-attachments/assets/527a56a4-99a7-48c0-8007-c336e3456db0)

1. Create New Wallet or use the same wallet used to submit form
2. Visit [Faucet](https://www.bnbchain.org/en/testnet-faucet) and get some tBNB in new wallet
3. Visit [Bridge](https://opbnb-testnet-bridge.bnbchain.org/deposit) and bridge tBNB from BNB testnet to opBNB testnet
4. Copy private_key of node wallet (without 0x)

## Run A Node
```console
docker run -d -e PRIVATE_KEY=$YOUR_PRIVATE_KEY --name glacier-verifier docker.io/glaciernetwork/glacier-verifier:v0.0.1
```
Make sure to take faucet before running

## Check Status
The online status of the verifier nodes on the testnet can be checked here: https://testnet.nodes.glacier.io/status

- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops
