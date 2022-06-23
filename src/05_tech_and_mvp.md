# Tech Stack & MVP

### Smart Contract Networks
Ethereum L1 EVM/Solidity w/outlook of a ZK Rollups playing an increasing role.

Despite the recent market downturn, I do feel Ethereum is where considerable resources and attention are and will be for many years.

The two potentially currently viable options for ZK Rollups are zkSync and StarkNet. Neither is ready for prime-time, but they probably will mature and become more production-ready in the time that it takes to develop Pipeline, at which point parts of the system could be migrated.

### Persistent Storage
During the production stage we'll mostly be dealing with digital deliverables, and we want to hedge against loss of artifacts. arweave is a solid pay-one-store-forever system, and the fees, compared to the project costs are negligible.

It would be absolutely affordable to publish all milestone deliverables on arweave to both keep the community in the loop wrt project progress and to make sure nothing is ever lost in an accident. 

Certain measures might be taken to restrict access to these resources, such as encryption that only allows actors involved in a specific project to view these artifacts. When the project is completed, this view access will be revoked. 

This doesn't prevent actors from downloading artifacts. Which, we might as well say, is by design since they're in one way or another are paying for the work to be done and as long as they do not circulate these artifacts outside of the community (we could have a EULA and digital fingerprinting in place to track such activity), we're fine.

### UI
React doesn't seem a bad choice for this one since it's shaping to be a large-ish system.

### Off-Chain Backend
Node.js

### MVP
For the MVP I would suggest taking a relatively simple project template (TBD) and fast-tracking the parts of the system that would make it possible to demonstrate it in action. Potentially deployed on a testnet first.