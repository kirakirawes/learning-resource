# A Simplified Dweb Glossary 

This is a live and non-comprehensive list of terms and phrases commonly used in the DWeb ecosystem. It also includes basic concepts relevant to computer networking and the Internet.

Created for the [DWeb for Creators](https://grayarea.org/course/dweb/) course by the Gray Area with support from the Filecoin Foundation for the Decentralized Web.


----

## Part 1. Common Dweb Terms 

## A

**ActivityPub**: A decentralized social networking protocol that provides a client/server API for creating, updating, and deleting content, and a federated server-to-server API for delivering notifications and content.

**Adoption**: Integration of a new technology, programming language, or methodology into an organization or by a group of users

**Authenticated Transfer Protocol (AT Protocol)**: A protocol for large-scale distributed social applications developed by Bluesky, focusing on account portability and algorithmic choice.


## B

**Block**: A validated, published record of data and its associated transactions, bundled together like packets for secure and chronological storage on a distributed ledger.

**Blockchain**: A decentralized, distributed digital ledger that records transactions across many computers in a peer-to-peer network, verified and validated through a consensus mechanism. While designed to be tamper-resistant, the recorded data can be modified through consensus-driven processes like forks, challenging the notion of absolute immutability

**BitTorrent**: A communication protocol for peer-to-peer file sharing which enables users to distribute data and electronic files over the Internet in a decentralized manner. There are many clients one can use to access the BitTorrent protocol such as Transmission, qTorrent, or µTorrent

**Briar**: A secure messaging app designed for activists, journalists, and anyone who needs a safe way to communicate, using direct Bluetooth or WiFi connections when internet access is unavailable.

**Byzantine Generals' Problem**: The challenge of coordinating a group facing unreliable communication. Even with conflicting messages, the generals (like blockchain nodes) must agree on a common action (like transaction validity) to achieve their goal

**Byzantine Fault Tolerance (BFT)**): Allows a system to agree on validation even when some nodes are unreliable or malicious by comparing data.


## C 

**Centralized Network**: Devices (nodes) communicate and access resources through a central server. The central server acts as a hub, controlling data flow and user access.

**Community Networks**: Local telecommunications infrastructures built, owned, and operated by communities, often in rural or underserved areas, using decentralized technologies.

**Computer**: A device that can perform calculations according to a set of predetermined instructions, usually including processing information. These instructions can be embodied in the physical design of the device itself or provided externally.

**Content Identifier (CID)**: A unique fingerprint in IPFS for a data block, acting as the address for finding that specific piece of information anywhere in the decentralized network.

**Content Addressible**: A piece of data that can be queried or referenced by what it contains

**Consensus Algorithms**: A mechanism by which nodes in the network agree on the current state of the system. In a blockchain contect, this means validating new transactions or blocks. It ensures that all participants in the network have access to the same copy of the blockchain, preventing double-spending and maintaining data integrity.​​​​​​​

**Content Delivery Networks (CDNs)**: Are geographically distributed networks of servers that host and deliver content, such as images, videos, or other streaming media, to users' federated network


**Cryptography**: Practice for secure communication usually consists of two techniques: signing and encryption

**CSPRNG**: Cryptographically secure pseudorandom number generator​​​​​​​, used to create Master Private Keys for digital wallets

**Custodial**: Services, whether blockchains themselves, platforms, or digital wallet providers, that hold funds in escrow or have access to your private keys



## D

**Data Centers**: Warehouses filled with powerful computers and networking equipment

**Data Custody**: Services that hold and manage user data on their servers, such as cloud storage providers or media platforms.

**Decentralized Network**: A structure where devices (nodes) communicate and share resources without a central authority. They can connect directly or indirectly through other nodes in the network. 

**Decentralized Autonomous Organization (DAOs)**: An entity governed by a set of rules encoded on a decentralized network. These rules, often represented by smart contracts, define how proposals are created, voted on, and executed, enabling collective decision-making and management without a central authority. DAO membership is typically represented by ownership of a specific asset associated with the organization.

