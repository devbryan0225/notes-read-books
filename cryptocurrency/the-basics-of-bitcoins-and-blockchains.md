# The Basics of Bitcoins and Blockchains by Antony Lewis

## Part 2 Interbank Payments
- Savings accounts are bank liabilities. Commercial banks have corresponding accounts in Central banks, facilitating transfer between customer accounts (liabilities).
- Currencies are kept within countries, and that sending money overseas is really just transferring money from sender to target foreign bank's corresponding account in sender's country.
- Banks do not loan out of customer's accounts, instead a balance of both asset and liability is created for a loan.

## Part 3 Cryptography
- address is the public key
- sign the transaction with private key which is the signature
- the bitcoin address (public) is generated from the private key
- cryptographic hashing function
  1. deterministic (x always result in y)
  2. quick forward calculation
  3. unfeasible backward calculation
  4. small change in x result in very different y
  5. not feasible to find matching hash values
- message + private key -> digital signature
- message + digital signature + public key -> valid/invalid

## Part 4 Cryptocurrencies
- Remove third party control/ admin through self generation public and private keys.
- Remove central bookkeeper by duplication. Prevents tampering by redundancy and allowing nodes to come and go.
- Solve transaction ordering by recording transactions in less frequenct batches or blocks. Allows time to agree on ordering of transaction blocks.
- The transaction in a block is confirmed with each addition of chained block.
- mining: when hash is not less than target, computer has to update nonce field and rehash until it meets the target.
- blockchains are tamper-evident since each block hash based on the previous block hash. 'immutable'
- long chain rule ensure new blocks are created on long chains. retailers are advised to wait for their block to be buried deep.
- Proof of work, block creators meet hash target by manipulating nonce values.
- each transaction records input outputs amount.
### Bitcoin
- decentralised yet software is mainly bitoin core and group mining pools.
- bitcoin is earned through self block rewards or transaction fees, expecting transaction to replace block rewards in the future. 
### Wallet
- the wallet doesn't store balances, instead it stores transactions
- an ethereum node contains pieces of code (smart contract) that is invoked by transaction and ledgers updated with the results
- does proof-of-stake instead of proof-of-work (calculation opportunity proportional to coins owned)
- transaction fees differs in transaction type
- gas price * amount used
- block size based on computational complexity
Eth blocks are based on gas limits, max of 8 mil gas
Uncles instead of orphans
Ethereum VM to do decentralized calculations, Swarm to store and receive data, Whisper to send and receive encrypted messages

Smart contracts are short programs uploaded onto the blockchain.
Smart contract languages like solidity, serpent, lisp compiles and runs on ethereum vm.
Ethereum software include geth, eth and pyethapp.
Ethereum enterprise alliance, develop roadmap for enterprise features and requirements, apply industry use case.
Forking codebase creates altcoins, leading to innovation.
Fork live blockchain, or chainsplit, by changing protocol rules, and successful when adopted by enough participants. Participants have shared history of balance on both ledgers.

Soft fork, blocks by participants who hasn't upgrade still valid.

Digital tokens
Blockchain native tokens, asset backed tokens, utility tokens, security tokens (backed by assets)
Erc 20 is utility tokens that can be spent on goods and services. A claim of service provided by the issuer.
Asset backed tokens - depository tokens, title tokens, contract tokens.
Ex. Represent gold bought at a company.
Hard to fake, relieve manual effort passing documents, and p2p system allows trading on exchange over self hosting.

Blockchain technology
Permissionless meaning create blocks or be bookkeeper without needing permission from authority.
Examples of permissiones blockchain are corda, hyperledger fabric and quorum. No incentive or proof of work needed.
Common concepts in blockchain technologies: database, broadcast/replication, peer to peer, cryptographic methods.

Private blockchains
Duplicate data such as invoices and having to update copies once paid.
Corda enable legal contacts to be managed and synchronized across mutually untrusting businesses.

ICO
token sales
Funders pays in cryptocurrency in exchange for security or utility tokens.
Tokens deemed to be securities will only hold private sales to accredited investors.
Else it will start off in private sales, pre sales and finally public offering.
Investors look to own the product or service, some wants to resell at higher price once token is available on exchange.

Investing
Pricing
Token claim on underlying asset will have price based on that asset.
Buy/sell at a price when someone has agreed on that price.
