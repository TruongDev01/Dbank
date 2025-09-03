# Run Completed Code

1. Make sure dfx is running

```
dfx start --clean
```

2. Deploy the project
```
dfx deploy
```

3. Start NPM
```
npm start
```
This interface belongs to a dApp (decentralized application) called DSurv, running on blockchain. It is a demo project for testnet tokens (not yet an official commercial project).

Main components on the interface:

DSurv logo: The brand identity of the application.

Faucet

A place where users can claim free tokens (in this case, the DTruong - DANG token).

Each time you click "Gimme gimme", the system grants 10,000 DANG tokens to your address (Principal ID).

This is only for testing, so no real purchase is required.

Check Balance

Users enter their Principal ID (a blockchain account identifier).

Clicking Check Balance shows the number of tokens they own.

Transfer

Allows transferring tokens from your account to another.

Enter To Account and Amount, then click Transfer.

If the account does not have enough balance, the system displays “Insufficient Funds” (as shown in the image).

👉 In short:
This is a test project for faucet + token transfer in the blockchain ecosystem (most likely on the Internet Computer Protocol - ICP, since it uses “Principal ID”). It helps users experience how to claim tokens, check balances, and transfer tokens before launching officially on the mainnet.


