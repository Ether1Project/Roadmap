# Ether-1 Roadmap

## Ether-1 Team

[@Dev-JamesR](https://github.com/Dev-JamesR) - Founder & Lead Developer

[@FallenGravity](https://github.com/fallengravity)- Project Manager & Developer

[@Primate411](https://github.com/Primate411) - Project Manager, Documentation expert & Discord Management

[Treehouse](https://twitter.com/Cryptomark9) - Project Manager & Discord Support

[@Dylie](https://github.com/dylie) - Developer, Graphic Designer & Bot Manager

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

* * *

## Road Map at a glance

-   [x] IPFS & ethoFS on all node tiers - Completed (Released on 10/06/2019)

-   [ ] Decentralized Node Protocol - Q1 2020

-   [x] ethoFS Dashboard - Completed (Released on 10/06/2019)

-   [ ] Website Revamp - Q1 2020 (latest)

-   [ ] Decentralized On-Chain Governance - N/A

-   [ ] Orbit DB - N/A

## Roadmap

#### [IPFS & ethoFS on all node tiers](https://github.com/Ether1Project/ether1-node-scripts/pull/4)

This WIP will add the ability for Service/Master/Gateway nodes to all run IPFS & ethoFS to support our global ethoFS network.

-   Service Nodes: The SN will provide bandwidth to the ethoFS network by hosting DHTs (Distributed Hash Table) which will allow for a quicker connection to data hosted on ethoFS, SNs Acts as a data relay and secures the Ether-1 blockchain.

-   Master Nodes: The MNs will act as a Bandwidth & Storage provider, MNs will host DHTs as well as store data hosted on ethoFS. MNs will also be responsible for processing power on ethoFS whilst further securing the chain.

-   Gateway Nodes: Not much changes to the Gateway node, they provide: Processing power, Bandwidth, storage and the gateway to all data hosted on ethoFS.

**Expected Release Quarter: Q4 2019**

* * *

#### [Decentralized Node Protocol](https://github.com/Ether1Project/Ether1/pull/10)

Decentralized Node-Protocol will remove all centralized aspects to node deployment, management, monitoring, and reward payment.

**Improvements/Protocol Overview:**

1.  Node deployment/indexing will be via smart contract.

2.  Node activity/availability will be verified at the time of reward payment via consensus protocol.

3.  A random node will be selected & verified for payment at each block — addresses will be validated and scrubbed for a malicious activity via consensus.

4.  Individual node status monitoring capability will be available via a local dashboard/front-end installed during node deployment.

The DNP is being utilized on the Ether-1 Production Testnet known as [Xerom](https://xerom.org), we’ve made significant progress & are happy to report it is nearly ready for activation on Ether-1.

**New Features:**

-   Cross-platform Capabilities
-   Custom API Port
-   Custom Swarm Port

**Improvements:**

-   Better Replication
-   Decerease in data usage
-   Better Peer Discover and communication

**Data Usage Decrease:**

V0.0.1 - 24 Hours (Service Node)

                rx      |     tx      |    total    
    ------------------------+-------------+---------
    today     75.95 GiB |   63.15 GiB |  139.10 GiB

V0.0.2 - 24 Hours (Service Node)

                rx      |     tx      |    total    
    ------------------------+-------------+---------
    today     13.75 GiB |   25.99 GiB |   39.74 GiB

71.43% decrease in data usage.

With DNP we can introduce support for Windows, Darwin & ARM Nodes - though it was previously not a priority, you can read [this](https://) article for a better understanding of why we've introduced cross-platform ethoFS.

**Release Date: 10/06/2019 - [Trinity](https://medium.com/@Ether1Official/ethofs-on-all-nodes-its-here-1ffcadf763e) **

* * *

#### ethoFS Dashboard

For a while, we’ve felt that the ethoFS upload dashboard was not in line with the rest of our branding and UI style, FallenGravity has been working to push the entire ethoFS.com to upgrade out. If you’d like to test out the dashboard it is available here: <https://beta.ethofs.com/>

Another Major reason this update & refresh was done was to allow for self-hosting of the dashboard. We take our motto of Decentralized Everything very seriously and the upload dashboard as been hosted by the Ether-1 team since the initial release of ethoFS and this made it a possible point of failure, by allowing the user to host a local copy of the dashboard we’ve lived up to our motto. If you’d like to host a copy of the ethoFS dashboard you can follow this guide: <https://docs.ether1.org/ethofs/how-to-host-your-own-ethofs-dashboard-at-home-on-macos>

**Release Date: 10/06/2019 - [Trinity](https://medium.com/@Ether1Official/ethofs-on-all-nodes-its-here-1ffcadf763e) **

* * *

#### [Website Revamp](https://github.com/Ether1Project/Roadmap/issues/2)

The Website Revamp will look at improving our SEO, Website UI & body copy.

**Expected Release Quarter: Q1 2020 (Latest)**

* * *

#### [Decentralized On-Chain Governance](https://github.com/Ether1Project/Ether1/pull/6)

This is currently on hold until the deployment of DNP, whilst the nodes still rely on the Ether-1 team for payments and activation we cannot implement a Decentralized governance model as it just doesn’t make sense. If you’d like to learn more about our Decentralized Governance or get involved in its creation by providing feedback you can do so here: <https://github.com/Ether1Project/Ether1/pull/6>

**Expected Release Quarter: Currently Unknown - Requires: ethoFS upgrade as well as DNP**

* * *

#### Community Suggestions for Roadmap items

| Name                                                                | Requester     | Status      | In-house/Out-sourced | Expected Release Quarter |
| ------------------------------------------------------------------- | ------------- | ----------- | -------------------- | ------------------------ |
| [Orbit DB](https://github.com/Ether1Project/Roadmap/issues/1)       | FallenGravity | Open        | N/A                  | N/A                      |
| [Website Revamp](https://github.com/Ether1Project/Roadmap/issues/2) | FallenGravity | In Progress | In-House             | Latest: Q1 2020          |
|                                                                     |               |             |                      |                          |
