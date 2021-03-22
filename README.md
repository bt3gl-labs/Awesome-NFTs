# ▲ A comprehensive curated collection about NFTs ▼ 

<br>

#### TL;DR NFTs are cryptographic tokens that prove authenticity, ownership, and scarcity of digital assets. It's a new *file format*, for a file you can't copy.

<br>
<br>



<p align="center">
<img src="https://github.com/dream3rs/awesome_NFTs/blob/main/layers.png" width="80%" align="center" style="padding:1px;border:thin solid black;" />
</p>




<br><br>

*A Non-Fungible Token (NFT) is a cryptographically secured token existing on the blockchain representing ownership of something unique. NFTs can represent tokenized ownership claims to real-world assets like a specific piece of land, or actual ownership of digital assets as in a rare digital trading card. Unlike fungible tokens such as Bitcoin where one BTC can be exchanged for any other BTC, each NFT is completely unique and represents verifiable digital scarcity.*

<br>

### What is fungibility?

*Fungible goods are equivalent and interchangeable, like Ether, bitcoin, fiat currencies, and voting rights. Non-fungible goods are unique and distinct, like deeds of ownership, or collectibles.*

<br>

### What is a token?

*A token is a representation of something in the blockchain: money, time, services, shares in a company, anything. By representing things as tokens, we can allow smart contracts to interact with them, exchange them, create or destroy them.*

*A token contract is an Ethereum smart contract. "Sending tokens" means "calling a method on a smart contract that someone wrote and deployed". A token contract is a mapping of addresses to balances, plus some methods to add and subtract from those balances. It is these balances that represent the tokens themselves. Someone "has tokens" when their balance in the token contract is non-zero.*

<br>

### Why NFTs will power the future of commerce

* NFT-enabled decentralized commerce could offer a viable alternative and save small businesses.
* Non-fungibility itself allows for new kinds of transactions, where users are not limited to monetary exchanges, but can enjoy the exchange of assets (digital or physical).


<br>

# 🌮 🪙
---

# Blockchains 101



## How it works

* Whenever a node wishes to include a new transaction in the blockchain, it sends it to its peers, who then send it to their peers, and so on. In this way, it propagates throughout the network. 
* Certain nodes, called miners, maintain a list of all of these new transactions and use them to create new blocks, which they then send to the rest of the network. 
* Whenever a node receives a block, it checks the validity of the block and of all of the transactions therein and, if valid, adds it to its blockchain and executes all of said transactions. 
* As the network is non-hierarchical, a node may receive competing blocks, which may form competing chains. The network comes to consensus on the blockchain by following the "longest chain rule", which states that the chain with the most blocks at any given time is the canonical chain. This rule achieves consensus because miners do not want to expend their computational work trying to add blocks to a chain that will be abandoned by the network.


## Consensus protocols

* **Proof-of-Work (PoW)**: used by Bitcoin's protocol. Validate transactions to the miners, who are the nodes that solve cryptographic, or mathematical problems, using their computers. Miners who solve a problem and validate and enable a block record are rewarded with bitcoin.
* **Proof-Of-Stake (PoS)**: used by Ethereum. Forgers (instead of miners) stake an amount of cryptocurrency, which allows them a chance, based on probability, to be a block validator. The successful forger receives the relevant block transaction fees as a reward. 
* **Proof-of-Authority (PoA)**: more centralized, it has predetermined block validators. New blocks on a blockchain are only created when the validators are in the majority. Used by a newer blockchain, Elysian.

<br>

# 🥞 🪙
---

# Ethereum

*Ethereum is a technology that lets you send cryptocurrency to anyone for a small fee.*

*Ethereum is an open-source, public, blockchain-based distributed ledger featuring smart contract (scripting) functionality. It enables developers to build blockchain applications with business logic that execute in a trustless environment, while leveraging the high availability of the Ethereum network.*

