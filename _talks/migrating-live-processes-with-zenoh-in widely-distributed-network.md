---
level:
- intermediate
tags:
- Migration
- Distribution
- Zenoh
title: Migrating live processes with Zenoh in widely distributed network
speakers:
- _participants/yutaka-kikuchi.md

---
It is relatively easy to migrate running Elixir/Erlang processes between BEAM VMs on an Erlang Cluster. However, configuring an Erlang cluster across a wide-area distributed environment is not necessarily straightforward. For example, NAPT is troublesome.

Not only routers and firewalls, but also Carrier Grade NAPT (CGN), introduced by ISPs due to IPv4 address exhaustion, prevent clustering of BEAM nodes across different networks under different CGNs.

Industrial systems often employ the Publisher/Subscriber (Pub/Sub) communication method. Using Pub/Sub enables more flexible process migration on a widely distributed network. We demonstrate that using Eclipse Zenoh for Pub/Sub communication allows flexible migration of GenServer processes.

**OBJECTIVES**
- We want to demonstrate that the already highly convenient Elixir/Erlang processes can be even more convenient with Live Migration.

**AUDIENCE**
- Audience considering introducing Elixir in large-scale distributed environments. Particularly, those in industrial fields are planning to build systems using multiple clouds and mobile network MECs.
