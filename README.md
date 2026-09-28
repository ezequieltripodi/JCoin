# JCoin

JCoin is a **Java-based, server-authoritative cryptocurrency system prototype** featuring a blockchain, cryptographic hashing, wallet management, and block mining.

Each JCoin **node** is an independently operated server. The node maintains and stores the complete blockchain and is responsible for validating blocks, processing the chain, and deriving wallet balances.

Clients can communicate with nodes over **TCP sockets** to submit mining results, get wallet balances, and push blocks to the network. Mining provides the mechanism for generating coins, after a minable block's nonce is found, the user is rewarded with a set amount of JCoins.

Nodes do not communicate or synchronize with one another. Each node therefore operates as an **independent JCoin network** with its own blockchain.
