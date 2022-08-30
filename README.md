# @edns/sdk

## Lookup Record

```
import {LookupAddress, LookUpText, TextType} from "@edns/sdk";

const domain = "apexlegend.404"

const cryptocurrencies = "ETH"
const address = await LookupAddress(domain,cryptocurrencies)
const description = await LookUpText(domain,TextType.DESCRIPTION)
```

## Lookup Reverse Domain

```
import {LookupDomainFromAddress} from "@edns/sdk";
const address = "0xCD58F85e6Ec23733143599Fe0f982fC1d3f6C12c"
const domain = await LookupDomainFromAddress(address);
```

## Set Reverse Domain

```
const RPC_ENDPOINT = 'https://polygon-rpc.com/';
const provider = new ethers.providers.JsonRpcProvider(RPC_ENDPOINT);
//Any Provider or ethers.Signer
const walletWithProvider = new ethers.Wallet(process.env.privateKey, provider);
const transaction = await SetReverseDomain("setter.meta",walletWithProvider)
```

<details>

<summary>TextTypes</summary>

```
enum TextType {
    EMAIL = 'email',
    URL = 'url',
    AVATAR = 'avatar',    
    DESCRIPTION = 'description',    
    NOTICE = 'notice',    
    KEYWORDS = 'keywords',    
    DISCORD = 'discord',    
    GITHUB = 'github',    
    REDDIT = 'reddit',    
    TWITTER = 'twitter',    
    TELEGRAM = 'telegram',    
    DELEGATE = 'delegate',
}
```



</details>

<details>

<summary>Cryptocurrencies Types</summary>



* ABBC

<!---->

* ADA

<!---->

* AE

<!---->

* AIB

<!---->

* AION

<!---->

* ALGO

<!---->

* AR

<!---->

* ARB1

<!---->

* ARDR

<!---->

* ARK

<!---->

* ATOM

<!---->

* AVAX

<!---->

* BCD

<!---->

* BCH

<!---->

* BCN

<!---->

* BDX

<!---->

* BNB

<!---->

* BPS

<!---->

* BSC

<!---->

* BSV

<!---->

* BTC

<!---->

* BTG

<!---->

* BTM

<!---->

* BTS

<!---->

* CCA

<!---->

* CCXX

<!---->

* CELO

<!---->

* CKB

<!---->

* CLO

<!---->

* DASH

<!---->

* DCR

<!---->

* DGB

<!---->

* DIVI

<!---->

* DOGE

<!---->

* DOT

<!---->

* EGLD

<!---->

* ELA

<!---->

* EOS

<!---->

* ETC

<!---->

* ETH

<!---->

* ETN

<!---->

* EWT

<!---->

* FIL

<!---->

* FIO

<!---->

* FIRO

<!---->

* FLOW

<!---->

* FTM

<!---->

* GO

<!---->

* GRIN

<!---->

* GRS

<!---->

* GXC

<!---->

* HBAR

<!---->

* HIVE

<!---->

* HNS

<!---->

* HNT

<!---->

* ICX

<!---->

* IOST

<!---->

* IOTA

<!---->

* IOTX

<!---->

* IRIS

<!---->

* KAVA

<!---->

* KMD

<!---->

* KSM

<!---->

* LCC

<!---->

* LRG

<!---->

* LSK

<!---->

* LTC

<!---->

* LUNA

<!---->

* MATIC

<!---->

* MONA

<!---->

* NANO

<!---->

* NAS

<!---->

* NEAR

<!---->

* NEM

<!---->

* NEO

<!---->

* NMC

<!---->

* NRG

<!---->

* NULS

<!---->

* ONE

<!---->

* ONT

<!---->

* OP

<!---->

* POA

<!---->

* PPC

<!---->

* QTUM

<!---->

* RDD

<!---->

* RSK

<!---->

* RUNE

<!---->

* RVN

<!---->

* SC

<!---->

* SERO

<!---->

* SOL

<!---->

* SRM

<!---->

* STEEM

<!---->

* STRAT

<!---->

* STX

<!---->

* SYS

<!---->

* TFUEL

<!---->

* THETA

<!---->

* TOMO

<!---->

* TRX

<!---->

* TT

<!---->

* VET

<!---->

* VIA

<!---->

* VLX

<!---->

* VSYS

<!---->

* WAN

<!---->

* WAVES

<!---->

* WICC

<!---->

* XCH

<!---->

* XDAI

<!---->

* XHV

<!---->

* XLM

<!---->

* XMR

<!---->

* XRP

<!---->

* XTZ

<!---->

* XVG

<!---->

* ZEC

<!---->

* ZEL

<!---->

* ZEN

<!---->

* ZIL

</details>
