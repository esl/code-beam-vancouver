---
audience:
- intermediate
tags:
- BEAM
- concurrency
- processes
title: Concurrency, understanding the BEAM limits
speakers:
- _participants/lorena-mireles.md

---
The goal of this talk is to understand how the BEAM runtime works in order to make better design decisions in concurrent systems.

The BEAM is known for its powerful concurrency model based on lightweight processes; however, this doesn't mean that concurrency is infinite or cost-free. Starting with a brief historical overview, we will analyze why the model was designed this way and what the real costs associated with processes are (memory usage, garbage collection, etc).

The aim is to lay the technical foundation for maximizing the potential of the VM, understanding that, although concurrency in BEAM is easy and cheap to achieve, it is always limited by the actual capacity of the system.

**OBJECTIVES**
- Understand how the BEAM runtime works in order to make better design decisions in concurrent systems.

**AUDIENCE**
- For developers who already have experience with BEAM but have ever faced problems related to design and strange behavior, even when everything seems "correct".
