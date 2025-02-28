Crypto Collectibles Series -
[Cats](https://github.com/cryptocopycats/contracts) ·
[Punks](https://github.com/cryptopunksnotdead/contracts)


# CryptoPunks Blockchain Contracts / Services

_Code on the Blockchain - Electronic Contract Scripts_


## Original V2

### /punks - CryptoPunksMarket

Etherscan

- CryptoPunkMarket, see contract address [`0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb`](https://etherscan.io/address/0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb#code), June 22, 2017 07:40:00 PM (Block #3914495)


For more see [**Inside the CryptoPunksMarket Blockchain Contract / Service »**](punks)


### /wrapped - Wrapped Punks (WPUNKS)

Etherscan

- WrappedPunk (WPUNKS), see contract address [`0xb7f7f6c52f2e2fdb1963eab30438024864c313f6`](https://etherscan.io/address/0xb7f7f6c52f2e2fdb1963eab30438024864c313f6#code), September 8, 2020 03:11:25 PM (Block #10821737)


For more see [**Inside the Wrapped Punk (WPUNKS) Blockchain Contract / Service »**](wrapped)



## Classic V1  - "First Deploy"

> When CryptoPunks launched, the contract was exploitable.
> Sellers didn't get paid. LarvaLabs quickly launched a fixed version
> of the contract, which everyone uses.
>
> But the V1 tokens are still out there.

<!--
https://twitter.com/seeker_curious/status/1375112685746941955
https://twitter.com/seeker_curious/status/1374605517444706306
-->

### /punks-v1 - CryptoPunks

Etherscan

- CryptoPunks, see contract address [`0x6Ba6f2207e343923BA692e5Cae646Fb0F566DB8D`](https://etherscan.io/address/0x6Ba6f2207e343923BA692e5Cae646Fb0F566DB8D#code), June 9, 2017 12:22:50 AM (Block #3842489)


### /wrapped-v1 - Wrapped Punks V1 (WPUNKS1)

Etherscan

- PunksV1Wrapper (WPUNKS1), see contract address [`0xf4a4644e818c2843ba0aabea93af6c80b5984114`](https://etherscan.io/address/0xf4a4644e818c2843ba0aabea93af6c80b5984114#code), March 25, 2021 04:26:43 AM (Block #12105923)





## More

### /phunks - CryptoPhunks (PHUNKS)

Etherscan

- CryptoPhunks (PHUNKS), see contract address [`0xa82f3a61f002f83eba7d184c50bb2a8b359ca1ce`](https://etherscan.io/address/0xa82f3a61f002f83eba7d184c50bb2a8b359ca1ce#code), June 14, 2021 04:18:53 AM (Block #12630376)

- CryptoPhunksV2 (PHUNKS), see contract address [`0xf07468ead8cf26c752c676e43c814fee9c8cf402`](https://etherscan.io/address/0xf07468ead8cf26c752c676e43c814fee9c8cf402#code), June 21, 2021 12:07:08 AM (Block #12674389)



### /hdpunks - HD Punks (HDPUNKS)

Etherscan

- HDPunks (HDPUNKS), see contract address [`0x3e86e26915403ae0e1cff7e7b23377b3a30104a0`](https://etherscan.io/address/0x3e86e26915403ae0e1cff7e7b23377b3a30104a0#code), June 29, 2021 09:52:03 PM (Block #12731429)





### /zunks -  Zunks (ZUNK)

web: [cryptozunks.com](https://www.cryptozunks.com)

> CryptoPunks were the first 10,000. CryptoZunks are the last 10,000.
>
> Numbered 10,000 - 19,999, Zunks are the first Punks to be
> generated on-chain with randomized attributes.
> Spin to mint your base model Zunk and re-roll any attributes.
>
>
>  How does on-chain generation for Zunks work? How do we keep Zunks unique from existing Punks?
>
> 1) CryptoZunks is the first on-chain Punks derivative project where the smart contract generates all the attributes randomly on-chain when the user mints. How does this work?
>
> 2) After determining what attributes the Zunk has, we create a string representation of the Zunk which can be decoded into the various attributes (gender, hat, beard, etc.).
>
> 3) This string representation of the Zunk is then saved on the blockchain. On subsequent Zunk mints, the contract validates that it hasn't generated a same Zunk that already exists. If it has, the contract will re-generate random attributes until it has created a unique Zunk.
>
> 4) There are optimizations built into the contract to re-generate a Zunk as few times as possible. It's important that users aren't stuck endlessly generating invalid Zunks and to keep gas usage low.
>
> 5) We've run thousands of simulations and have validated that we can reliably generate 10k unique Zunks Partying face
>
> 6) We also wanted to guarantee that the generated Zunk doesn't match an existing Punk. We took all 10k Punks, converted them into our string representation, and seeded the contract with these Punks so that the contract may validate against them.
>
> 7) Now when the contract generates a Zunk or a user rerolls an attribute, the contract will validate that it does not match any existing Zunks or Punks. After the Zunk is confirmed to be unique and minted, the contract emits an event of the string representation of the Zunk.
>
> 8) Our goal is to innovate and to bring a unique and fun minting experience that gives some power to the user, while still upholding the ethos of decentralization. Every Zunk is randomly generated on chain, your Zunk's destiny is in your hands!
>
> -- [Amanda](https://twitter.com/0xMandy/status/1423678586494410754)
>
>
> All 10,000 Zunks have been minted!
> A lot of dizziness from all of the spins today.
>
> -- [CryptoZunks](https://twitter.com/CryptoZunks/status/1424165997733289992), Aug 8, 2021
>
>
> Commentary:
> The devs are raking in at least $1.35 million dollars
> with the mint of 10,000 Zunks
> and will of course profit a
> substantial amount of all future sales.


Etherscan

- CryptoZunks (ZUNK), see contract address [`0x031920cc2d9f5c10b444fd44009cd64f829e7be2`](https://etherscan.io/address/0x031920cc2d9f5c10b444fd44009cd64f829e7be2#code), August 7, 2021 04:01:17 AM (Block #12975638)


