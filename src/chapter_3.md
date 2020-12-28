# 3. Blockchain as a Distributed Ledger Technology 

We have seen how the field expanded considerably as the Bitcoin
project progressed. The emergence of new applications as well as
changes and extensions to the code led to the objectification of
Bitcoin's conceptual structure. Attention gradually shifted away from
the Bitcoin project as a whole and towards one of the technical
concepts underpinning it: blockchain.

This chapter explains how the success of Bitcoin actually led to the
objectification of blockchain technology, when the technical concept
that permitted the operation and administration of Bitcoin became an
object of study in itself. We then examine how the concept became
relevant to the handling of all types of transactions. Lastly, we look
at the ways in which industrial sectors have tried to adapt the
concept to their requirements by integrating other conceptual and
semantic changes -- from blockchain to distributed ledgers.

## 3.1. Other applications of the Bitcoin protocol 

Namecoin was the first project to use the Bitcoin protocol for a type
of asset other than money. In 203. a discussion took place on the
\#bitcoin-dev IRC channel regarding the possibility of using the
Bitcoin protocol to create a DNS system for generating domain names
that could circumvent the risk of the Bitcoin domain being censored,
as Wikileaks had been. The Namecoin code base consists of the Bitcoin
code base with some relatively minor changes and a few additional
features. In 2012, the American engineer J.R. Willett was seeking ways
of promoting greater acceptance of Bitcoin by the general public.
Rejecting the idea of creating a new cryptocurrency to compete with
Bitcoin, he designed a new feature within the Bitcoin protocol
intended to serve as a base on which everyone could build their own
currencies. Mastercoin software (today OmniLayer), which implements
this new feature, provides the tools required to design and publish
proprietary currencies with their own rules by configuring a new
token. The idea of layering other software on top of Bitcoin arose
from the custom of stacking protocols (for example, the HTTP protocol
is stacked on top of TCP/IP).

The concept of adding new layers to the Bitcoin protocol was then
tested for other applications. The challenge was to find ways of using
the Bitcoin protocol to represent other assets. These included
personalised currencies and financial products like Colourcoin,
property ownership (Smartproperty), and even contractual relationships
for executing clauses (Smartcontract) and the management of
organisations (DAOs). In 2013 the Colourcoin project published its
prospectus and described the situation in the following terms:

"The natural question is: is it possible to use the same functionality
for other applications as well? The answer, it turns out, is yes. The
fundamental innovation behind Bitcoin, that of using cryptographic
proof-of-work to maintain a secure distributed database, is good for
more than just the single limited-supply currency originally envisioned
by Satoshi Nakamoto in 2009; exactly the same technology can be used to
maintain ownership of company shares, 'smart property', alternative
currencies, bank deposits and much more. Anything which is representable
as a digital asset, and a 'rivalrous good', meaning that only one person
can own it at a time, is potentially fair game for representation in the
Bitcoin blockchain."

## 3.2. The objectification of blockchain 

In 2014, Vitalik Butarin, one of the authors of whitepapers for
Colored Coins, finalised the conceptualisation of Ethereum: a new
platform that used a more generalised scripting language than Bitcoin
and intended to facilitate decentralised application development.

Ethereum borrows most of Bitcoin's design concepts but operates on its
own network with its own protocol. It also has its own cryptocurrency,
called Ether.

Ethereum implements the smart-contract concept invented by Nick Szabo.
In this context, however, the term 'smart-contract' is somewhat of a
misnomer. It is actually a type of computer programme. Network users
can run the programme whenever they want as long as they pay the costs
of executing it. It can perform a variety of procedures, such as
notarial and financial contracts, equipment rental, or equity sharing.
The results, whether movement of Ethers or information storage are
held in a type of distributed database: a blockchain.