**Decentralized Applications (DApps)**: A type of distributed, open-source software application that runs on a peer-to-peer (P2P) or blockchain network rather than on a single computer.

**Decentralized Storage Network (DSN)**: A distributed system that allows for secure, redundant storage of data across multiple nodes, eliminating the need for a central authority or single point of failure. It leverages peer-to-peer networking, cryptographic techniques, and economic incentives to enable reliable and censorship-resistant storage and retrieval of data.​​​​​​​ These systems often use blocks but are not blockchains.

**Delegated Proof of Stake (DPoS)**: ​​​​​​​Token holders vote to elect a small number of delegates who are responsible for validating transactions and creating blocks. ​​​​​​​***Example: EOS blockchain***

**Distributed Network**: A system where tasks or computations are divided and processed across multiple interconnected computers or devices. This distribution can be coordinated by a central server and in itself does not denote decentralization.

**Distributed Hash Table (DHT)**: A common data structure used across servers so that peers can discover each other

**Distributed Ledger**:  A record that stores all transactions across the network in a sequential chain of blocks, providing transparency and enabling participants to verify and audit transactions without the need for a central authority. While designed to be resistant to modification, a distributed ledger can be altered through consensus-driven processes like hard forks or reorganizations, challenging the notion of absolute immutability.

**Domain Name System (DNS)**: A public, decentralized database that links a unique name to an IP address, a location, and other data


## E

**End-to-end Encryption (E2EE)**: A secure communication process that prevents third parties from accessing data exchanged between devices, such as sender and receiver


## F

**Federation**: Interconnected servers that can function independently or collectively to route data between them for a common task for applications (e.g. Mastodon or PeerTube)

**Federated Network**: A network structure that combines aspects of centralized and decentralized networks. It consists of multiple independent sub-networks (nodes or groups) that agree to follow a common set of rules and protocols enforced by a central management framework. This framework facilitates communication and resource sharing between the sub-networks while still allowing them some degree of autonomy.

**Friend-to-Friend**: A type of private peer-to-peer network where connections and data sharing occur only between trusted friends or acquaintances. In an F2F network, users directly communicate with one another, enhancing the security and privacy of the shared data. This network model is mainly used in file sharing, social networking, and private communication applications. The term was coined by Dan Bricklin in 2000.

**Fungible Token**: Interchangeable, individual units that can be exchanged one-to-one with any other unit of the same kind. Examples outside of cryptocurrency include dollars, stock, and unopened cans of soda.

## G

**Gateway**: A centralized bridge between the traditional web and decentralized protocols

**Gas**: The unit used to measure the computational effort and storage space required to execute a specific transaction or smart contract on the Ethereum blockchain. All blockchains encorporate some kind of transaction fee, but they do not always use the word "gas".

**Gossip**: When one computer (A) tells another computer (B) about data it received from a 3rd computer (C) without B and C talking directly


## H 

**Hash:** A hash function is like a fingerprint for digital data. It takes information, like a text file or image, and crunches it through a mathematical formula. This formula outputs a unique fixed string of numbers and letters, called a hash value or hash, that acts as a summary of its bits.

**Hierarchical Deterministic Wallet**: Wallet software that uses a single Master or Parent Private Key to deterministically derive nearly infinite child keys. The child keys can be recovered by anyone with access to the parent but cannot be traced back to it by an outside observer.

**Holepunching**: A technique used in peer-to-peer communications to establish direct connections between devices behind NAT firewalls or routers.

**Hyperboria**: A global decentralized network built with cjdns that creates encrypted connections between nodes using public-key cryptography for routing.

**Hypercore**: An open-source, peer-to-peer technology stack that allows people to connect and share data seamlessly across the planet, all without servers

