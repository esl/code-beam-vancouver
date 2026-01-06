---
level:
- Intermediate
tags:
- GraphQL
- Spark
title: Sparking Joy - Tidying up GraphQL schemas with custom DSLs
speakers:
- _participants/nicholas-geraedts.md

---
DSLs are a common tool in programming narrow down complex concepts into digestible pieces. We often use them without thinking of them as DSLs, but chances are most Elixir codebases will interact with DSLs one way or another - Ecto, Plug, and even CSS.

At Hiive, we’ve used GraphQL to power our frontends place since inception. Our schemas have grown organically with the business, but have also grown somewhat unwieldily. We used the power of Spark (the library that makes Ash work) to provide some opinionated guardrails, improve our error handling, tidy up our schema definitions, and improve developer joy.

**OBJECTIVES**
- A primer on Spark, the library that powers Ash DSLs, and hopefully to inspire more people to build small DSLs to simplify their developer experience.

**AUDIENCE**
- Developers, managers.
