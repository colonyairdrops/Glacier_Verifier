# Glacier Verifier Node v2
- Follow Video: [Youtube](https://youtu.be/xda46PXs82g)
- Official Docs: [Here](https://docs.glacier.io/getting-started/glacier-nodes/run-testnet-nodes)

- If you are just starting you can follow the previous guide

## Step-by-Step Guide
1. Stop & Remove Docker Container
```console
docker stop glacier-verifier 
```
```console
docker rm glacier-verifier 
```

2. Run A Node
```console
docker run -d -e PRIVATE_KEY=YOUR_PRIVATE_KEY --name glacier-verifier docker.io/glaciernetwork/glacier-verifier:v0.0.3
```
- Enter your node wallet private key

3. Check Logs
```console
docker logs -f glacier-verifier
```

4. Check Status
The online status of the verifier nodes on the testnet can be checked here: https://testnet.nodes.glacier.io/status
---

- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops
