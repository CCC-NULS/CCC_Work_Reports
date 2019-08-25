# Project Plan
```
Project:	Mobile wallet
Lead Link : Angelillou
Period: 	2019.08 ~ 2019.12
Circle	: CCCd
```
## Milestones

### New version of nuls-js implementing 2.0 protocol

  This will support the official mobile wallet and the current and future dapps, will be an __isomorphic__ javascritp lib built using __lerna__ monorepo project, and distributed as __npm namespaced modules__ with bundles in different formats, to be easily integrated in different contexts: backend, frontend, and mobile projects.

  - In a first version we will achieve the next features:
  -- Modular package architecture
  -- Account module
  -- Block module
  -- Transaction module
  -- Smart contract module
  -- Docs and tests

### Nuls app wallet:

  Due to the requirements of the project, and the skills of the team members, we will build a __react native__ application targetting both: __android__, and __ios__ platforms using nuls-js as our main library to connect our application with the nuls 2.0 network.

  - This are the features we will aproach in a first version:
  -- Basic architecture of the project
  -- UX & UI implementation based on Claudio's wireframes and some designs we are going to need from the UI design team
  -- Security concerns (MFA, Fingerprint / FaceId, cyphered secure storage, ...)
  -- Account management (Wallet secure generation, backup, recovery, aliasing, delete, ...)
  -- Account details (transaction list, staking summary info, ...) 
  -- Basic portfolio aggregation statistics and price information
  -- Simple transaction form with configurable parameters (gas price, remark, ...)
  -- Staking form with deposit and withdrawal functionallity
  -- Internationalization at least in english, spanish and chinnese languages
  -- Integrated Dapp browser using nuls-js and local accounts
  -- Qr "sign and send" transaction protocol feature, for integrating with NULS light wallet
  -- Documentation, tests, deployment and distribution of the app

### New version of light explorer supporting the nuls-js framework

  This is not a priority right now, at the begining, nuls-js and mobile wallet will interact with the official nuls explorer deployed at nulscan.io, but as long as the community keep growing and the there will be more users, developers, and proyects using the infrastructure, we will need to offer to the developers community an scalable, configurable and light version of the nuls explorer ready to go with nuls-js to allow them to deploy and support their own instances. This will incurre in a better scalability of their projects.
  We will discuss this after :)

## Progress 

```
Date: 	2019.08.25
```

#### Nuls-js:

  - Modular package architecture: 0%
  - Account module: 0%
  - Block module: 0%
  - Transaction module: 0%
  - Smart contract module: 0%
  - Docs and tests: 0%

#### Nuls mobile wallet:

  - Basic architecture: 0%
  - UX & UI implementation: 0%
  - Security concerns: 0%
  - Account management: 0%
  - Account details: 0%
  - Basic portfolio: 0%
  - Transaction form: 0%
  - Staking form: 0%
  - Internationalization: 0%
  - Dapp browser: 0%
  - light wallet Qr integration: 0%
  - Documentation, tests, deployment and distribution: 0%

```
Notes:
Angelillou has vacations till 2019.09.01
Tudor is progressing on UX, but we need someone who starts with the designs ASAP
```