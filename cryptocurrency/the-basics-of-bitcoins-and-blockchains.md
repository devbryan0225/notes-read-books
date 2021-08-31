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
