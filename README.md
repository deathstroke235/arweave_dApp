
# Arweave dApp
A decentralized Twitter:
where people can talk and create topic such as hashtags in twitter,where every user with arweave wallet can only be applicable for transaction on the page.
Message once posted cant be deleted because transaction is signed it can only be changed by creating another transaction.
dApp consists of home topic and users tab where home page shows all the transactions, topic is same as hashtags in twitter and users shows all the transactions done by the specific user.

## Documentation

[Arweave](https://arwiki.wiki/#/en/main)


Installing Arweave:

```bash
npm install --save arweave
```
```bash
import Arweave from 'arweave';
export const arweave = Arweave.init({});
```
## Deployment


```bash
  npm build
```

```bash
  npm install -g arkb
```

```bash
  arkb deploy ./build --wallet ~/arweave/testWallet/walletname.json
```