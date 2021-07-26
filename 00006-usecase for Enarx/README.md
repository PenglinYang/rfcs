# 00006：Usecase for Enarx
* authors
* Status: 
* Since: 2021
* Status Note: initiate
* Start Date: 
* Tags: usecase
## Summary 
This document is used to introdue Enarx to different scenarios especially which have standards or universal architecture that can be referenced.
## Motivation
Since confidential computing is an emerging concept and solution for protecting data in use, it is crutial that this project can provide some convincing and instructional usecase to introduce to different industries. And these usecases can also promote the design of Enarx to fulfill general uses.
## Scenarios
### Scenario 1: MEC(Multi-access edge computing) with Enarx
In the MEC scenario, the edge computing infrastructure is deployed at the edge of network consumer. 
For example, an MEC platform could be deployed together with UPF(User Plain Function) beside a factory to support low latency applications. In addition, the architecture of MEC is based on NFV(Network  Function Virtualization), which is based on virtualization infrastructure like virtual machine and container. In this situation, the factory may want to make sure the edge computing environment is secure and the application context cannot be accessed by the operator. Enarx could be used to provide remote attestation and trust execution environment for this edge computing demand.

![image](https://user-images.githubusercontent.com/80935986/126958816-0e28b23c-88d7-4497-bc0c-6589e96c4448.png)

The above figure shows where the Enarx architecture could be deployed in MEC system. AS long as the Enarx client maintains the **session key(private key/toke?)** about the Enarx, it can fully trust the application and data which will not be leaked by MEC.
#### issues need to clarify:
* the workflow of key management
* the workflow of orchestrator
### Scenario 2: NFV based 5G Core Network deployed in public Cloud with Enarx
tbc

### Scenario 3: 


## References
* ETSI GS MEC 003 V2.2.1(2020-12)
* 
* 
