# polygon-bootcamp-africa.wk-3
Deploying my first smart contract with polygon

**Smart Contracts** 

Smart contracts are the primary reason that the field of blockchain development exists.

Ethereum's core innovation in 2013 was to allow developers to write small chunks of code, known as smart contracts, that could be deployed to the Ethereum network to run independently of their creators. In Ethereum, smart contracts are written in Solidity, a high-level programming language designed to run on the [Ethereum Virtual Machine.](https://cypherpunks-core.github.io/ethereumbook/13evm.html)

A smart contract is a program that defines a set of rules, or "contract" that automatically executes the encoded rules when called by a user on the blockchain. In particular, once a smart contract is deployed, it will always function identically - it cannot be modified or taken control of by a bad actor.

As a result, smart contracts are ideal candidates to run financial applications - they can receive or send cryptocurrencies as independent actors in a guaranteed, repeatable fashion.

# Real-World Examples

Okay, but what are some real-world examples of tools that can be replaced by smart contracts?

- **Financial Instruments**: Typically, when you trade money for a stock, or a currency for another currency online, you'll need a third-party to hold both assets in escrow while the trade is happening - a stockbroker, for instance. Smart contracts can act as that third-party, allowing trades to happen without a middleman.
- **Property Ownership:** As compared to legal documents, smart contracts execute almost instantaneously, are publicly accessible, and can allow for fractionalized ownership.
- **Building Additional Tokens:** Incredibly enough, you can actually launch new token systems such as Tether or Chainlink on Ethereum. Similarly, you can launch NFT projects such as Bored Apes or CryptoPunks using smart contracts.

And many, many more. In fact, we're likely still just scratching the surface of what systems can be eventually redesigned with blockchain.

# Traits of Smart Contracts

What traits give smart contracts the ability to revolutionize or replace existing technical models? Unlike traditional programming languages, smart contracts have the following properties:

- **Transparency**: Smart contracts are published to the blockchain, and can be read and written by anyone who has access to the blockchain.
- **Simplicity**: Because smart contracts are expensive to deploy onto the blockchain and contain sensitive logic dictating the flow of financial transactions, they tend to be much smaller and simpler than most codebases.
- **Immutability**: Once a smart contract has been deployed, it (typically) can't be modified and is guaranteed to function identically no matter when its called! This allows smart contracts to operate as reliable, trusted third parties - because no individual controls the smart contract, it can act as a financial intermediary, a trustworthy automated market maker, or much more by guaranteeing impartiality.

Once deployed, these smart contracts behave as independent actors that are fully transparent but can contain complex logic. Therefore, instead of only human users owning accounts on Ethereum, there are two types of accounts:

- **Externally Owned Accounts** (EOAs) managed by a human user.
- **Contract Accounts** which are managed by their underlying smart contract code.



Impressively enough, these two types of accounts can do basically the same things! Both of these account types can:
• Receive or send fungible tokens (Ether) to any account
• Receive or send non-fungible tokens (a CryptoKitty) to any account
• Trigger another contract account - allowing a smart contract to run other smart contracts.
• Generate new smart contracts - allowing a smart contract to act as a contract factory!
However, there are a few limitations of contract accounts:
• Contract accounts can't instantiate actions on their own - they can only respond to transactions they receive (typically from EOAs).
• Contract accounts are controlled entirely by their code, whereas EOAs are controlled by their associated private keys.
