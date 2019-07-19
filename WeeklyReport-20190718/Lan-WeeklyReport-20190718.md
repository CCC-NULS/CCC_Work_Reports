# Weekly Report 
```
Time	2019.07.13 ~ 2019.07.19
Circle	CCCc
Role	Coder
Name	Lan
```
## This week's summary
- Performance test of the account information memory of the accounting module after caching.

-  Network module adds RPC interactive blocking message caching mechanism and functional testing.

- Intranet networking fatigue test and mixed intranet networking fatigue test.

  During the test and follow-up to solve the problem: block download efficiency problem, consensus time under the critical value of block problem, network server time problem, etc.

  Questions to be tracked:

  - RPC occasionally interacts with a delay of more than 0.5s under pressure (not necessarily present) 
  - Smallblock msg(Block header message) propagation time-consuming 3S delay problem (not necessarily present)
  - The peer of the transaction module finds an exception (not necessarily present) that the transaction is empty from the local hash.
  - Block module has message queue memory overflow problem (not necessarily present)

## Next week's plan

-  Solving known bugs
-  Guarantee the stability of network credit value under the mixed network of internal and external networks.
- Traffic control scheme and implementation of network module.

## Work Problem Feedback
- No

