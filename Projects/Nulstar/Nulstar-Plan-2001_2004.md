# Project Plan
```
Project:	Nulstar
Lead Link : Berzeck
Period: 	2020.01 ~ 2020.04
Circle	: CCCc
```
## Milestones

1] DappStarter Integration with NULS and Nulstar  ( https://dappstarter.trycrypto.com/ )
   Estimated Completion Date: 2020-03
   
   Description: DappStarter is a solution being developed by one of our partners which its main goal is to provide an extremely easy way to start developing dapps,
   the language chosen is JavaScript because it is easy to learn and most web developers know about it.
   
   The project needs to build a layer that connects DappStarter to NULS and also a framework on which to build NULS specific modules that hightlight 
   NULS blockchain benefits against other chains. The layer built will also help DappStarter be the perfect complement to Chain Factory solution
   
   (Need to learn web development TypeScript, JavaScript and React)

 2] Nulstar 2.0 Design complete
    Estimated Completion Date: 2020-03
   
    Description:
     In order to scale to enterprise grade usage some modules need to be upgraded:
         * An embedded message broker will be available in case a system using Nulstar  scales to tens or hundreds of modules
         * A storage module will be added so systems that use transactional databases can be developed withouth breaking microservices decoupled pattern
         * A Reports Engine should be added so systems can develop reports in a unified easy way
         * Authentication/Authorization module should be added, maybe wrap an opensource soultion like WSO2
         * Message protocol should be upgraded to modern solution like protobuffers or Thrift, also use AMQP enterprise message solution
           
   
 3] Design Documentation of all modules
    Estimated Compeltion Date: 2020-04
     
    Description: 
    Nulstar 2.0 design will be documented including the SBL (Service Base Library) which will be standarized

