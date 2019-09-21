# Ether-1 Roadmap

## Ether-1 Team

[@Dev-JamesR](https://github.com/Dev-JamesR) - Founder & Lead Developer

[@FallenGravity](https://github.com/fallengravity)- Project Manager & Developer

[@Primate411](https://github.com/Primate411) - Project Manager, Documentation expert & Discord Management 

[Treehouse](https://twitter.com/Cryptomark9) - Project Manager & Discord Support

[Dylie](https://github.com/dylie) - Developer, Graphic Designer & Bot Manager

[CoachCryptos](https://twitter.com/CoachCryptos) - Social Media & Marketing Manager

[Houliboots](https://twitter.com/Top5Global) - Social Media & Marketing Manager

[Pistol](https://twitter.com/pistolcrypt) - Discord Moderator & Support

## Ether-1 Links

[Ether-1 Website](https://ether1.org)

[ethoFS - Website](https://beta.ethofs.com)

## Ether-1 Contact Emails:

[Admin](mailto:admin@ether1.org)

[Ethan/FallenGravity](mailto:ethan@ether1.org)

[Community](mailto:community@ether1.org)

---

## Roadmap

#### [IPFS & ethoFS on all node tiers](https://github.com/Ether1Project/ether1-node-scripts/pull/4) 

This WIP will add the ability for Service/Master/Gateway nodes to all run IPFS & ethoFS to support our global ethoFS network.

- Service Nodes: The SN will provide bandwidth to the ethoFS network by hosting DHTs (Distributed Hash Table) which will allow for a quicker connection to data hosted on ethoFS, SNs Acts as a data relay and secures the Ether-1 blockchain.

- Master Nodes: The MNs will act as a Bandwidth & Storage provider, MNs will host DHTs as well as store data hosted on ethoFS. MNs will also be responsible for processing power on ethoFS whilst further securing the chain.

- Gateway Nodes: Not much changes to the Gateway node, they provide: Processing power, Bandwidth, storage and the gateway to all data hosted on ethoFS.

**Expected Release Quater: Q4 2019**

#### [Decentralized Node Protocol](https://github.com/Ether1Project/Ether1/pull/10)

Decentralized Node-Protocol will remove all centralized aspects to node deployment, management, monitoring, and reward payment.

**Improvements/Protocol Overview:**

1. Node deployment/indexing will be via smart contract.

2. Node activity/availability will be verified at the time of reward payment via consensus protocol.

3. A random node will be selected & verified for payment at each block — addresses will be validated and scrubbed for a malicious activity via consensus.

4. Individual node status monitoring capability will be available via a local dashboard/front-end installed during node deployment.

The DNP is being utilized on the Ether-1 Production Testnet known as [Xerom](https://xerom.org), we’ve made significant progress & are happy to report it is nearly ready for activation on Ether-1.

**New Features:**
- Cross-platform Capabilities
- Custom API Port
- Custom Swarm Port

**Improvements:**
- Better Replication 
- Decerease in data usage
- Better Peer Discover and communication 

**Data Usage Decrease:**

V0.0.1 - 24 Hours (Service Node)
```
            rx      |     tx      |    total    
------------------------+-------------+---------
today     75.95 GiB |   63.15 GiB |  139.10 GiB 
```

V0.0.2 - 24 Hours (Service Node)
```
            rx      |     tx      |    total    
------------------------+-------------+---------
today     13.75 GiB |   25.99 GiB |   39.74 GiB 
```

71.43% decrease in data usage.

**Expected Release Quater: Q1 2020**