**Hypertext Transfer Protocol (HTTP)**: A location-based hypermedia server protocol for exchanging or transferring hypertext, structured text that uses logical links called hyperlinks to refer to other content on nodes. HTTP isn't encrypted.


## I 

**Identifier**: A number or string of characters that does not change and can be used to reference a piece of data or user at any point in time


**Indigenous Data Sovereignty**: The proper locus of authority over the management of data about indigenous peoples, their territories, and ways of life.

**The Institute of Electrical and Electronics Engineers (IEEE)**: A professional society for promoting the development of electronic technologies and the advancement of related professions

**Interoperable**: When two systems are able to exchange and make use of information from each other

**Inter-Plantetary File System (IPFS)**: IPFS is a peer-to-peer web storage system that breaks down files into unique blocks, storing them securely across a network of computers. IPFS uses hash functions to ensure data integrity and redundancy, making it more resistant to censorship and data loss.

**Internet Corporation for Assigned Names and Numbers (ICANN)**: The global organization responsible for coordinating the Internet's unique identifier systems, including domain names and IP addresses. Founded in 1998, it operates as a non-profit public-benefit corporation maintaining the stability and security of the Internet's core infrastructure.

**The Internet Engineering Task Force (IETF)**: Creates and publishes standards for Internet protocol suite (TCP/IP)

**The International Telecommunication Union's Standardization Sector (ITU-T)**: Allocates slices of the electromagnetic spectrum for different applications and licenses

**The International Organization for Standardization (ISO)**: Defines standards for applications in a wide number of sectors such as technology, business, government, and society

**Internet Protocol (IP)**: Standardizes how packets are addressed and routed through the internet

**Internet Protocol Security (IPSec)**: A protocol that comes with a diversity of mechanisms to ensure the integrity, authenticity, and confidentiality of data packets.

**IPNS**: Like a DNS of decentralized architecture, IPNS is a naming system for IPFS. It creates human-readable names that point to the constantly changing content addresses (CIDs) in IPFS. 


## J 


## K 

**Key Pair**: A two-part key (Public Key and Private Key) used in cryptography to provide end-to-end encryption and signature verification


## L

**Layer One (L1)**: A base-level blockchain protocol and network infrastructure that establishes the foundational rules, consensus mechanisms, and data structure for recording transactions. It serves as the primary layer upon which additional layers, such as scaling solutions or application layers, can be built to extend functionality and improve performance.

**Layer Two (L2)**: A secondary protocol built on top of an existing layer one blockchain, designed to improve scalability and transaction throughput by handling computational operations off the main chain.

**Leased Proof of Stake (LPoS)**: Token holders lease their stake to validators without transferring ownership of the tokens. This enables token holders to participate in the consensus process and earn rewards while retaining control over their tokens.​​​​​​​ Example: Waves blockchain

**Liquid Proof of Stake (LPoS):** Allows token holders to delegate their stake to validators while keeping their tokens liquid, meaning they can be moved or spent without being locked for a specific period. This system combines the security benefits of staking with liquidity for token holders. _Example_: Tezos

**LoRaWAN (Long Range Wide Area Network)**: A low-power, wide-area networking protocol built on LoRa technology, allowing for long-range communications at a low bit rate, useful for IoT and decentralized sensing networks.

## M 

**Mobile Ad-hoc Network (MANET)**: A continuously self-configuring, infrastructure-less network of mobile devices connected wirelessly, where each device can move independently in any direction.

**Master Private Key (Cryptocurrency)**: A private key used to derive many child keys, which cannot be traced back to the original parent by an outside observer (see also Hierarchical Deterministic Wallet).

**Media Access Control (MAC / aka device ID)**: A unique, identifiable address that a device needs to communicate with another device, such as a home router. A MAC address is a 12-digit hexadecimal number split up into 6 number pairs, i.e. A0:1B:2C:3D:4E:5F