* [What's Ethereum](https://ethereum.org/en/what-is-ethereum/)
* [Ethereum Improvement Proposals](https://eips.ethereum.org/)
* [Scaffold ETH](https://github.com/austintgriffith/scaffold-eth)


### Ether (Ξ)

*Ether (ETH) is the cryptocurrency generated by the Ethereum protocol as a reward to miners in a proof of work system for adding blocks to the blockchain.*

### Accounts

* **user accounts**: create transactions, which must be signed using the account's private key, a 64-character hexadecimal string that should only be known to the account's owner (signature algorithm is ECDSA). 

* **contracts**: associated code and storage (the values of the variables at any given time). For instance, it might send ETH, alter its storage values, create temporary storage, call any of its own functions, call any public function of a different contract, create a new contract, and query information about the current transaction or the blockchain.


### Virtual machine

*The Ethereum Virtual Machine (EVM) is the runtime environment for smart contracts in Ethereum. It is a 256-bit register stack designed to run the same code exactly as intended (a fundamental consensus mechanism for Ethereum).*


### Gas

*Ethereum transaction fees: to transact on the network, users pay gas fees in ETH to miners running the computers that validate, or process, every transaction completed (from simple token transfers to more complex engagements with dapps). It's a unit of account within the EVM.*

*This fee mechanism is designed to mitigate transaction spam, prevent infinite loops during contract execution, and provide for a market-based allocation of network resources.*


* [Check gas price](https://www.gasnow.org/)
* [eth gas station](https://ethgasstation.info/)




### Trading protocols 

* [Uniswap](https://uniswap.org/)


### Protocols

* [polygon](https://polygon.technology/get-started/): protocol for connecting Ethereum-compatible blockchain networks.


### Sharding 

*If the Ethereum nodes become too expensive to run, the network will be more susceptible to centralization. A solution is to split the entire Ethereum network into multiple portions. Each shard would contain its own independent state, meaning a unique set of account balances and smart contracts.*


### Ethereum 2.0 (Serenity)

*The main purpose of the upgrade is to increase transaction throughput for the network from the current of about 15 transactions per second to up to tens of thousands of transactions per second.*

*Increase throughput by splitting up the workload into many blockchains running in parallel (sharding), having them all share a common consensus proof of stake blockchain.*


### Security

* In 2016, a flaw in The DAO was exploited to steal $50 million of Ether. As a result, the Ethereum community voted to hard fork the blockchain to reverse the theft. Ethereum Classic (ETC) continued as the original chain.

### Ethereum standards tokens:

* [**ERC-721**](https://eips.ethereum.org/EIPS/eip-721): non-fungible tokens.
* **ERC-20**: fungible tokens.
* **ERC-1400**: security tokens that be sold as securities.
* **ERC-223**: allows for the transaction fees to be paid using the tokens involved. 
* **ERC-777**: aims to be an improvement on the ERC20 standard by lowering overheads and adding new features.
* [**ERC-998**:](https://eips.ethereum.org/EIPS/eip-998): Composable Non-Fungible Token standard.

<br>

# 🧆 🪙
---

# Matic / Polygon

* A [protocol and a framework](https://polygon.technology/) for building and connecting Ethereum-compatible blockchain networks.


---

# Flow



* [Flow](https://www.onflow.org/primer): "smart contracts assembled like lego blocks".
* [Cadence playground](https://play.onflow.org/)
* [Awesome flow](https://github.com/gianni-dalerta/awesome-flow)


### Flow standards tokens:
* [Fungible Token Standard](https://github.com/onflow/flow-FT)
* [Flow Non-Fungible Token Standard](https://github.com/onflow/flow-NFT)



<br>

# 🥨 🪙
---

# Permanent storage solutions (Arweave and IPFS)


* [Check my NFT](https://checkmynft.com/): explains the problem.
* [Arweave](https://www.arweave.org/)
* [IPFS to Arweave](https://ipfs2arweave.com/)
* [infiNFT](https://infinft.com/): on-chain metadata and image storage, available for 3D, audio, multiple files
* [Mintable](https://mintable.app/)
* [Mintbase](https://mintbase.io/)
* [Pinata](pinata.cloud)



<br>

# 🥖 🪙
---

# Smart Contracts


## Solidity (Ethereum)


* [ERC-721 Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721)
* The ERC721 metadata JSON schema:

```
{
    "title": "Asset Metadata",
    "type": "object",
    "properties": {
        "name": {
            "type": "string",
            "description": "Identifies the asset to which this NFT represents"
        },
        "description": {
            "type": "string",
            "description": "Describes the asset to which this NFT represents"
        },
        "image": {
            "type": "string",
            "description": "A URI pointing to a resource with mime type image/* representing the asset to which this NFT represents. Consider making any images at a width between 320 and 1080 pixels and aspect ratio between 1.91:1 and 4:5 inclusive."
        }
    }
}
```

* [CryptoPunksMarket Solidity contract](https://github.com/larvalabs/cryptopunks/blob/master/contracts/CryptoPunksMarket.sol)
* [CryptoCats contract](https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#readContract)


### Repositories & Tools

* [Chainlink](https://chain.link/)
* [OpenZeppelin](https://openzeppelin.com/): libraries of modular, reusable, secure smart contracts for Ethereum network, written in Solidity.
* [Brownie](https://github.com/eth-brownie/brownie): Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
* [Mamba](https://mamba.black/): a framework to write, compile, and deploy smart contracts written in Vyper language and Solidity language.


## Cadence (Flow)


* [Tutorial to deploy, store, and transfer NFT](https://docs.onflow.org/cadence/tutorial/04-non-fungible-tokens/).


<br>

# 🍣 🪙
---


# Artist, creators, and collectors

*The lesson of Web 2.0: when the process of sharing content with others is owned entirely by private platforms, the cost of this mediation falls heavily on creators.*

## Collectibles

* [CryptoKitties](https://www.cryptokitties.co/): the first digital asset to use the ERC721 asset standard for NFTs (in 2017).
* [Rare Pepe Wallet](https://rarepepewallet.com/)
* [Non fungible pepes](https://nonfungiblepepe.com/): set of 1069 NFTs.
* [Bullrun Babes](https://www.bullrunbabes.com/rules): set of 888 NTFs, based on Legend cards.
* [CryptoPunks](https://www.larvalabs.com/cryptopunks)
* [Curio Cards](https://curio.cards/)
* [Joy World](https://www.joy.world/)
* [Axie](https://axieinfinity.com/): A digital nation.

## Marketplaces

- [Known Origin](https://knownorigin.io/): curated marketplace for rare digital work, featuring artists, on Ethereum, files held on IPFS.
- [Foundation](https://foundation.app/): crated marketplace backed on MetaMask wallet, on Ethereum.
- [Digitalax](https://marketplace.digitalax.xyz/): digital fashion engine.
- [Terra Virtua](https://terravirtua.io/): immersive digital collectible platform.
- [Zora.co](https://zora.co/): curated marketplace backed on MetaMask wallet, on Ethereum.
- [Nifty Gateway](https://niftygateway.com/): marketplace created by [Gemini](https://www.gemini.com/).
- [OpenSea.io](https://opensea.io/): open marketplace on ERC721 and ERC1155.
- [CryptoSlam.io](https://www.cryptoslam.io/): collect digital cards.
- [Rarible](https://rarible.com/): community-owned NFT marketplace.
- [SuperRare](https://superrare.co/): collect digital art work.
- [Wax](https://wax.io/): decentralized video game and entertainment network.
- [NonFungible.com](https://nonfungible.com/): database of blockchain gaming and crypto collectible markets.
- [Data.nyc](https://dada.nyc/artgallery): collection of virtual conversations.
- [Maecenas.co](https://www.maecenas.co/): fine art investments.
- [Portion](https://portion.io/): premier online marketplace.
- [Meme factory](https://memefactory.io/): A decentralized registry and marketplace for the creation, exchange, and collection of provably rare digital assets.
- [beta.cent.co](https://beta.cent.co/~discover/).
- [Async.art](https://async.art/)
- [Token Trove](https://tokentrove.com/)
- [Cargo](https://cargo.build/)
- [Blockparty](https://blockparty.co/)
- [Charged Particles](https://app.charged.fi/go/market)
- [Don't buy meme](https://dontbuymeme.com/)
- [Ghost Market](https://ghostmarket.io/).


## Games and Gaming Marketplaces

- [Enjix](https://enjinx.io/eth/marketplace)
- [Neon District](https://neondistrict.io/)
- [Hedgie](https://www.hedgie.io/)
- [My Crypto Heros](https://www.mycryptoheroes.net/)
- [Skyweaver](https://www.skyweaver.net/)
- [War of Crypta](https://warofcrypta.com/)
- [Mine or Die](https://warriders.com/)
- [World of Ether](https://worldofether.com/)
- [Crypto Weebs](https://www.crypto-weebs.com/)
- [Axie infinity](https://axieinfinity.com/)



## Upcoming technologies

### Zora Protocol

[Zora Protocol](https://zora.engineering/whitepaper) is a universal market protocol for media ownership. Creators can set a perpetual ownership stake in their work, and are rewarded whenever ownership changes hands. Based on Ethereum blockchain and ERC-721 tokens.

   - Each piece of media is embedded with a market, consisting of a transparent pool of bids.
   - Whenever a bid is accepted, or an ask fulfilled, the piece of media is transferred to the buyer, and the funds from that bid are split amongst its shareholders. There can be up to three shareholders for a piece of media: the owner, the previous owner, and the original creator.
   - Zora protocol introduces integrity checks to ensure that media and its metadata are provably unique. The representation of media on the Zora protocol is two URI pointers: one to the metadata, and one to the content itself (the URI can be updated, but the sha256 checksums representing the data they point to may not).
   - Uses Bids to represent buy-side liquidity for a piece of media and specifies an ERC-20 currency to be bid with (allowing for a market of many currencies to exist for the media):

```
struct Bid {
    // Amount of the currency being bid
    uint256 amount;
    // Address to the ERC20 token being used to bid
    address currency;
    // Address of the bidder
    address bidder;
    // Address of the recipient
    address recipient;
    // % of the next sale to award the previous owner
    Decimal.D256 sellOnFee;
}

struct Ask {
    // Amount of the currency being asked
    uint256 amount;
    // Address to the ERC20 token being asked
    address currency;
    // % of the next sale to award the seller
    Decimal.D256 sellOnFee;
}
```



## Understanding assets

* [NFT Market Overview](https://nonfungible.com/market/history)
* [Crypto slam](https://www.cryptoslam.io/)
* [Etherscan](https://rinkeby.etherscan.io/): search by address, txn hash, block.




<br>

# 🥧 🪙
---


# Socioeconomics of decentralizing the world

## Communities

* [Peeps democracy](https://medium.com/peeps-democracy)


## Opinionated articles 

* [Why people collect art](https://aeon.co/essays/what-drives-art-collectors-to-buy-and-display-their-finds)
* [Some thoughts on token governance and curation](https://medium.com/knownorigin/some-thoughts-on-token-governance-and-curation-a-look-into-a-possible-future-for-knownorigin-41ac900f8a79)
* [Why Decentralization Matters](https://onezero.medium.com/why-decentralization-matters-5e3f79f7638e)
* [Can cryptoart really change the world](https://medium.com/knownorigin/can-cryptoart-really-change-the-world-54f26a4f2821)




## Monetization

*Protocols such as NFTfi and Rocket allow NFTs to be used as collateral for peer-to-peer loans, enabling holders to treat their digital collectibles like any other asset to be monetized.*

* [$WHALE](http://):
* [NFTfi](https://nftfi.com/): marketplace for NFT collateralized loans.
* [Rocket](https://defirate.com/rocket-nft-loans/). collateralized lending.
* [NFT20](https://nft20.io/): Decentralized NFT Trading Protocol.
* [NFY](https://nfy.finance): DeFi protocol.
* [nftx.org](https://nftx.org/#/): platform for making ERC20 tokens that are backed by NFTs (funds, fungible, composable). For example, **CryptoPunks NFT funds**: $PUNK, $PUNK-BASIC, $PUNK-FEMALE, $PUNK-ATTR-4, $PUNK-ATTR-5, $PUNK-ZOMBIE.
* [Tokenize Real Estate](https://blog.realt.co/)


<br>

# 🥯 🪙
---

# Acronyms and concepts


* **DApps**: decentralized applications (which can include games, digital collectibles, online-voting systems, financial products and many others).
* **DAOs**: decentralized autonomous organizations (MakerDao is an example).
* **DeFi**: decentralized finance: social currency backed by high-values assets.
* **DEXs**: decentralized exchanges ([Uniswap](https://uniswap.org/) is an example).
* **Liquidity pools**: pool of tokens locked in the smart contract, used to facilitate trade by providing liquidity, and used by some of the decentralized exchanges.
* **AMMs**: automated market Mmkers.
* **Stablecoins**: offers users vital means of storing and transferring value on the blockchain, without exposing them to volatility.
* **DAI**: stablecoin cryptocurrency, maintained by MakerDao. 
* **Chainlink VRF**: verifiable randomness function that allow developers to apply random traits to an NFT.
* **minting**: creating of NFTs (the process of validating information, creating a new block, and recording that information into the blockchain).
* **burning**: destruction NFTs.

<br>

# 🥘 🪙
---

# Hot Wallets to get started

(remember: not your keys, not your coins)

* [MetaMask](https://metamask.io/)
* [rainbow](https://rainbow.me/)
* [Coinbase](https://wallet.coinbase.com/)
* [Pillar](https://pillarproject.io/)
* [Enjin](https://enjin.io/software/wallet)
* [Trust Wallet](https://trustwallet.com/)
* [Exodus](https://www.exodus.com/)

<br>

# 🍮 🪙
---

# Community, Curators, Aggregators


* [Crypto Art Pulse](https://cryptoartpulse.com/)
* [ETH Global](https://ethglobal.co/)


<br>

# 🍇 🪙
---


# Moar

### General Guides


* [⭐️ ⭐️ ⭐️ ⭐️ ⭐️ - NFTs Skeptics Guide](https://justincone.com/posts/nft-skeptics-guide/)
* [⭐️ ⭐️ ⭐️ ⭐️ - NFTs players and Landscape](https://coopahtroopa.mirror.xyz/PF42Z9oE_r6yhZN9jZrrseXfHaZALj9JIfMplshlgQ0)
* [⭐️ ⭐️ ⭐️ ⭐️ - OpenSea NFT Bible](https://opensea.io/blog/guides/non-fungible-tokens/)
* [⭐️ ⭐️ ⭐️ ⭐️ - Cryptopedia](https://www.gemini.com/cryptopedia)
* [⭐️ ⭐️ ⭐️ - A beginner guide to NFTs](https://linda.mirror.xyz/df649d61efb92c910464a4e74ae213c4cab150b9cbcc4b7fb6090fc77881a95d)
* [⭐️ ⭐️ ⭐️ - Crypto makes the internet ownable](https://variant.mirror.xyz/T8kdtZRIgy_srXB5B06L8vBqFHYlEBcv6ae2zR6Y_eo)
* [⭐️ ⭐️ - NFT Beginner's Guide](https://decrypt.co/resources/non-fungible-tokens-nfts-explained-guide-learn-blockchain)

### DAOs

* [The DAO of Daos](https://www.notboring.co/p/the-dao-of-daos).

