---
description: >-
  This section is explaining how to register the domain on the EDNS chain(s) to
  map to the Web 2.0 URL, such as company website or personal website.
---

# Map Web 2.0 Domain to EDNS

### Available Function

[SetReverseDomain](setreversedomain.md)



### Example

To set a reverse domain which can access from EDNS to Web 2.0 URL

```
const RPC_ENDPOINT = 'https://polygon-rpc.com/';
const provider = new ethers.providers.JsonRpcProvider(RPC_ENDPOINT);
//Any Provider or ethers.Signer
const walletWithProvider = new ethers.Wallet(process.env.privateKey, provider);
const transaction = await SetReverseDomain("setter.meta",walletWithProvider)
```

