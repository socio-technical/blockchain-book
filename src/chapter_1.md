#  1. Blockchain as a Historical Construct 

From the earliest days of computing, questions regarding the sharing,
reliability, auditability, and confidentiality of information have
been treated as strategic issues by governments, businesses, and
universities. Between 1950 and the 2000s, buoyed by military,
academic, and industrial research, taking place mostly in the United
States, these questions led to major technical advances as well as to
the commercialisation of computing. Blockchain forms part of this
historical continuum in terms of both technology and culture.

In this chapter we demonstrate that blockchain is a historical
construct. Technically speaking, it comprises a series of concepts
that were developed over the course of the history of computing. Here,
we present the chronological evolution of the reasoning behind
blockchain as well as the achievements that led to its consolidation.
We explore in particular the ways in which the essential technical
underpinnings of blockchain, namely, distributed cryptography and
distributed systems, were developed and tested, and how they
subsequently matured. We also explain the origins of certain
practices, rules, incentives, and behaviours that shaped the field.
The challenge we set ourselves is to bring together the initial
elements of an analytical framework for the field.

## 1.1. Cryptography and decentralised networks in the post-war period 

Cryptography is the art of protecting communications against
disclosure using keys or secrecy. Its use was an important facet of
the Enigma project during the Second World War. At the end of the war
the armed forces retained secrecy around the project, considering it
to be a strategically important asset. Confidential research was
conducted for the national intelligence agencies NSA and GCHQ to
develop information encryption systems capable of preserving the
confidentiality of electronic communications. In 1945, while
conducting research at Bell Industrial Laboratories, Claude Shannon
wrote a paper entitled *A Mathematical Theory of Cryptography*, which
was classified as secret by the

US government. He also addressed the issue of signal transmission in
his renowned work on the mathematical theory of communication. In
1949, Shannon published another paper entitled *Communication Theory
of Secrecy Systems*. There he laid the foundations for modern
cryptography, approaching the field from the perspective of
information theory for the first time. Also of interest is Horst
Feistel's research on encryption algorithms, which he completed while
working at IBM.

The problems associated with decentralising computer networks were
first addressed during the Cold War, notably with the development of
ARPANET in 1968. It is generally understood that, for reasons of
security, the US military authorities and their affiliated university
researchers designed a large network enabling computers from a large
number of universities as well as the research centres with which
DARPA worked, to communicate with each other. Technical and economic
considerations led them to develop a non-centralised network model
consisting of interconnected nodes. In this model, routers served as
gateways to transfer information between computers using the telephone
network. Some claim that Arpanet's decentralised structure was
intended to standardise connection techniques, while others argue that
it was designed to maintain the reliability of a network even when
part of it was damaged or destroyed.

In the early 1970s, the Network Working Group, an informal university
group which was to define ARPANET's peer-to-peer communication
protocols, developed the email system and the TCP/IP suite of
protocols (Transmission Control Protocol and Internet Protocol), in
order to transfer information securely between different computers
connected over a network. The increasing availability of personal
computers and microcomputing (e.g., the Hewlett-Packard 9100A and the
Apple II) for businesses and the general public opened up the
possibility of networking on a massive scale, a theme that was
explored by the Xerox Palo Alto Research Center.

## 1.2. Consequences of the growth of electronic communications 

The National Bureau of Standards, an agency of the United States
Department of Commerce, went on to employ Horst Feistel's research at
IBM and to adopt the Data Encryption Standard (DES) as the standard
for the corporate world. This is a symmetric-key algorithm in which a
single 56-bit key is used to

encrypt and decrypt messages. In response to this approach, Whitfield
Diffie and Martin Hellman of the University of Berkeley wrote the
foundational paper 'New Directions in Cryptography' in conjunction
with Ralph Merkel. In this paper, the authors develop the concept of
asymmetric cryptography. It is this encryption method, which
differentiates between public keys and private keys, that is used to
encrypt and decrypt transactions in a blockchain.

The significant success of this article within the scientific
community paved the way for many other works to be published in
specialised journals such as ACM and IEEE Journals. In 1978, a paper
written by Ronald Rivest, Adi Shamir, and Leonard Adleman at MIT
modelled an application for asymmetric cryptography using an
encryption algorithm called RSA. At around the same time Usenet, the
first network of forums organised into discussion groups, was
connected to ARPANET. With the rapid expansion of electronic
communications, researchers began to commercialise their work and file
patents, including DiffieHellman for key exchange and RSA encryption.

