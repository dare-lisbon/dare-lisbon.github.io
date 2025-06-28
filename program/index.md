---
layout: home
---

DARE 2025 focuses on techniques for supporting highly available distributed systems. 
The school combines theory and practice. 
Through lectures by active researchers in the field, 
students will get acquainted with state-of-the-art techniques and the latest research advances. 
Moreover, in hands-on sessions, students can also develop and experiment with existing frameworks.

### Lecturers and Topics

**Nuno Preguiça - The Quest for “Optimal” Conflict Resolution**

In this lecture we focus on the problem of conflict resolution in the context of data management systems. We overview different contexts in which conflict resolution is a key issue, from groupware to geo-replicated and local-first systems, and discuss the requirements and techniques used, from simple last-writer-wins registers to CRDTs.

**Ragnar Mogk - Protocol RDTs: Programs as Replicated Data**

Protocol RDTs extend the concept of replicated data types by treating programs—not just data—as the replicated entity. This approach captures both state and behaviour, enabling systems to enforce application-level correctness under weak consistency. The talk presents the foundations of Protocol RDTs and demonstrates how they enable expressive, coordination-free distributed programming.

**José Orlando Pereira - Highly Available Analytical Processing**

State-of-the-art analytical processing relies on advanced query optimisation and parallelism across processors and clusters. Meanwhile, geo-distributed and local-first systems achieve high availability by encapsulating eventual consistency in replicated data types. However, these approaches are difficult to combine, limiting analytical performance on highly available data. This talk offers a hands-on introduction to analytical processing and Conflict-free Replicated Data Views as a solution for enabling high-performance analytics under high availability.

**Alexey Gotsman - Database Isolation Levels**

Transaction isolation specifications determine which database states transactions can observe during their execution, and thus, which results queries are allowed to return. This isolation corresponds to the letter "I" in the famous ACID acronym. Different "ACID" systems actually provide a spectrum of isolation levels, which expose the concurrency inside the database to the application programmer to a lesser or greater extent. Examples of such levels are serializability, snapshot isolation, and read committed.

Historically, the definitions of isolation levels have often been ambiguous or tied to database implementation internals. As a result, transaction isolation remains a difficult topic even for seasoned database professionals. This is a problem because understanding the isolation level provided by a given database is necessary to use it correctly. In this tutorial, I will explain the concept of transaction isolation and highlight pitfalls to be wary of when navigating the spectrum of isolation levels while also explaining some of the levels provided by modern database systems.

**Burcu Kulahcioglu Ozkan - Testing Distributed System Implementations**

Distributed systems are difficult to design, implement, and test. They must ensure correctness in the concurrent execution of a distributed set of processes, different delivery orderings of asynchronous messages, and in the existence of network and process failures. Unforeseen interleavings of concurrent events and faults can result in expected malfunctioning or outages, and it is important to detect and diagnose them. In this tutorial, we will discuss concurrency and fault-tolerance bugs in distributed systems and introduce state-of-the-art testing techniques for efficiently detecting concurrency and fault-tolerance bugs in distributed system implementations.

**Guido Salvanechi - Taming the Distributed Systems Beast with Programming Languages**

Distributed systems are notoriously hard to design, implement, and deploy. In this talk, we argue that programming languages are a fundamental tool to tackle the complexity of distributed systems.
We first discuss concrete examples of how abstractions offered by programming languages have been fundamental in solving problems in distributed systems. Then we discuss recent research results in this area, such as abstractions for data consistency and behavioral types for distributed applications. Finally, we outline promising research directions.
