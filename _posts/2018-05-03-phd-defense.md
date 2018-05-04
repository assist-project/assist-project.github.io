---
layout: post
---

Andreas Löscher will defend his thesis _Targeted Property-Based Testing with Applications in Sensor Networks_ in Auditorium Minus, Gustavianum, Akademigatan 3, Uppsala, Thursday, 7th of June.

#### Abstract

Testing is a fundamental part of modern software development, as it unveils bugs in the system under test and gives confidence in their correctness. Testing is often a laborious task as it typically requires to write by hand a plethora of test cases to test a system thoroughly. This task can be aided by high-level testing techniques such as random property-based testing (PBT) where the testing task is reduced to specifying properties that the system under test is expected to satisfy, and generators that produce well-distributed random inputs to these properties. However, as with all random testing techniques, the confidence in the system and the chances of finding a bug is proportional to the number of tests. If the set of possible inputs is large, even a high number of tests does not yield a satisfactory result. One example is testing sensor networks, where one not only needs to produce the inputs for the software system but also needs to consider the network topology and the systems environment.

This dissertation presents targeted property-based testing, an enhanced form of PBT where the input generation is guided by a search strategy instead of being random, thereby combining the strengths of QuickCheck-like and search-based testing techniques. It furthermore presents an automation for the simulated annealing search strategy that reduces the manual task of using targeted PBT. We present concrete implementations for all presented techniques and a framework for PBT of sensor networks.

Applying PBT to testing sensor networks has allowed us to test relatively complex software and uncover subtle and hard-to-find bugs. We evaluate targeted PBT by comparing it to its random counterpart on a series of case studies. We show that its testing performance is significantly higher than that of random PBT. Furthermore, we demonstrate that the extra effort required to use targeted PBT is limited to specifying a test goal. With these results, we argue that targeted PBT improves the state-of-the-art of software testing and ultimately leads to higher confidence in complex software systems.