**Mesh Network**: A local area network topology with no central router, in which the infrastructure nodes connect directly, dynamically and non-hierarchically to as many other nodes as possible and cooperate with one another to efficiently route data to and from clients

**Minting (Bitcoin)**: the process of creating new tokens as a reward for miners who successfully solve a complex computational puzzle to create the next block

**Minting (Non-Bitcoin)**: The concept of minting is purely colloquial outside of the Bitcoin environment, referring to the creation of any kind of token.

**Miner (PoW)**: Miners are specialized computer systems (usually Application-Specific Integrated Circuits (ASICs) ) that continuously perform complex hash computations. The first miner to find a hash below a specific target secures the right to add a new block containing validated transactions to the blockchain. The miner collects all fees associated with transactions in the created block and receives a one-time cryptocurrency payment, called the block reward.

**Mining (PoW)**: Mining is the work of maintaining a blockchain: validating transactions, performing hash calculations to search for and generate new blocks, and participating in consensus. Mining is performed simultaneously by many miners in a competitive process. Successful miners earning a block reward and transaction fees.​​​​​​​

**Message Queuing Telemetry Transport (MQTT)**: A lightweight messaging protocol designed for constrained devices and unreliable networks, using a publish-subscribe model to efficiently transmit data between IoT devices. Things applications due to its minimal bandwidth requirements and reliable message delivery system.

## N 

**Network**: A collection of interconnected devices that can share resources and communicate with each other according to a set of communication protocols.

**NAT Traversal**: Techniques for establishing and maintaining connections through Network Address Translation (NAT) gateways, fundamental for peer-to-peer communication.

**Net Neutrality:** The principle that no data online is advantaged or disadvantaged, in terms of access or flow. The closer you can get to net neutrality, the better for a Decentralized Web. 

**Network Card**: A common hardware component of an electronic telecommunications device that handles its connection to the network, including providing the network with the device's identification

**Nodes**: Nodes are devices on a network that send or receive information. On a network, a node has an address, which is how nodes find one another. Any networked hardware with a network address (MAC or IP address) is a node.

**Nominated Proof of Stake (NPoS)**: Token holders nominate validators to secure the network. It focuses on maximizing network security by distributing stakes across many validators. Example: Polkadot blockchain

**Non-Custodial**: A user maintains complete, independent control over their data or private keys, without relying on a third-party. Losing this data or to access credentials could result in permanent loss.

**Non-Fungible Token (NFT)**: ​​​​​​​Tokens with unique identifiers and other metadata that cannot be necessarily exchanged one-to-one with each other.​​​​​​​ Examples outside of cryptocurrency include artworks, houses, and used bicycles.

**Notes and Other Stuff Transmitted by Relays (Nostr)**: A simple, open protocol for creating censorship-resistant social media platforms using decentralized relays and public key cryptography.



## O 

**Optimized Link State Routing Protocol (OLSR)**: A routing protocol optimized for mobile ad hoc networks that proactively maintains routes to all destinations in the network.

**Onion Routing**: A technique for anonymous communication over a network where messages are encapsulated in multiple layers of encryption, used in networks like Tor.

**OpenWrt**: A Linux operating system targeting embedded devices, commonly used in mesh networking applications and community networks.

**Open Systems Interconnection (OSI) Model**: A conceptual framework that standardizes network communication functions into seven distinct layers, from physical transmission at the bottom to application interfaces at the top. Each layer serves a specific purpose and interacts only with the layers directly above and below it, allowing different network technologies to interoperate by providing standard interfaces between disparate systems and simplifying both network design and troubleshooting.

**Opportunistic Networking**: A type of networking where devices communicate whenever they are within range of each other, useful in areas with intermittent connectivity.

**Oracle**: A bridge that retrieves external data or fulfills requests like API calls (usually both still centralized even in the case of a Decentralized Oracle Network (DON)) to feed information to decentralized infrastructures, enabling them to make automated decisions with this external data.


## P 

