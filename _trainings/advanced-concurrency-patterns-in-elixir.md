---
experience:
- Intermediate
title: "Advanced Concurrency Patterns in Elixir"
type: training
venue: TBC
trainers:
- _participants/andrea-leopardi.md
event_date: 24 March 2026

---
In this tutorial, we’ll explore advanced concurrency patterns and building blocks that help you design systems that scale, stay responsive under load, and shut down gracefully.

Like any respectable OTP concurrency training, we'll start from GenServer, but we'll mostly focus on when it's *overkill* (and `Agent` or `Task` are better) and when it *hits its limitations*.

Then, we'll look at `gen_statem`, a more powerful alternative to GenServer.

After that, we'll switch to scalability. We’ll look at tools such as `PartitionSupervisor` and `Registry`, and discuss when and how to use lower-level primitives like atomics, counters, and `persistent_term` to optimize performance.

We’ll also dive into process pooling strategies, both built-in and using external libraries (`nimble_pool`).

Finally, we’ll cover graceful shutdown and lifecycle management: designing supervision trees deliberately and architecting them for graceful shutdown.

This is an intermediate-level tutorial for developers who are already comfortable with Elixir’s basics and want to go beyond process/message passing or run-of-the-mill GenServers, focusing instead on the kinds of concurrency patterns that draw many people to Elixir in the first place.
