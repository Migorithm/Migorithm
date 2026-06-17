## Migo 
Show-off or self-reflection? Somewhere in between. 
I care more about the process of understanding a system than the result of shipping it. 
If that sounds counter-productive, you might want to skip me over.

*Consensus · replication · failure detection · partitioning & sharding · event-driven & CQRS messaging · log-structured storage.*


#### Rust — Distributed Systems
- [EastGuard – Zero-controller distributed messaging built for the scale that breaks Kafka](https://github.com/f-rustrated/EastGuard)
  - Metadata sharded across many small Raft groups, so coordination throughput scales with the cluster instead of funneling through a single controller
  - SWIM gossip for decentralized, O(log N) failure detection — no central heartbeats, no heartbeat storm
  - Dynamic ranges that split and merge with load; segments striped across nodes for automatic balancing
  - Seal-on-failure replication in place of Kafka's ISR — seal the segment, reopen on a healthy replica set, treat sealed data as immutable
- [Duva – Strongly-consistent distributed key-value store](https://github.com/Migorithm/duva)
  - Replicated storage designed around correctness under node and network failure
- [Ruva – Event-driven framework](https://github.com/Migorithm/ruva)
  - Message-driven core, async end to end
- [CQRS / Event-Sourcing Framework](https://github.com/Migorithm/cqrs)
  - Command/query separation with an append-only event log as the source of truth


#### Python — Architecture & Patterns
- [IAM](https://github.com/Migorithm/IAM) — identity & access management service
  - Event-driven architecture
  - Domain-Driven Design
  - Async-first

#### DevOps & GitOps
- [GitOps Setup](https://github.com/Migorithm/gitops)
  - [Kubernetes Basics](https://github.com/Migorithm/kubernetes-basic)
  - Docker, ArgoCD, SealedSecrets, LetsEncrypt
 





<br><br>

<div align=center>
  
  ![Migorithm's Stats](https://github-readme-stats.vercel.app/api?username=Migorithm&theme=vue-dark&show_icons=true&hide_border=true)

  ![Migorithm's Streak](https://github-readme-streak-stats.herokuapp.com/?user=Migorithm&theme=vue-dark&hide_border=true)
  
  ![Migorithm's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Migorithm&theme=vue-dark&show_icons=true&hide_border=true&layout=compact)


  </div>

<br><br>


### Tech Blog
[Articles](https://www.linkedin.com/in/migo-lee/recent-activity/articles/)

### Contact
<p>
    <a href="https://www.linkedin.com/in/migo-lee-763874175/" target="_blank">
        <img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height="30"/>
    </a> 
</p>








<!---
Migorithm/Migorithm is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