Conscious of the ever-increasing number of emails being sent across
the Arpanet network, researchers Zaw-Sing and Paul Mockapetris of the
University of Southern California set out the entire concept for the
implementation of a Domain Name System (DNS) in a series of classified
reports for DARPA. The architecture they designed involved a database
in which information was fragmented into small calculation units and
then distributed over several computers connected to each other
through the Arpanet network.

At that time, university research in the field of communications
focused mainly on issues specific to communications networks. At the
University of Berkeley, Leslie Lamport's work on the resilience of
networks with failed nodes and ways of addressing problems that arose
led him to come up with his much-quoted metaphor of the Byzantine
generals[^3]. One of the inventors of asymmetric cryptography, Ralph
Merkle, was working on a digital signature scheme. He created
cryptographic hashing and hash tree functions to digitally fingerprint
digital objects so they could be identified. This is the same method
that is used to structure information storage in a blockchain.

## 1.3. Designing privacy 

In the wake of the commercialisation of cryptography and the expansion
of the ARPANET computer network, cryptology began to be recognised as
a scientific domain in its own right. In 1982, the International
Association for Cryptologic Research at the University of California,
Santa Barbara, organised the Annual International Cryptology
Conference, one of the largest international conferences in the field.
At the same university, David Chaum was in the process of modelling a
network communications system in which messages were anonymised
through blind signatures and the links between their sources and
destinations obscured (known as mix networks).

Chaum was especially interested in privacy and the accessibility of
the personal information used in electronic financial transactions. In
an attempt to guarantee the confidentiality of financial transactions,
he designed and produced a cryptographic system in which neither banks
nor governments would be able to trace personal payments made online.
This model led to the creation of the eCash project, one of the first
attempts to launch a cryptographic electronic currency on the
international markets.

The question of the rights and the level of control that producers of
information have over their productions is also at the heart of the
creation of free software rights. While working at the Artificial
Intelligence Laboratory at MIT in 1983, Richard Stallman launched the
GNU project. Its aim was to develop an operating system that could
guarantee certain rights for its users. He announced the project on
the Usenet forum and invited others to take part in its development.

In order to enable people to make voluntary contributions to GNU,
Stallman asked lawyer Eben Moglen to formulate a legal text that would
standardise the extension of intellectual property rights. In 1989, he
published the first version of the General Public Licence (GPL), which
established new legal conditions for the freedom to operate, study,
modify, and distribute software. This licence forms the legal basis
for the distribution of most blockchains.

## 1.4. Consequences of public access to the global computer network 

As the ARPANET project came to a close at the beginning of the 1990s,
it ushered in public access to the global computer network through the
internet. At CERN in Geneva, Tim Berners Lee launched the HyperText
Transfer Protocol (HTTP) build on top of TCP/IP. This protocol would
lead to the development of a user-friendly World Wide Web browser
capable of providing access to different types of resources via a
single interface. The authentication and encryption protocol used to
protect payments made over the internet, Secure Sockets Layer (SSL),
was developed by the same company that produced the Netscape Navigator
browser. The SSL protocol was based on the RSA encryption algorithm.
The Internet Engineering Task Force (IETF) went on to add to the
development of SSL by creating the Transport Layer Security (TLS)
protocol.

Numerous new projects inspired by DNS architecture, including
Seti\@home and Folding\@home, tested the viability of distributed
computing. The results showed that a data analysis process that would
require a large amount of computing time for a single computer could
be done by distributing or sharing the work between a large community
of computers connected to each other through the internet.

'Strong' cryptography was still a classified research area. In a form
of 'cryptowar', the US government tried to restrict access to
cryptographic methods by both the public and other nations. Concerns
about the control of communications systems by state bodies were
widespread amongst US academics and computer-industry players such as
Intel and Sun. The debate centred around the export of encryption
technologies, in particular the RSA algorithm used in SSL, which was
heavily regulated at the time.

A form of information activism was beginning to emerge. Philippe
Zimmerman designed the PGP ('Pretty Good Privacy') encryption software
and distributed it under the GNU GPL licence (General Public Licence)
in order to ensure public access. Personalities such as Tim May, Eric
Hughes, and John Perry Barlow published texts such as *A Declaration
of the Independence of Cyberspace*, which contained strong political
messages regarding the need for information independence. Regular
meetings were held at Stanford, the cypherpunk collective was
established, and global discussion lists were created
(cypherpunksrequest\@toad.com). The Electronic Frontier Foundation was
set up as a lobbying force to defend the right to information privacy.
Between 1996 and 2000, under the Clinton administration, US
regulations on the use of cryptography were relaxed and then virtually
abolished.

