# Key Components of the Pipeline Architecture

### DAO & mini-DAOs
The *top-level Pipeline DAO* is comprised of Governors (based on actual contributions to the Treasury or actual projects.)

This would be a relatively standard piece of governance tech, where the directions taken by the protocol are proposed and vote on by the community, and all the tech upgrades go through the same procedure.

Changes to project templates, new project templates, core processing logic would all be decided here.

Each project is a mini-DAO, and the decisions made here all project-level and are based around project templates.

### Treasury & Shareholding Accounting
The tokenomics for both types of DAOs interweaves with both the decision-making processes and the execution of templates. Separate on-chain logic engines will be responsible for accounting on both and feed back into the voting process.

(Since having voting rights will depend on being a liquidity contributor.)

### Rep Tracking System
Based on prior performance, all actors will be assigned reputation points. Details TBD.

### Project Templates
A project template includes all the parameters necessary to assess viability of a project.

In particular:
- Project type;
- Project deliverables;
- Project milestones;
- Costs associated with each milestone;
- Types of collaborators involved;
- Costs of achieving milestones;
- The order of operations of the project's state machine.
- And other stuff. :)

### Decentralized Production Pipeline
DPP is a combination of
- persistent storage systems such as Arweave, 
- a finite-state machine interpreter for project templates, and
- certain DAO mechanism that help navigate the pipeline

### Collab Marketplace
This is not a separate entity, but part of the UI.

### UI
The (initially centralized) application that ties everything together and serves as:
- A discovery mechanism
- A collab marketplace
- A governance platform
- A project tracker
