# Weekly Report 
```
Time: 	2019.09.05 ~ 2019.09.19
Circle	: CCCc
Role:	Architect,Coder
Name: Berzeck
```
## This week's summary

- NulstarManager completion at 97% (2 items left: compress files and create, sign the manifest file's  hash )
- Nulstar Manager 'CreatePackage' component completed
- Testing and bringing temporary workaround solutions to users and a partner about issues found in NULS 2.0 processing methods from Connector, several methods detected
- Nulstar Manager is now able to create package in the format needed for the Updater to download and validate the integrity of the modules and libraries
- More NULS Beta 3.2  tests (Check 'Work Problem Feedback' section for details. 
- Chinese community had some questions about western team proposal, worked with David, Xfans and Sue to modify answers to be more clear for Chinese community
- Studied Infura API offering for Ethereum ( infura.io ), the conclusion is that Connector from Nulstar  offers similar functionality but th end product will offer a lot more, so the plan will be updated to focus on Connetor
- Give support to node owners and users 
- First bits of Updater module

## Next week's plan

- Complete NulstarManager
- Start Nulstar Updater module

## Work Problem Feedback

- Nulstar Connector WebSockets API.- Some methods are not being able to be processed by the respective module like:
     * latestBlockHeader
     * latestHeight
     * getLatestBlockHeaders
         In this block module, but some other methods from this module were processed without problems like getStatus
         The problem was traced back to the block module as it was checked that Connector and ServiceManager were routing the mthods correctly to the target module
    Nulstar htttp server
      The same problem above

