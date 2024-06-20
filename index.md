<!-- # 1st Workshop on Distributed Computing with Emerging Hardware Technology -->

<!-- ### In conjunction with [PODC'24](https://www.podc.org/podc2024/), Nantes, France, June 17-21, 2024 -->

### June 21th, 2024. Colocated with [PODC'24](https://www.podc.org/podc2024/) and [SPAA'24](https://spaa.acm.org/). Nantes, France.

## Overview and scope

EMERALD aims at investigating how the utilization of future and emerging hardware technology can influence (or add to) the foundations of concurrent and distributed computing. The workshop will host a series of invited talks which will contribute to the better understanding of how such technology could change what we know about concurrent and distributed algorithms and models. The emphasis will be on persistent memory computing, NUMA-aware computing, distributed computing in systems with Remote Direct Memory Accesses (RDMA), distributed and concurrent computing on top of heterogeneous hardware, processing in memory (PIM), near-memory processing (NMP), disaggregated/composable systems, and others. 
The topics covered by EMERALD specialize the following broader topics for systems that feature modern, emerging or future hardware technology:

- concurrency, synchronization, and persistence 
- design and analysis of concurrent and distributed algorithms
- distributed and concurrent data structures
- fault-tolerance, self-organization, and self-stabilization
- lower bounds and impossibility results for distributed computing
- multiprocessor and multi-core architectures and algorithms
- transactional memory

Through a carefully-chosen collection of invited talks, EMERALD aspires to reveal realistic and practical aspects that can positively influence theory research, in whatever regards the choice of the problems to work on, the right level of abstraction to study them, how to come up with realistic models for computation, how to efficiently support additional desirable features (persistence, NUMA-awareness, architecture-specific design) when designing concurrent and distributed algorithms, while maintaining or improving their performance characteristics, etc. 
EMERALD will be a full-day event.  In addition to hosting lectures by invited speakers, it will feature an open discussion session aiming at highlighting important problems for future research. 


## Speakers

- **João Barreto**, University of Lisbon and INESC-ID, Portugal

- **Gregory Chockler**, University of Surrey, UK

- **Denisa-Andreea Constantinescu**, EPFL, Switzerland

 - **Naama Ben David**, Technion, Israel

- **Panagiota Fatourou**, University of Crete and FORTH, Greece

- **Phillip Gibbons**, Carnegie Mellon University, US

- **Wojciech Golab**, University of Waterloo, Canada

- **George Hodgkins**, University of Colorado, Boulder and Sandia National Lab, US

- **Eleni Kanellou**, FORTH ICS, Greece

- **Jim Larus**, EPFL, Switzerland

- **Roberto Palmieri**, Lehigh University, US

- **Erez Petrank**, Technion, Israel

- **Paolo Romano**, University of Lisbon and INESC-ID, Portugal

- **Eric Ruppert**, York University, Canada

- **Samuel Thomas**, Brown University, US

- **Gala Yadgar**, Technion, Israel




## Program

The workshop takes place on June 21st, 2024. 

| Time  | Activity  |
|---|---|
| 9:00–10:40 <br/> Session 1 |	**Persistent Computing – Theory, Algorithms, Data Structures<br/>Session Chair: Maurice Herlihy** <br/> 1. **Wojciech Golab**: How Persistent Memory Changed Distributed Computing Theory<br/> 2. **Erez Petrank**: The Persistence Bug: Dead or Alive?<br/>3. **Panagiota Fatourou**: Persistent Data Structures: The principles that govern their design<br/>4. **Eleni Kanellou**: The Power of Software Combining in Persistence<br/>5. **Eric Ruppert**: When is Recoverable Consensus harder than Consensus? |
| 10:40–11:00 |	**Coffee Break I** |
| 11:00–12:20<br/> Session 2 | **Hardware-Aware/Accelerated/Supported Distributed Computing<br/>Session Chair: João Barreto**<br/>1. **Roberto Palmieri**: Synchronization using RDMA: High Performance, Programmability, and Scalability<br/>2. **George Hodgkins**: LOCO: Building Applications in Network Memory with Cross-Node Objects<br/>3. **Jim Larus**: Hardware-Accelerated, Fine-Grain BSP<br/>4. **Denisa-Andreea Constantinescu**: Neuro-Inspired Edge AI Architectures for Distributed Federated Learning |
| 12:40–13:50 |	**Lunch** |
| 13:50–15:30<br/> Session 3 | **Memory & Storage – Systems, Practice, Applications<br/>Session Chair: Erez Petrank**<br/>1. **Naama Ben-David**: The Effects of Fast I/O on Concurrent Computing<br/>2. **Gala Yadgar**: Who moved my cheese? How storage systems deal with changes in their media<br/>3. **Gregory Chockler**: Mangosteen: Fast Transparent Durability for Linearizable Applications using NVM<br/>4. **João Barreto**: Persistent hardware transactions can scale <br/>5. **Samuel Thomas**: Rethinking Secure NVM in the Age of CXL |
| 15:30–15:50 |	**Break** |
| 15:50–16:30<br/> Session 4 | **Processing in Memory<br/>Session chair: Panagiota Fatourou**<br/>1. **Phillip Gibbons**: Processing-in-Memory: Theory and Practice<br/>2. **Paolo Romano**: Transactional Memory for Processing-In-Memory Systems: a Software-based Implementation for the UPMEM platform |
| 16:30–18:00 | **Discussion Session - Panel** |



## Talks

<table>
    <tbody>
{% include_relative talks/barreto.html %}
{% include_relative talks/chockler.html %}
{% include_relative talks/constantinescu.html %}
{% include_relative talks/david.html %}
{% include_relative talks/fatourou.html %}
{% include_relative talks/gibbons.html %}
{% include_relative talks/golab.html %}
{% include_relative talks/hodgkins.html %}
{% include_relative talks/kanellou.html %}
{% include_relative talks/larus.html %}
{% include_relative talks/palmieri.html %}
{% include_relative talks/petrank.html %}
{% include_relative talks/thomas.html %}
{% include_relative talks/romano.html %}
{% include_relative talks/ruppert.html %}
{% include_relative talks/yadgar.html %}
    </tbody>
</table>






## Organization committee

- Iris Bahar, Colorado School of Mines, USA
- João Barreto, INESC-ID, Portugal
- Panagiota Fatourou, University of Crete and Foundation for Research and Technology – Hellas
(FORTH), Greece
- Maurice Herlihy, Brown University, USA
- Erez Petrank, Technion, Israel

Contact: Panagiota Fatourou <faturu@ics.forth.gr>



