# topos-aleo-connector

This is an exploration of what would be required to build a Topos&lt;-&gt;Aleo connector, and how that would work.

Topos ([https://docs.topos.technology](https://docs.topos.technology)) is a zkEcosystem that offers uniform security across its shards (called subnets), with provable state transition validity and state non-equivocation. It allows for seamless, trustless interoperability between different participants in the network (called subnets).

So, from within Topos, the capabilities provided by the various subnets become composable sets of functionality. It would be compelling to be able to have a dApp deployed within a Topos subnet that can seamlessly interact with Aleo and programs deployed on Aleo.

![https://docs.topos.technology/static/6f319961d29691a7ce586a8ca12863d6/f88f4/topos-components.png](https://docs.topos.technology/static/6f319961d29691a7ce586a8ca12863d6/f88f4/topos-components.png)

![https://docs.topos.technology/static/7eae492d8886c0901454d3b3b279734f/f88f4/cross-chain-transaction-swim-lane.png](https://docs.topos.technology/static/7eae492d8886c0901454d3b3b279734f/f88f4/cross-chain-transaction-swim-lane.png)