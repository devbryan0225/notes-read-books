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
- decentralised yet software is mainly bitoin core and group mining pools.
- bitcoin is earned through self block rewards or transaction fees, expecting transaction to replace block rewards in the future. 