**Packet**: A network packet is a unit of data that consists of headers, that specify routing and other kinds of information, and content. A packet is made up of text-based headers and then either text or binary data (0's and 1's).

**PatchWork**: A secure, distributed social network built on the peer-to-peer Secure Scuttlebutt protocol, designed to work with or without internet access.

**Peering**: The voluntary interconnection of administratively separate networks for the purpose of exchanging traffic between users of each network.

**Peers**: A specific type of node that has an equal relationship with other nodes. They can communicate directly with each other and share resources or data. All peers are nodes but not all nodes are peers.

**Peer-to-peer (P2P)**: A distributed application architecture in which computers can connect to each other, and share information and resources directly over a local network or the internet, without relying on a central server

**Permissioned**:

**Permissionless**:

**Proof of Work (PoW)**: A consensus mechanism that requires miners to perform resource-intensive computations, effectively solving a cryptographic puzzle, in order to create a new block and have it accepted by the network.

**Proof of Authority (PoA)**: This mechanism relies on pre-selected, trusted entities to validate transactions. It's often used in private blockchains. Example: PALM sidechain, Flow (with additional PPoS functions).

**Proof of Staked Authority (PoSA)**: Combines elements of Proof of Authority (PoA) and PPoS, where validators are chosen based on their stake and identity/reputation. Example: Binance blockchain

**Proof of Space/Proof of Capacity (PoC)**: Leverages verifiable functions that demonstrably require significant storage allocation. Nodes competing for block creation submit proofs demonstrating their storage capacity, with higher capacity increasing their chance of selection. Example: Chia blockchain

**Proof of Space Time (PoST)**: Building on PoC, requires users to not only have storage but also prove they've kept data there for a specific time. Example: Filecoin blockchain

**Pure Proof of Stake (PPoS)**: Selects validators based on the proportion of tokens they hold and are willing to "stake" or lock up, without requiring delegation or election by token holders. It aims for simplicity and direct participation in the consensus mechanism. _Example: Algorand and Ethereum_

**Private Key**: The part of a keypair that is used to create signatures and should be kept secret

**Protocol**: A set of well-defined rules for how data is sent and received between computers

**Public Key:** The part of a keypair that can be used by others to verify a signature

**PubSub (Publish-Subscribe)**: A messaging pattern where senders (publishers) categorize messages into classes that subscribers can register interest in, enabling loosely coupled systems in distributed architectures.


## Q 

**Quick UDP Internet Connections (QUIC)**:  Uses multiple, speedy UDP connections but in a manner that is reliable and accurate, like TCP

**Quorum**: The minimum number of participants that must agree for a decision to be valid in a decentralized system.

## R

**Radio Mesh Networks**: Networks that use radio technology to connect nodes without requiring fixed infrastructure, often employed in disaster response or rural connectivity.

**Replication**: The process of creating and maintaining multiple copies of data in different locations on a network.

**Relay**: A node that helps connect users who cannot directly connect to each other in a peer-to-peer network.

**Router**: Routers are devices used to connect different networks and route traffic in between them. Routers direct IP packets, the pieces of data that make up internet traffic, from one network to another.


## S

**Secure Scuttlebutt (SSB)**: A peer-to-peer communication protocol, mesh network, and self-hosted social media ecosystem

**Secure HTTP (HTTPS)**: Not an acronym and is defined as securing HTTP connections by means of the cryptographic protocol Transport Layer Security

**Seeding**: sharing the parts of the file you've already downloaded, helping other users in the network download the data faster.

**Seedphrase/mnemonic phrase**​​​​​​​: A human-readable version of private key to a digital wallet, typically consisting of 12 or 24 "randomly" chosen words.

**Self-hosted**: Software or services that users install and operate on their own hardware rather than relying on third-party providers, enhancing control and privacy.

**Self-Sovereign Identity (SSI)**: A particular model of identity in which subjects of identity are able to express their identities autonomously and to control their identities on their own terms when interacting & communicating with other subjects irrespective of context.

