#Introducing Project "Bletchley"
*Marley Gray, Director Blockchain Business Development and Strategy - Microsoft*

###Microsoft's Blockchain Architecture Overview

Blockchain has captured the collective curiosity of the business and technology world and rapidly approaches the peak of the hype-cycle witnessed in other technology “fads” of the past.  However, this “fad” is different from those in that it is **largely not based on new technology**, but rather a composite of proven technologies applied to create the underpinning of Bitcoin.  However, that same technology when applied to other use cases happens to address a substantial latent pain that exists across industries.  Blockchain, or more accurately Distributed Ledger, is more of a catalyst to inspire change in the way disparate organizations work together in highly competitive markets.  Existing inter-company transactions carry enormous costs in process, procedure and crosschecking of records to come to settlement on what could turn out to be a trivial exercise using blockchain technology.  In short, blockchain or distributed ledger technologies can provide the next wave of innovation that streamlines the way business operates, the same way the web did, giving birth to a new collaborative economy.


If you are already comfortable with blockchain technology and do not need an introduction, please skip forward to the [Bletchley Overview](#bletchley).
##Definitions##
###Cryptographically Tokenized Assets###
 






![Tokenization](images/tokenization.png)

For example, if a screwdriver manufacturer creates a new screwdriver, they could tokenize the screwdriver and record it using the digital signature of the manufacturer establishing provenance.  Then, once sold and shipped to a distributor, a transaction transfers ownership of the tokenized screwdriver to the distributor (public key).  This transfer of ownership is confirmed by signing the transaction with the same digital signature of the manufacturer.  The distributor can repeat the same exercise using their keys when selling the asset in the future, documenting the lineage of that screwdriver as it navigates the supply chain.



This allows assets to be tracked individually and collectively across organizations which is not possible with today’s serial number and SKU system.


 

![Blockchain](images/blockchain.png)

For a transaction to be valid, the address tokens must be valid as well. For example, in order to create a token for an object, you as an individual need a token as well which is usually called an account.  When you create an account, you are establishing provenance for your identity (anonymously or not).  Once you have an account, you can create transactions by signing them with your private key. 
 

![Lineage](images/lineage.png)

Using this simple database, that is authentic, shared, not centrally owned and immutable allows for a shared truth to resolve all sorts of lengthy human intensive processes.






RDBMS systems evolved to include logic in the form of stored procedures to assist with more complex data operations.  Much like this, distributed ledgers have added a logic tier in the form of Smart Contracts. This code exists alongside the data in the database.  This can be thought of as Blockchain 2.0.  Ethereum, Eris and others fall into Blockchain 2.0

![2.0](images/bc2.png)

This added code is called SmartContracts.  These SmartContracts operate just like tokenized programs, they have public keys just like any other thing on the network, however they have code and can “do” things like a stored procedure would.  SmartContracts offer a lot of promise to create intelligent systems with self-enforcing contracts to allow business processes to operate independently.  

Blockchain 2.0 and 1.0 differ in how things are tokenized and are transacted against.  A SmartContract is essentially a ledger of itself within the distributed ledger.  Tokenized assets exist within SmartContracts themselves.  Whereas 1.0 UTXO databases transact directly against tokenized assets and their unspent transaction outputs (UTXO).  This is not the forum to discuss which approach is better, but its safe to assume that both types of systems will exist and in fact a good argument can be made that both are needed.  An example of this could be tokenizing entities like people, organizations, assets, commodities…actual things which are created or “provenanced” on a UXTO blockchain and the applications or contracts that work with those items are “provenanced” on SmartContract based systems.  It is trivial to record the public key or hash of an item created in a UXTO database within a SmartContract. 







For example, in financial services, a distributed ledger that meets the performance, security, privacy, regulatory and functional requirements for a derivative contract will be different from one that does cross boarder payments.  So there will need to be two separate distributed ledgers operating those networks.  This will NOT require a 1-1 mapping between product and blockchain since similar products can reside on the same distributed ledger.

![ConsortiumNode](images/bcdc.png)

A modular framework will allow consortiums to pick the best of breed components and build their distributed applications regardless of the detail underneath.  Additionally, it will allow for the components to change baring any dependencies created above the core layer.

##Bletchley introduces Cryptlets##


![Cryptlets](images/cryptlets.png)





Contract Cryptlets can function as autonomous agents or bots, interacting with the world off the chain while maintaining the integrity of the blockchain and SmartContract itself.  Contract Cryptlets are attractive to consortium blockchains where SmartContracts are signed by known counter-parties and there is no need for execution of the logic to run globally.  This will allow SmartContract based blockchains to scale their computational power as well as their overall performance.

![UtilityVContract](images/UtilityVContract.png)

[encryptField=”ContractSignersOnly”]
```

![CryptletSecurityEnvelope](images/trustenvelop.png)

Using Cryptlets via the CryptoDelegate, the security envelope is extended from the SmartContract on the blockchain using secure communications(HTTPS/SSL), attested hosting, key verification and signature recording in the SmartContract by the Cryptlet providing the service.  Optional Cryptlet attributes can also provide for process isolation for additional levels of security.



![3.0](images/evolution.png)


 
![Bletchley](images/bletchleyarchitecture.png)






![Azure Marketplace](images/marketplace.png)
![Consortium](images/consortiumrings.png)

  

More about Bletchley will be disclosed and discussed at [Microsoft's World Wide Partner Conference July 12-16th in Toronto.](https://partner.microsoft.com/en-US/wpc)  See you there!