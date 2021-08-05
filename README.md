# TRIPL: Experience, travel and leisure block-chain

TRIPL = smaRT TRaveL IndusTRy PRoTocoL

## Introduction

Hotel nights, flight seats, opera tickets and a place in an exotic expedition can be seen as NFTs.

## Actors

- Travelers
- Hosts (hotels, airlines, tourist attractions, guides, the ones giving the real experience to the traveler)
- Performers (musicians, guides, a person or a group of person that directly interact with travelers to give them an experience)
- Helpers (CRC services, translators, auto publishers for availability, any service needed by the hosts to create a better experience for the traveler)
- Reseller (travel companies, tour operators, bed banks, channel managers, the ones that facilitate the travel more on the side of communication, aggregation, APIs)

## Availability

Travel industry spends on availability calculations a lot. Over and over tons of CPU cycles are used to know the price of a room in Paris for the next week. This calculus takes a lot of parameters, mostly all commercial ones totally obscure for the traveler, like the discounts the middle man have, the taxes that needs to pay with the ten financial companies they uses to bill their clients which are doing a very similar calculus for the traveler.

An NFT distributed database will make all that obsolete. The availability and the price are always public.

In the most simple operation the _host_ publish what they want to sell and its price. The _traveler_ interact with the block-chain and get that price.

_Host_ can drop rooms at a fixed price or to an auction. They can also set if they are allowing re-sales and a fee for the resale. Of course, there will be cancellation fees.

## Privacy

All booking will remain anonymous. At the check in the user can show a confirmation code generated with their private key. The _host_ can have temporary access to the _traveler_ personal information to complete regulation.

Some services, like flights, requires some personal information in advance, like nationality. On this kind of services _hosts_ can specify which data can have last minute changes. Also, if the service requieres any data must be visible by the _host_ prior to the service the _traveler_ will know it before booking.

All bookings/transactions even between the same _traveler_ and _host_ will be anonymized. The host will not be able to track previous booking from the same traveler in the block-chain unless the traveler allow it (usually as part of some loyalty program) but, anyway, the relationship will be private in the block-chain.

## Taxes

The block-chain as a decentralized entity cannot retain any taxes. All prices in the block-chain are consumer prices. _Hosts_ and _helpers_ can generate invoices and taxes declaration based on the data in the block-chain. _Hosts_ can delegate this task to _helpers_ given them a restricted access to some data. _helpers_ can also deliver software that could be installed in the _hosts_ network to insure that any private data is never shared. _travelers_ can agree with the _hosts_ if their personal data can be shared with _helpers_ for certain purposes, like taxes.

Governments can see all transaction on the network. While the privacy is guaranteed for the _travelers_ open identity is a must for services providers in the network.

## Bundles & Auctions

A _hosts_ (an hotel, for example) can start a bid for a bundle (allotment) for the next summer season. _resellers_ can bid and then resell it at higher prices. _host_ will get the bid price and royalties of the subsequent sells.

## Private resale

Did you book a room for that Champions Final in Barcelona and your team did not get to final? Re-sale that room to a fixed price or in an auction! The _host_ will get a part but there will be no cancellation.

## Block-chain rewards and governance

### Travelers points

Travelers will earn _points_ by traveling, validating and reviewing _hosts_, _helpers_ and _performers_ to participate in the block-chain governance decisions.

### Host points

TBD

## Industry play or independent

We can make the travel industry a more fair one. Why traveling to xxx which is 10k km from home is cheaper than going to the country next to ours? Costs. Simple, but that implies that people get less for the same work.

# Road map & high level implementation details

## Road map

- Ideation, sharing: looking for people to join, criticize, grow the idea.
- Partnership: look for partners (mainly univerities, hotel chains, bed banks and distributors)
- Coin selection or creation
- Coding first versions on test networks.
- TBD

## TRIPL Coin

By this time you may want to know which crypto asset to buy because this project is amazing... Creating a crypto currency maybe required but it's not the only way. The network will have a reward system but it may be implemented in any existing coin. Services in this network should use any currency. Some _hosts_ may prefer BTC or ETH while other will tend to use USDT or BUSD. It should be possible to implement TRIPL with these or another coins. TRIPL coin may exist but **we prefer to define an excellent product with a clear market rules before choosing or creating a coin**.

## Identity

Any actor in the networks needs an identity. For travelers only a wallet address is enough. For _hosts_, _performers_, _helpers_ and _resellers_ some extra information is needed and must be validated to ensure the quality of service.
_hosts_ may also requires delegation of certain permission to their workers, _helpers_ and _resellers_.

## Host validation

A _host_ can be validated be a reseller (acting as a _helper_ for the block-chain) or by _travelers_. As any decentralized database, making sure that the service offered are real is a main concern. Actual travel industry players can be very use full to validate _hosts_.

## Objects

- Experience (a set of:)
- - Booking
- - - Accommodation
- - - - Hotel
- - - - Camping
- - - - B&B
- - - - AirBNB like
- - - - Couch
- - - - Bed
- - - Transport
- - - - Flight
- - - - Train
- - - - Car rental
- - - - Taxi, transfer
- - - - Bus
- - - Event (ticket)
- - - - Concert
- - - Food? Amenities?...
- Traveler
- Host
- Performer
- Helper
- Reseller

# Who we are

We are [this team](https://github.com/orgs/tripl-to/people) ... but we're looking forward more people to join us, come on!

## Why is this distributed as MIT

We are in the middle of a turn in history. A decentralised travel blockchain is inevitable, it's not about _if_ it's just about _when and who_. We hope we can help to create a fair one. One that warranties the freedom of host and travelers to offer and enjoy the best experiences.

We would love to send this idea to the European Research Found. That founds are giving priority to collaborative projects between universities and several companies. I truly believe that frameworks is the ideal to develop a new industry standard that will change how we buy and trade our travels. I still believe that big players can help to develop this faster but I'm not going to wait.

# Support

Who can you help this idea grow?

- Share it in the social media.
- Share it in your company, university...
- The idea is free to be copy and developed by anyone... and improved, of course, you can *send a PR!* if you want this document can be improve (We're sure of it)
