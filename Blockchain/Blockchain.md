## What Is a Blockchain?

A blockchain is a distributed database or ledger [shared among a computer network](https://www.investopedia.com/terms/f/ftp-file-transfer-protocol.asp)'s nodes. They are best known for their crucial role in cryptocurrency systems for maintaining a secure and decentralized record of transactions, but they are not limited to cryptocurrency uses. Blockchains can be used to make data in any industry immutable—the term used to describe the inability to be altered.

Because there is no way to change a block, the only trust needed is at the point where a user or program enters data. This aspect reduces the need for trusted third parties, which are usually auditors or other humans that add costs and make mistakes.

Since Bitcoin's introduction in 2009, blockchain uses have exploded via the creation of various cryptocurrencies, decentralized finance (DeFi) applications, non-fungible tokens (NFTs), and smart contracts.  

### KEY TAKEAWAYS

- Blockchain is a type of shared database that differs from a typical database in the way it stores information; blockchains store data in blocks linked together via cryptography.
- Different types of information can be stored on a blockchain, but the most common use for transactions has been as a ledger. 
- In Bitcoin’s case, blockchain is decentralized so that no single person or group has control—instead, all users collectively retain control.
- Decentralized blockchains are immutable, which means that the data entered is irreversible. For Bitcoin, transactions are permanently recorded and viewable to anyone.

![Blockchain](https://www.investopedia.com/thmb/BKycn4lBpa_8aIB7gvb0dgreDoY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Blockchain_final-086b5b7b9ef74ecf9f20fe627dba1e34.png)

Investopedia / Xiaojie Liu

## How Does a Blockchain Work?

  
You might be familiar with spreadsheets or databases. A blockchain is somewhat similar because it is a database where information is entered and stored. But the key difference between a traditional database or spreadsheet and a blockchain is how the data is structured and accessed.

A blockchain consists of programs called scripts that conduct the tasks you usually would in a database: Entering and accessing information and [saving and storing it somewhere](https://www.investopedia.com/10-biggest-blockchain-companies-5213784). A blockchain is distributed, which means multiple copies are saved on many machines, and they must all match for it to be valid.

The blockchain collects transaction information and enters it into a [block](https://www.investopedia.com/terms/b/block-bitcoin-block.asp), like a cell in a spreadsheet containing information. Once it is full, the information is run through an encryption algorithm, which creates a hexadecimal number called the hash.

The hash is then entered into the following block header and encrypted with the other information in the block. This creates a series of blocks that are chained together.

### Transaction Process

Transactions follow a specific process, depending on the blockchain they are taking place on. For example, on Bitcoin's blockchain, if you initiate a transaction using your cryptocurrency wallet—the application that provides an interface for the blockchain—it starts a sequence of events.

In Bitcoin, your transaction is sent to a memory pool, where it is stored and queued until a miner or validator picks it up. Once it is entered into a block and the block fills up with transactions, it is closed and encrypted using an encryption algorithm. Then, the mining begins.

![Blockchain](https://www.investopedia.com/thmb/Wkxt-BotrjUCXiarPkmE4c_8kPY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dotdash_Final_Blockchain_Sep_2020-01-60f31a638c4944abbcfde92e1a408a30.jpg)

The entire network works simultaneously, trying to "solve" the hash. Each one generates a random hash except for the "nonce," short for number used once.

Every miner starts with a nonce of zero, which is appended to their randomly-generated hash. If that number isn't equal to or less than the target hash, a value of one is added to the nonce, and a new block hash is generated. This continues until a miner generates a valid hash, winning the race and receiving the reward.

Generating random hashes until a specific value is found is the "proof-of-work" you hear so much about—it "proves" the miner did the work. The amount of work it takes to validate the hash is why the Bitcoin network consumes so much computational power and energy.

Once a block is closed, a transaction is complete. However, the block is not considered to be confirmed until five other blocks have been validated. [Confirmation takes the network about one hour](https://www.investopedia.com/what-are-layer-1-and-layer-2-blockchain-scaling-solutions-7104877) to complete because it averages just under 10 minutes per block (the first block with your transaction and five following blocks multiplied by 10 equals about 60 minutes).

Not all blockchains follow this process. For instance, the Ethereum network randomly chooses one validator from all users with ether staked to validate blocks, which are then confirmed by the network. This is much faster and less energy intensive than Bitcoin's process.

## Blockchain Decentralization

A blockchain allows the data in a database to be spread out among several network nodes—computers or devices running software for the blockchain—at various locations. This not only creates redundancy but maintains the fidelity of the data. For example, if someone tries to alter a record at one instance of the database, the other nodes would prevent it from happening. This way, no single node within the network can alter information held within it.

Because of this distribution—and the encrypted proof that work was done—the information and history (like the transactions in cryptocurrency) are irreversible. Such a record could be a list of transactions (such as with a cryptocurrency), but it also is possible for a blockchain to hold a variety of other information like legal contracts, state identifications, or a company’s inventory.

## Blockchain Transparency

Because of the decentralized nature of the Bitcoin blockchain, all transactions can be transparently viewed by either having a personal node or using [blockchain explorers](https://www.blockchain.com/explorer?utm_campaign=dcomnav_explorer) that allow anyone to see transactions occurring live. Each node has its own copy of the chain that gets updated as fresh blocks are confirmed and added. This means that if you wanted to, you could track a bitcoin wherever it goes. 

For example, exchanges have been hacked in the past, resulting in the loss of large amounts of cryptocurrency. While the hackers may have been anonymous—except for their wallet address—the crypto they extracted are easily traceable because the wallet addresses are published on the blockchain.

Of course, the records stored in the Bitcoin blockchain (as well as most others) are encrypted. This means that only the person assigned an address can reveal their identity. As a result, blockchain users can remain anonymous while preserving transparency.

## Is Blockchain Secure?

Blockchain technology achieves decentralized security and trust in several ways. To begin with, new blocks are always stored linearly and chronologically. That is, they are always added to the “end” of the blockchain. After a block has been added to the end of the blockchain, previous blocks cannot be changed.

A change in any data changes the hash of the block it was in. Because each block contains the previous block's hash, a change in one would change the following blocks. The network would reject an altered block because the hashes would not match.

Not all blockchains are 100% impenetrable. They are distributed ledgers that use code to create the security level they have become known for. If there are vulnerabilities in the coding, they can be exploited.

For instance, imagine that a hacker runs a node on a blockchain network and wants to alter a blockchain and steal cryptocurrency from everyone else. If they were to change their copy, they would have to convince the other nodes that their copy was the valid one.

They would need to control a majority of the network to do this and insert it at just the right moment. This is known as a 51% attack because you need to control more than 50% of the network to attempt it.

Timing would be everything in this type of attack—by the time the hacker takes any action, the network is likely to have moved past the blocks they were trying to alter. This is because the rate at which these networks hash is exceptionally fast—the Bitcoin network hashed at 348.1 exahashes per second (18 zeros) on April 21, 2023.1

## Bitcoin vs. Blockchain

Blockchain technology was first outlined in 1991 by Stuart Haber and W. Scott Stornetta, two researchers who wanted to implement a system where document timestamps could not be tampered with. But it wasn’t until almost two decades later, with the launch of Bitcoin in January 2009, that [blockchain had its first real-world application](https://www.investopedia.com/news/what-genesis-block-bitcoin-terms/).2

The Bitcoin protocol is built on a blockchain. In a research paper introducing the digital currency, Bitcoin’s pseudonymous creator, [Satoshi Nakamoto](https://www.investopedia.com/terms/s/satoshi-nakamoto.asp), referred to it as “a new electronic cash system that’s fully peer-to-peer, with no trusted third party.”3

The key thing to understand is that Bitcoin uses blockchain as a means to transparently record a ledger of payments or other transactions between parties.

### Blockchain

Blockchain can be used to immutably record any number of data points. This could be in the form of transactions, votes in an election, product inventories, state identifications, deeds to homes, and much more.   

Currently, tens of thousands of projects are looking to implement blockchains in various ways to help society other than just recording transactions—for example, as a way to vote securely in democratic elections.

The nature of blockchain’s immutability means that fraudulent voting would become far more difficult. For example, a voting system could work such that each country's citizens would be issued a single cryptocurrency or token.

Each candidate would then be given a specific wallet address, and the voters would send their token or crypto to the address of whichever candidate for whom they wish to vote. The transparent and traceable nature of blockchain would eliminate the need for human vote counting and the ability of bad actors to tamper with physical ballots.

## Blockchain vs. Banks

Blockchains have been heralded as a disruptive force in the finance sector, especially with the functions of payments and banking. However, banks and decentralized blockchains are vastly different.

To see how a bank differs from blockchain, let’s compare the banking system to Bitcoin’s blockchain implementation.

## How Are Blockchains Used?

As we now know, blocks on Bitcoin’s blockchain store transactional data. Today, more than 23,000 other cryptocurrency systems are running on a blockchain. But it turns out that blockchain is a reliable way of storing data about other types of transactions.

Some companies experimenting with blockchain include Walmart, Pfizer, AIG, Siemens, and Unilever, among others. For example, IBM has created its Food Trust blockchain to trace the journey that food products take to get to their locations.4

Why do this? The food industry has seen countless outbreaks of E. coli, salmonella, and listeria; in some cases, hazardous materials were accidentally introduced to foods. In the past, it has taken weeks to find the source of these outbreaks or the cause of sickness from what people are eating.

Using blockchain allows brands to track a food product’s route from its origin, through each stop it makes, to delivery. Not only that, but these companies can also now see everything else it may have come in contact with, allowing the identification of the problem to occur far sooner—potentially saving lives. This is one example of blockchain in practice, but many other forms of blockchain implementation exist.

### Banking and Finance

Perhaps no industry stands to benefit from integrating blockchain into its business operations more than banking. Financial institutions only operate during business hours, usually five days a week. That means if you try to deposit a check on Friday at 6 p.m., you will likely have to wait until Monday morning to see that money hit your account.

Even if you make your deposit during business hours, the transaction can still take one to three days to verify due to the sheer volume of transactions that banks need to settle. Blockchain, on the other hand, never sleeps.

By integrating blockchain into banks, consumers might see their transactions processed in minutes or seconds—the time it takes to add a block to the blockchain, regardless of holidays or the time of day or week. With blockchain, banks also have the opportunity to exchange funds between institutions more quickly and securely. Given the size of the sums involved, even the few days the money is in transit can carry significant costs and risks for banks.

The settlement and clearing process for stock traders can take up to three days (or longer if trading internationally), meaning that the money and shares are frozen for that period. Blockchain could drastically reduce that time.

### Currency

Blockchain forms the bedrock for cryptocurrencies like Bitcoin. The U.S. dollar is controlled by the Federal Reserve. Under this central authority system, a user’s data and currency are technically at the whim of their bank or government. If a user’s bank is hacked, the client’s private information is at risk.

If the client’s bank collapses or the client [lives in a country with an unstable government](https://www.investopedia.com/tech/how-blockchain-can-help-failing-economies/), the value of their currency may be at risk. In 2008, several failing banks were bailed out—partially using taxpayer money. These are the worries out of which Bitcoin was first conceived and developed.

Blockchain can also give those in countries with unstable currencies or financial infrastructures a more stable currency and financial system. They would have access to more applications and a wider network of individuals and institutions with whom they can do domestic and international business.

By spreading its operations across a network of computers, blockchain allows Bitcoin and other cryptocurrencies to operate without the need for a central authority. This not only reduces risk but also the processing and transaction fees.

Using [cryptocurrency wallets](https://www.investopedia.com/terms/d/digital-wallet.asp) for savings accounts or as a means of payment is especially profound for those without state identification. Some countries may be war-torn or have governments lacking any real identification infrastructure. Citizens of such countries may not have access to savings or brokerage accounts—and, therefore, no way to safely store wealth.

### Healthcare

Healthcare providers can leverage blockchain to store their patients’ medical records securely. When a medical record is generated and signed, it can be written into the blockchain, which provides patients with the proof and confidence that the record cannot be changed. These personal health records could be encoded and stored on the blockchain with a private key so that they are only accessible to specific individuals, thereby ensuring privacy.

### Property Records

If you have ever spent time in your local Recorder’s Office, you will know that recording property rights is both burdensome and inefficient. Today, a physical deed must be delivered to a government employee at the local recording office, where it is manually entered into the county’s central database and public index. In the case of a property dispute, claims to the property must be reconciled with the public index.

This process is not just costly and time-consuming, it is also prone to human error, where each inaccuracy makes tracking property ownership less efficient. Blockchain has the potential to eliminate the need for scanning documents and tracking down physical files in a local recording office. If property ownership is stored and verified on the blockchain, owners can trust that their deed is accurate and permanently recorded.

In war-torn countries or areas with little to no government or financial infrastructure and no Recorder’s Office, proving property ownership can be nearly impossible. If a group of people living in such an area can leverage blockchain, then transparent and clear timelines of property ownership could be established.

### Smart Contracts

A smart contract is a computer code that can be built into the blockchain to facilitate a contract agreement. Smart contracts operate under a set of conditions to which users agree. When those conditions are met, the terms of the agreement are automatically carried out.

Say, for example, that a potential tenant would like to lease an apartment using a smart contract. The landlord agrees to give the tenant the door code to the apartment as soon as the tenant pays the security deposit. The smart contract would automatically send the door code to the tenant when it was paid. It could also be programmed to change the code if rent wasn't paid or other conditions were met.

### Supply Chains

As in the IBM Food Trust example, suppliers can use blockchain to record the origins of materials that they have purchased. This would allow companies to verify the authenticity of not only their products but also common labels such as “Organic,” “Local,” and “Fair Trade.”

As reported by Forbes, the food industry is increasingly adopting the use of blockchain to track the path and safety of food throughout the farm-to-user journey.5

### Voting

As mentioned above, blockchain could facilitate a modern voting system. Voting with blockchain carries the potential to eliminate election fraud and boost voter turnout, as was tested in the November 2018 midterm elections in West Virginia.6

Using blockchain in this way would make votes nearly impossible to tamper with. The blockchain protocol would also maintain transparency in the electoral process, reducing the personnel needed to conduct an election and providing officials with nearly instant results. This would eliminate the need for recounts or any real concern that fraud might threaten the election.

## Pros and Cons of Blockchain

For all of its complexity, blockchain’s potential as a decentralized form of record-keeping is almost without limit. From greater user privacy and heightened security to lower processing fees and fewer errors, blockchain technology may very well see applications beyond those outlined above. But there are also some disadvantages.

Pros

- Improved accuracy by removing human involvement in verification
    
- Cost reductions by eliminating third-party verification
    
- Decentralization makes it harder to tamper with
    
- Transactions are secure, private, and efficient
    
- Transparent technology
    
- Provides a banking alternative and a way to secure personal information for citizens of countries with unstable or underdeveloped governments
    

Cons

- Significant technology cost associated with some blockchains
    
- Low transactions per second
    
- History of use in illicit activities, such as on the dark web
    
- Regulation varies by jurisdiction and remains uncertain
    
- Data storage limitations
    

## Benefits of Blockchains

### Accuracy of the Chain

Transactions on the blockchain network are approved by thousands of computers and devices. This removes almost all people from the verification process, resulting in less human error and an accurate record of information. Even if a computer on the network were to make a computational mistake, the error would only be made to one copy of the blockchain and not be accepted by the rest of the network.

### Cost Reductions

Typically, consumers pay a bank to verify a transaction or a notary to sign a document. Blockchain eliminates the need for third-party verification—and, with it, their associated costs. For example, business owners incur a small fee when they accept credit card payments because banks and payment-processing companies have to process those transactions. Bitcoin, on the other hand, does not have a central authority and has limited transaction fees.

### Decentralization

Blockchain does not store any of its information in a central location. Instead, the blockchain is copied and spread across a network of computers. Whenever a new block is added to the blockchain, every computer on the network updates its blockchain to reflect the change.

By spreading that information across a network, rather than storing it in one central database, blockchain becomes more difficult to tamper with.

### Efficient Transactions

Transactions placed through a central authority can take up to a few days to settle. If you attempt to deposit a check on Friday evening, for example, you may not actually see funds in your account until Monday morning. Financial institutions operate during business hours, usually five days a week—but a blockchain works 24 hours a day, seven days a week, and 365 days a year.

On some blockchains, transactions can be completed in minutes and considered secure after just a few. This is particularly useful for [cross-border](https://www.investopedia.com/articles/forex/09/currency-cross-triangulation.asp) trades, which usually take much longer because of time zone issues and the fact that all parties must confirm payment processing.

### Private Transactions

Many blockchain networks operate as public databases, meaning anyone with an internet connection can view a list of the network’s transaction history. Although users can access transaction details, they cannot access identifying information about the users making those transactions. It is a common misperception that blockchain networks like Bitcoin are fully anonymous; they are actually pseudonymous because there is a viewable address that can be associated with a user if the information gets out.

### Secure Transactions

Once a transaction is recorded, its authenticity must be verified by the blockchain network. After the transaction is validated, it is added to the blockchain block. Each block on the blockchain contains its unique hash and the unique hash of the block before it. Therefore, the blocks cannot be altered once the network confirms them.

### Transparency

Most blockchains are entirely open-source software. This means that everyone can view its code. This gives auditors the ability to review cryptocurrencies like Bitcoin for security. However, it also means there is no real authority on who controls Bitcoin’s code or how it is edited. Because of this, anyone can suggest changes or upgrades to the system. If a majority of the network users agree that the new version of the code with the upgrade is sound and worthwhile, then Bitcoin can be updated.

### Banking the Unbanked

Perhaps the most profound facet of blockchain and cryptocurrency is the ability for anyone, regardless of ethnicity, gender, location, or cultural background to use it. According to The World Bank, an estimated 1.3 billion adults do not have bank accounts or any means of storing their money or wealth.7 Moreover, nearly all of these individuals live in developing countries where the economy is in its infancy and entirely dependent on cash. 

These people are often paid in physical cash. They then need to store this physical cash in hidden locations in their homes or other places, incentivizing robbers or violence. While not impossible to steal, crypto makes it more difficult for would-be thieves.

Blockchains of the future are also looking for solutions to not only be a unit of account for wealth storage but also to store medical records, property rights, and a variety of other legal contracts.

## Drawbacks of Blockchains

### Technology Cost

Although blockchain can save users money on transaction fees, the technology is far from free. For example, the Bitcoin network's proof-of-work system to validate transactions consumes vast amounts of computational power. In the real world, the energy consumed by the millions of devices on the Bitcoin network is more than Pakistan consumes annually.8

Some solutions to these issues are beginning to arise. For example, bitcoin-mining farms have been set up to use solar power, excess natural gas from fracking sites, or energy from wind farms.

### Speed and Data Inefficiency

Bitcoin is a perfect case study for the possible inefficiencies of blockchain. Bitcoin’s PoW system takes about 10 minutes to add a new block to the blockchain. At that rate, it’s estimated that the blockchain network can only manage about three transactions per second (TPS).9 Although other cryptocurrencies, such as Ethereum, perform better than Bitcoin, blockchain still limits them. Legacy brand Visa, for context, can process 65,000 TPS.10

Solutions to this issue have been in development for years. There are currently blockchains that boast more than 30,000 TPS.11 Ethereum's merge between its main net and beacon chain (Sep. 15, 2022) is predicted to allow up to 100,000 TPS after it rolls out a series of upgrades that include sharding—a splitting of the database so that more devices (phones, tablets, and laptops) can run Ethereum. This is expected to increase network participation, reduce congestion, and increase transaction speeds.12

The other issue is that each block can only hold so much data. The [block size debate](https://www.investopedia.com/tech/history-bitcoin-hard-forks/) has been and continues to be one of the most pressing issues for the scalability of blockchains going forward.

### Illegal Activity

While confidentiality on the blockchain network protects users from hacks and preserves privacy, it also allows for illegal trading and activity on the blockchain network. The most cited example of blockchain being used for illicit transactions is probably the [Silk Road](https://www.investopedia.com/terms/s/silk-road.asp), an online dark web illegal-drug and money laundering marketplace operating from February 2011 until October 2013, when the FBI shut it down.13 

The [dark web](https://www.investopedia.com/terms/d/dark-web.asp) allows users to buy and sell illegal goods without being tracked by using the [Tor Browser](https://www.investopedia.com/terms/t/tor.asp) and make illicit purchases in Bitcoin or other cryptocurrencies. This is in stark contrast to U.S. regulations, which require financial service providers to obtain information about their customers when they open an account. They are supposed to verify the identity of each customer and confirm that they do not appear on any list of known or suspected terrorist organizations.14

Illicit activity accounted for only 0.24% of all cryptocurrency [transactions](https://www.investopedia.com/bitcoin-taproot-upgrade-5210039) in 2022.15

This system can be seen as both a pro and a con. It gives anyone access to financial accounts, but allows criminals to transact more easily. Many have argued that the good uses of crypto, like banking the unbanked world, outweigh the bad uses of cryptocurrency, especially when most illegal activity is still accomplished through untraceable cash.

### Regulation

Many in the crypto space have expressed concerns about government regulation over cryptocurrencies. While it is getting increasingly difficult and near impossible to end something like Bitcoin as its decentralized network grows, governments could theoretically make it illegal to own cryptocurrencies or participate in their networks. 

This concern has grown smaller over time as large companies like PayPal begin to allow customers to use cryptocurrencies on their e-commerce platforms.

## What Is a Blockchain in Simple Terms?

Simply put, a blockchain is a shared database or ledger. Pieces of data are stored in data structures known as blocks, and each network node has a replica of the entire database. Security is ensured since the majority will not accept this change if somebody tries to edit or delete an entry in one copy of the ledger.

## How Many Blockchains Are There?

The number of live blockchains is growing every day at an ever-increasing pace. As of 2023, there are more than 23,000 active cryptocurrencies based on blockchain, with several hundred more non-cryptocurrency blockchains.16

## What’s the Difference Between a Private Blockchain and a Public Blockchain?

A public blockchain, also known as an open or permissionless blockchain, is one where anybody can join the network freely and establish a node. Because of their open nature, these blockchains must be secured with cryptography and a consensus system like proof of work (PoW). A private or permissioned blockchain, on the other hand, requires each node to be approved before joining. Because nodes are considered to be trusted, the layers of security do not need to be as robust.

## The Bottom Line

With many practical applications for the technology already being implemented and explored, blockchain is finally making a name for itself in no small part because of Bitcoin and cryptocurrency. As a buzzword on the tongue of every investor in the nation, blockchain stands to make business and government operations more accurate, efficient, secure, and cheap, with fewer middlemen.

As we head into the third decade of blockchain, it’s no longer a question of if legacy companies will catch on to the technology—it’s a question of when. Today, we see a proliferation of NFTs and the tokenization of assets. As a result, the next decades will prove to be a significant period of growth for blockchain.

_The comments, opinions, and analyses expressed on Investopedia are for informational purposes online. Read our [warranty and liability disclaimer](https://www.investopedia.com/legal-4768893#toc-warranty-and-liability-disclaimer) for more info. As of the date this article was written, the author does not own any of the assets discussed here._