At Bellcorp's Bell Laboratories, cryptographers Stuart Haber and Scott
Stronetta were developing a method for timestamping digital documents.
The challenge was to date the creation and modification of documents
with complete accuracy. The method was supplemented by a digital
signature scheme that could guarantee the integrity of an electronic
document and authenticate its author. Haber and Stronetta then set up
their own timestamping company, Surety, using the AbsoluteProof
software, which continues to provide cryptographic sealing for digital
documents. Every week since 1995, Surety has published all of its new
seals in a single signature in the 'Notices & Lost and Found' section
of the daily issue of *The New York Times*. The same method is used to
protect author rights in blockchains by creating proof of precedence.

In 1994, lawyer and computer scientist Nick Szabo began to publish a
series of papers about the concept of the Smart Contract. Szabo had
worked with David Chaum as a consultant on the eCash cryptographic
electronic currency project. His experience in the field led him to
develop ways of adapting specific commercial and contractual practices
to electronic commerce between individuals over the internet. His
premise was that many types of contractual clause, such as privileges,
guarantees, and ownership rights, could be converted into code and
executed automatically.

Nick Szabo conceptualised the computer protocols that would enable
several parties to a contract to observe its execution, check that the
agreed conditions had been met, disclose only those details necessary
for the execution, and, finally, reduce their costs by automatically
implementing the contract once all the criteria had been met. To
illustrate his concept, Szabo compared the operation of smart
contracts with that of vending machines that dispense a beverage when
the exact amount has been fed into the machine. Once the parameters
have been initiated, the smart contract runs automatically, regardless
of external events such as one of the parties changing their mind.

Cithy Dwork and Moy Naor of the IBM research division in San Jose
published a paper in the review of the Annual International Cryptology
Conference which presented a method for fighting spam and other
undesired electronic communications by asking the sender of the email
to provide proof that a certain algorithm had been executed. This is
called 'proof-of-work' and is based on the idea that some form of cost
should be incurred for the use of free online services such as email.
Inspired by their work, Adam Back posted a solution on the Cypherpunk
mailing list which could fight spam more effectively -- a
proof-of-work system he called Hashcash.

In 1989, David Chaum exploited the eCash patent through a company
called Digicash. In 1994 he introduced Digicash at the first
international World Wide Web conference in Geneva, in a talk entitled
'World's First Electronic Cash Payment Over Computer Networks'. With
the aid of financial players such as Credit Suisse, Deutsche Bank, and
the Mark Twain Bank, Chaum was able to experiment further with his new
centralised cryptographic money system. Digicash filed for bankruptcy
in 1998. Chaum put this down to the fact that his system had entered
the market before e-commerce had fully taken root on the internet.

Others would go on to design decentralised currency systems without
implementing them. These included Nick Szabo's BitGold, which
incorporated digital signatures, timestamping, and proof-of-work. We
can also cite Wei Dai's B-money, which he described as 'a scheme for a
group of untraceable digital pseudonyms to pay each other with money
and to enforce contracts amongst themselves without outside help'.

In the early 2000s, against a backdrop of increasing internet speeds
and a proliferation of access providers, computers and peripherals,
cryptography was fully declassified by Al Gore. Audio file-sharing
sites began to emerge, especially for music files. Napster enabled its
users to share music files in MP3 format by making a list of files
available on a server that could be searched and downloaded by anyone.
Only the downloading of files was decentralised. In March 2000, the
Gnutella protocol was created to allow objects to be searched and
retrieved without a central server.

Napster and Gnutella paved the way for further upheavals in the
cultural sector. Audio, video, and literary file-sharing services
using completely decentralised peer-to-peer systems, like Soulseek,
LimeWire, SETI, Bitorrent, and Tor took off. Media production and
distribution companies filed a plethora of copyright violation suits.
These early services were important driving forces in the evolution of
peer-to-peer systems.


[^3]: In computer science, the problem of the Byzantine generals is a
    metaphor that deals with the questioning of the reliability of
    transmissions and the integrity of interlocutors.