**Server**: Nodes that provide services over a network are called servers. A server is a node that accepts connections from other nodes on a network and usually transmits, receives, or processes information as a service or application.

**Sharding**: A database partitioning technique used to improve scalability by dividing the network into smaller parts called shards.

**Sidechain**: a separate blockchain that runs in parallel to a main blockchain, allowing for increased scalability and experimentation while still being securely attached to the main chain through two-way pegging. Unlike layer two solutions that operate on top of the main chain, sidechains are independent blockchain networks that can have different rules, consensus mechanisms, and governance models, while still enabling the transfer of assets between the main chain and sidechain.

**Signed Data**: Data with an associated cryptographic payload that confirms the creator of the data also possessed the associated private key at the time the data was created

**Smart Contract:** Programs of any kind stored on a blockchain, such as Ethereum, Tezos, or Cosmos. Some blockchains such as Bitcoin do not support full smart contracts. Smart contracts often provide the foundation and logic for token creation and management​​​​​​​.

**Staking:** Staked cryptocurrency acts like a security deposit, incentivizing validators to behave honestly and contribute to the network's security. If validators behave dishonestly, they may lose some or all of their stake. On some networks, validators with larger stakes have a higher chance of being chosen to validate transactions and earn rewards.

**Store-and-Forward Networking**: A telecommunications technique where data is sent to an intermediate node where it's temporarily stored before being forwarded to the next node, useful in networks with intermittent connectivity.

**Sybil Attack**: An attack which disrupts a system by creating a large number of fake identities. This allows the attacker to unfairly influence the system through a swarm of seemingly legitimate accounts, manipulating voting power or flooding the network with noise.

**System**: A set of computers and software working together as parts of an interconnecting network



## T 

**Token**: Digital units of value that represent something/anything specific​​​​​​​

**The Onion Router (TOR)**: A network of virtual tunnels that allows people to improve their privacy and security on the internet by routing encrypted traffic through multiple servers.

**Torrent file**: A file that tells your computer the names, sizes, and verification hashes of the files you want to access via the BitTorrent protocol.​

**Transmission Control Protocol (TCP)**: Used to ensure the reliable sending and receiving of packets across the internet, but not necessarily in a timely way

**Transport Layer Security (TSL)**: A protocol that provides privacy for data in transit, the ability to authenticate the identity of communicating nodes, as well as a message integrity check to prevent undetected loss or alternation of data

**Two-Way Pegging**: The mechanism that allows digital assets to be moved between two separate but connected blockchains, such as a main 


## U 

**User Datagram Protocol (UDP)**: Prioritize speed by not worrying about the ordering of delivery of packets


## V

**Validator (PoS)**: Validators fulfil a role on a Proof of Stake network similar to the one Miners perform on a Proof of Work network, including validating transactions and securing the network, while earning additional cryptocurrency rewards for their participation.

**Virtual Private Network (VPN / aka proxy)**: A mechanism that provides a secure connection between two devices. VPN conceals network traffic and makes and receives DNS requests on your behalf. VPN providers know who you are, so a VPN doesn't provide total anonymity.


## W

**Wallet**: An off-chain mechanism, usually software such as a mobile app or browser extension, used for managing keys and interacting with a blockchain

**Web 1.0:** Host-generated content, host-generated authority. The browser-accessible internet before social media as we know it, consisting of individual websites that offered limited user interaction, primarily serving as one-way channels for information dissemination.

**Web 2.0**: User-generated content, host-generated authority. Content was user-generated and social interaction was now facilitated through centralized platforms that streamlined content creation. However, the shift in authority from individual hosts to these platforms raises concerns about user control over data and content.

**WebRTC**: A free, open-source project providing web browsers and mobile applications with real-time communication capabilities via simple APIs, enabling peer-to-peer connections without requiring plugins or downloads.

