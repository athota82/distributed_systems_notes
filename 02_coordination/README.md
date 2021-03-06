# Distributed Systems Notes

## Coordination

This chapter focuses on coordination strategies for computers in a distributed system. 

Unlike a multi-core processor in a single machine, there is no shared memory (or any other 
resource). So the algorithms described here focus on how to manage distributed state, ordering, 
and updates, that would otherwise be really easy on a single machine.

* Clock Synchronization
  * External Synchronization: Cristian's Algorithm
  * Internal Synchronization: The Berkeley Algorithm
* Logical Synchronization
  * Lamport Timestamps
  * Vector Timestamps 
* Leader Election
  * The Bully Algorithm
  * Ring Election: Candidate Replacement
  * Ring Election: Signup
  * **Election in Wireless Networks**
  * **Pitfalls of Leader Election and Relation to Consensus**
* **Notification Filtering**
  * **TODO**
* **Gossip Coordination**
  * **TODO**
* **Mutual Exclusion**
  * **Token Rings**
  * **Using Lamport Clocks**
  * **Performance Comparison**
  * **TODO**
  
**Bold indicates it's incomplete, but is planned/in progress**