The blockchain is considered here to be a type of administrative
ledger that is not managed from a single point but is distributed over
the network. Despite this distributed architecture, the ledger
establishes and maintains the uniqueness of an asset, or any piece of
information for that matter. It establishes an inviolable link between
an object and its identifier. For example, it guarantees that a
Bitcoin has not been spent twice (the problem known as double
spending), or that a property asset or contract has not been forged or
registered twice. It is this technical characteristic that attracted
the attention of major industrial and financial players and resulted
in services being developed to meet the needs of specific industrial
sectors and groups.

For example, Ripple is a settlement infrastructure system that enables
payments to be sent and received without an intermediary, regardless
of their value or the financial institution. The project relies on a
database that records all the information from all Ripple accounts.
Financial transactions are verified, validated and compared in a
closed network of servers that can belong to anyone, including banks
and market players.

Another example is the Hyperledger project, a blockchain development
platform created in 2015. Hosted by the Linux Foundation, Hyperledger
was founded by major industry players such as IBM, Intel, Cisco
Accenture, and J.P. Morgan. Hyperledger aims to improve the
performance and reliability of blockchains and distributed ledger
techniques to enable them to handle global business transactions for
leading technology, finance, and supply-chain companies. The platform
combines a number of development structures (frameworks) and tools to
explore the capabilities of distributed ledger techniques when faced
with a wide variety of problems, such as those of supply chains and
digital identities. The goal of Hyperledger is to enable large
industrial companies to create blockchains that guarantee the
confidentiality of certain types of information. The Fabric project
was one of the first Hyperledger projects: a protocol for the
deployment and exploitation of permissioned blockchains. Like all
Hyperledger projects, Fabric is hosted by the Linux Foundation.
Members must abide by a code of conduct, and the protocol is shared
under a free opensource licence (an Apache 2 licence, which is
GPL-compatible).

## 3.3. The emergence of permissioned distributed ledger techniques 

In the Bitcoin and Ethereum blockchains, anyone can join the network.
This means that anyone can read and write transactions and take part
in validating them; the blockchain is considered to be public. In
2015, developments began that sought to create distinctions between
public, private and consortium blockchains.

In 2015, the family office R3 CEV (Crypto Consulting Exchanges
Ventures), chaired by David E. Rutter, a former Wall Street executive,
organised a number of roundtables for those working specifically on
blockchain projects such as Ripple, the beginnings of the Hyperledger
project as well as other major public and private players in the
banking industry like the Bank of England and Bank of America. These
roundtables were intended to examine the transformation of the finance
sector by cryptocurrencies. One of the issues discussed was how banks
could trade foreign currencies on community-managed ledgers, as in a
blockchain.

Following the roundtable discussions, R3 published an article
summarising the lessons learned: *Consensus-as-a-Service: A Brief
Report on the Emergence Of Permissioned, Distributed Ledger Systems*.
The article raised the issue of permissions, i.e., the ways in which
transactions are validated, differentiating between Bitcoin and
distributed ledgers. For the author, distributed ledger models like
Hyperledger and Ripple solved some of the problems associated with
Bitcoin and Ethereum in that the information was managed by an
identified community and authenticated using a permission system. The
author, Tim Swanson, concluded that this capacity enabled the various
distributed ledgers to be interoperable.

The article laid the foundations for differentiating between
permissioned and permissionless blockchains, and also examined the use
of private blockchains (Table 12). Unlike Ethereum and Bitcoin,
so-called closed blockchains are forms of centralised ledgers, the
decision-making powers for which are centralised within a single
organisation. They can be used to test new techniques and increase
expertise in this area. A consortium blockchain is a closed network
that is partially decentralised and requires permission from members
to join it. The power to audit it can be reserved for members and
decisions regarding it are taken by this closed community. This aspect
of permissioned blockchains serves to keep certain information
confidential. The model is intended to prevent inappropriate sharing
of customer information in that not all transactions can be shared
with all network participants.

Table 12. Permissioned and permissionless public and private
blockchains.