**Whisper**: A communication protocol in the Ethereum stack that allows for secure, low-level messaging between nodes.

## X

**XMPP (Extensible Messaging and Presence Protocol)**: An open communication protocol designed for instant messaging, presence information, and contact list maintenance, serving as the foundation for many decentralized messaging platforms.

## Y


## Z 

**Zero Knowledge:**


**51% Attack:** A single entity (or group) gains control of more than half of the mining hash rate or computational power of a blockchain. This dominance allows them to disrupt the consensus of a network



---

## Part 2. Common Marketing Terms in Dweb

**Cloud**: A marketing term used to refer to servers all around the world that are connected together across the internet 

**Certificate of Authenticity**: In most cases, smart contracts and subsequent tokens are not equivalent to a Certificate of Authenticity in the fine arts for many reasons, including their general lack of on-chain metadata to identify the work, and off-chain URIs, admin functions that allow mutable edits to the data.

**Decentralized**: Platforms and protocols claiming to be decentralized often rely on Web 2.0 infrastructure and centralization.

**Immutable/Immutability**: The false idea that transactions on a digital ledger cannot be altered. Smart contract vulnerabilities and admin functions are common, compromising the ideal of absolute immutability. Additionally, blockchain protocols can undergo soft or hard forks, altering how data is interpreted over time.

**Middlemen**: This term can unfairly diminish the value of curators, gallerists, and advisors. These arts workers offer specialized knowledge, navigating the intricacies of the art market and connecting artists with an audience.  Striving for complete autonomy might leave artists with the burden of marketing and selling their work, potentially hindering their artistic focus and overall success.

**On-Chain:** With the understanding that blockchains are not actually immutable, the importance of data being “on-chain” loses meaning. Even the most “on-chain” works of art are not completely on chain. _Example_: Autoglyphs is produced in ASCII and still requires a browser and off-chain instructions to properly render an image.

**Permanence/”Forever”**: A concept implying data will be immutably stored and accessible forever. However, the reality is more nuanced. While blockchain technology offers greater data resilience in theory compared to centralized servers, factors like protocol changes, storage costs, and network disruptions can still impact data accessibility in the long term.

**Provenance**: Marketed as an infallible record of ownership history, the actual effectiveness of blockchain for provenance hinges on data accuracy at the point of entry, which is deeply flawed.  Furthermore, challenges like forking, scalability limitations, and the potential for lost or inaccessible data raise questions about the long-term reliability of blockchain-based provenance.

**Royalties**: There have been aspirations to revolutionize arts monetization with automated royalty payments facilitated by smart contracts. However, current limitations exist.  Smart contracts lack built-in royalty protocols requiring additional extensions that require platform opt-in.  Creators are susceptible to royalty circumvention if platforms choose not to participate and through loopholes, such as token gifting and paying the transaction through alternative means, such as an additional transaction or off-chain in cash.

**Transparency**: Transparency is a cornerstone of distributed ledgers, with all transactions supposedly visible on a public ledger. However, achieving true transparency can be challenging. Anonymity features on many blockchains make it difficult to trace ownership and activity back to real-world entities. Additionally, the lack of standardized metadata, human-readable information about data, can hinder comprehension. While the ledger itself might be transparent, lack of metadata obfuscates traceability. Furthermore, there is the technique of “submarining” on IPFS, which makes access to data private and blockchains like Secret, which hide transaction data. 


**Web 3.0**: Often used as a marketing term to describe an evolving vision of a more decentralized internet than the host-generated authority of Web 2.0. However, the specific technologies and functionalities that define Web 3.0 are not well adopted at the protocol layer, making it more of an aspiration than a current reality.

__________________


## References

getdweb.net, decentpatterns.com, How The Internet Really Works (Article 19), Jolocom, Indigenous Data Sovereignty: Toward An Agenda, Wikipedia Computer Science, Jay Graber

_Last updated: 20 April 2025_
