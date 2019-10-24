# Project Plan
```
Project:	Mobile wallet
Lead Link : Angelillou
Period: 	2019.08 ~ 2019.12
Circle	: CCCd
```
## Milestones

**ECD = "Estimated Completion Date"*

### New version of nuls-js implementing 2.0 protocol

  This will support the official mobile wallet and the current and future dapps, will be an __isomorphic__ javascritp lib built using __lerna__ monorepo project, and distributed as __npm namespaced modules__ with bundles in different formats, to be easily integrated in different contexts: backend, frontend, and mobile projects.

  #### In a first version we will achieve the next features:
  - Modular package architecture (ECD: 2019-09-Q2)
  - Account module (ECD: 2019-09-Q2)
  - Transaction module (ECD: 2019-10-Q3)
  - Smart contract module (ECD: 2019-10-Q4)
  - Block module (ECD: 2019-11-Q1)
  - Docs and tests (ECD: 2019-11-Q1)

### Nuls app wallet:

  Due to the requirements of the project, and the skills of the team members, we will build a __react native__ application targetting both: __android__, and __ios__ platforms using nuls-js as our main library to connect our application with the nuls 2.0 network.

  #### This are the features we will aproach in a first version:
  - Basic architecture of the project (ECD: 2019-09-Q1)
  - UX & UI implementation based on Claudio's wireframes and some designs we are going to need from the UI design team (ECD: 2019-11-Q1)
  - Security concerns (MFA, Fingerprint / FaceId, cyphered secure storage, ...) (ECD: 2019-09-Q4)
  - Account management (Wallet secure generation, backup, recovery, aliasing, delete, ...) (ECD: 2019-09-Q3)
  - Account details (transaction list, staking summary info, ...) (ECD: 2019-09-Q1)
  - Basic portfolio aggregation statistics and price information (ECD: 2019-10-Q1)
  - Simple transaction form with configurable parameters (gas price, remark, ...) (ECD: 2019-10-Q1)
  - Staking form with deposit and withdrawal functionallity (ECD: 2019-11-Q1)
  - Internationalization at least in english, spanish and chinnese languages (ECD: 2019-11-Q1)
  - Integrated Dapp browser using nuls-js and local accounts (ECD: 2019-11-Q4)
  - Qr "sign and send" transaction protocol feature, for integrating with NULS light wallet (ECD: 2019-11-Q3)
  - Documentation, tests, deployment and distribution of the app (ECD: 2019-12-Q1)

### New version of light explorer supporting the nuls-js framework

  This is not a priority right now, at the begining, nuls-js and mobile wallet will interact with the official nuls explorer deployed at nulscan.io, but as long as the community keep growing and the there will be more users, developers, and proyects using the infrastructure, we will need to offer to the developers community an scalable, configurable and light version of the nuls explorer ready to go with nuls-js to allow them to deploy and support their own instances. This will incurre in a better scalability of their projects.
  We will discuss this after :)

## Progress 


```
Date: 	2019.10.24
```

#### Nuls-js:

  - Modular package architecture: 95%
  - Account module: 95%
  - Block module: 0%
  - Transaction module: __60%__
  - Smart contract module: 0%
  - Docs and tests: __20%__

#### Nuls mobile wallet:

  - Basic architecture: 95%
  - UX & UI implementation: 50%
  - Security concerns: 60%
  - Account management: 20%
  - Account details: 20%
  - Basic portfolio: 0%
  - Transaction form: 20%
  - Staking form: 0%
  - Internationalization: 0%
  - Dapp browser: 0%
  - light wallet Qr integration: 0%
  - Documentation, tests, deployment and distribution: 0%


```
Date: 	2019.09.19
```

#### Nuls-js:

  - Modular package architecture: 95%
  - Account module: __95%__
  - Block module: 0%
  - Transaction module: __20%__
  - Smart contract module: 0%
  - Docs and tests: __10%__

#### Nuls mobile wallet:

  - Basic architecture: 95%
  - UX & UI implementation: __50%__
  - Security concerns: __60%__
  - Account management: __20%__
  - Account details: __20%__
  - Basic portfolio: 0%
  - Transaction form: __20%__
  - Staking form: 0%
  - Internationalization: 0%
  - Dapp browser: 0%
  - light wallet Qr integration: 0%
  - Documentation, tests, deployment and distribution: 0%


```
Date: 	2019.09.05
```

#### Nuls-js:

  - Modular package architecture: __95%__
  - Account module: __90%__
  - Block module: 0%
  - Transaction module: 0%
  - Smart contract module: 0%
  - Docs and tests: __5%__

#### Nuls mobile wallet:

  - Basic architecture: __95%__
  - UX & UI implementation: __33%__
  - Security concerns: __20%__
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