+----------------------+----------------------+----------------------+
|                      | **Permissionless**   | **Permissioned**     |
|                      |                      |                      |
|                      | (no restrictions for | (transaction         |
|                      | validators)          | validation is        |
|                      |                      | limited to specific  |
|                      |                      | users)               |
+======================+======================+======================+
| > **Public**         | All users can read   | All users can read   |
| >                    | transactions         | transactions         |
| > (No restrictions   |                      |                      |
| > on reading         | All users can        | Only certain users   |
| > blockchain         | validate             | can validate         |
| >                    | transactions         | transactions         |
| > data)              |                      |                      |
+----------------------+----------------------+----------------------+
| **Private**          | Transactions can     | Transactions can     |
|                      | only be read by      | only be read by      |
| (Direct access to    | selected users       | selected users       |
| blockchain data is   |                      |                      |
| limited to specific  | All users can        | Among these users,   |
| users)               | validate             | only those with      |
|                      | transactions         | specific permissions |
|                      |                      | can validate         |
|                      |                      | transactions         |
+----------------------+----------------------+----------------------+

R3 sent this paper to the banks with which it regularly worked,
garnering a good deal of attention. In 2015, R3 and nine major
financial players (Barclays, Commonwealth Bank of Australia, Credit
Suisse, Goldman Sachs, J.P. Morgan, Royal Bank of Scotland, State
Street, and UBS) founded an interbank consortium called the
Distributed Ledger Group (later to take on the name R3). Between 2015
and 2018, nearly 200 major players in industry and finance joined the
consortium. They included Bank of America, Thomsons Reuters, Société
Générale, UniCredit, BNP Paribas, Toyota Financial Services, and the
Bank of Canada.

The intention of this consortium was to create a framework, based on
the Hyperledger model, for the development of distributed consortium
ledgers in order to share information between companies in the banking
sector. In 2016, the consortium announced the Corda software project,
designed to record, execute, and manage the financial arrangements of
companies within a community of financial institutions. The platform
was also intended to be used to launch financial applications for a
number of markets, including foreign exchange and loans.

In 2016, the consortium announced that the source code for the Corda
software was to be shared under the same licence as that of the
Hyperledger projects: Apache 2.0. The use of this license demonstrated
the formal rapprochement between the two projects, with Corda becoming
a Hyperledger project, though remaining distinct.

Some members left the consortium to develop their own networks. In
2017, J.P. Morgan left the Hyperledger and Corda consortiums to
develop Quorum, which was presented as a 'permissioned implementation
of Ethereum supporting data privacy'. Quorum might be called a hybrid
blockchain, in that it combines several characteristics of public and
private blockchains. Like Ethereum, Quorum is shared on Github and
under a free GPL (General Public Licence). Quorum determines which
information should remain private and which information can be made
public. Instead of transactions being shared privately within a
consortium, they could now be displayed in other blockchains, such as
Bitcoin. This feature enabled companies to use a number of ledgers and
to selectively share information in the course of their business
operations.

## 3.4. Other distributed ledger techniques 

A dissection of the issue of distributed ledgers reveals that
blockchain is not the only technique that can be used. The majority of
distributed ledger implementations, like Bitcoin and Ethereum, are
based on a blockchain, whether closed or consortium, such as
Hyperledger or Corda, but other techniques have also been explored.
The differences can include the ways in which transactions are stored
in the ledgers, or the transaction validation rules themselves.

For example, the Internet of Things Application (IOTA) is a
distributed ledger that is not based on a blockchain, but on an
open-source experimental protocol known as The Tangle. IOTA aims to
provide a secure payment method for transactions between different
devices connected via the Internet (the Internet of Things). It is
designed to process micropayments and payments between devices,
creating an entire machine-to-machine micro-economy. The very large
number of possible transactions between connected objects in the IOTA
project requires a highly scalable architecture, which is difficult
for blockchains to achieve.

Other experiments exist, such as the Hashgraph, another patented
distributed ledger technique. Hashgraph is based on consensus and
information-sharing techniques that differ from blockchain: the
so-called 'Gossip about Gossip' technique. Hashgraph uses
information-sharing and polling techniques that demand network
participants share all their information, meaning that all
participants are aware of all the information that has been created
since the outset.

