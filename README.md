# Collection of Distributed Protocol Verification Problems

Compiled by Aman Goel [(amangoel@umich.edu)](amangoel@umich.edu)  and  Karem A. Sakallah [(karem@umich.edu)](karem@umich.edu) , University of Michigan



#### Description
54 safety checking problems ([Ivy](https://github.com/microsoft/ivy) files, as well as in [PYV](https://github.com/wilcoxjay/mypyvy) and [VMT](http://www.vmt-lib.org/) format), that can be classified as follows:

- **paxos:** 
A set of 10 problems from [9, 10, 11]. Problems include Lamport's Paxos, Voting, simplified EPR version of Paxos from [11], etc.

- **tla:** 
A set of 5 problems converted from the TLA+ Examples repository [1, 2, 3]. Problems include transaction commit, two-phase commit, etc.

- **ex:** 
A set of 14 problems collected from various openly-available resources [4, 5, 6]. Problems include toy consensus, decentralized lock, simple election, etc.

- **i4:** 
A set of 7 problems collected from benchmark suite accompanying the tool I4 [7]. Problems include chord ring, database chain replication, two-phase commit, etc.

- **mypyv:** 
A set of 16 problems collected from benchmark suite accompanying the tool fol-ic3 [8]. Problems include hybrid reliable broadcast, learning switch, firewall, etc.

- **distai:** 
A set of 2 problems collected from benchmark suite accompanying the tool DistAI [9]. Problems include blockchain and Ricart-Agrawala.



#### References
1. Transaction Commit TLA+ Examples: https://github.com/tlaplus/Examples/tree/master/specifications/transaction_commit

2. TeachingConcurrency TLA+ Examples: https://github.com/tlaplus/Examples/tree/master/specifications/TeachingConcurrency

3. Consensus TLA+ Examples: https://github.com/tlaplus/Examples/blob/fca227eb2bda8b811cda68d92d512ca266e4412f/specifications/PaxosHowToWinATuringAward/Consensus.tla

4. Ivy Examples: https://github.com/microsoft/ivy/tree/master/examples/ivy

5. mypyvy Examples: https://github.com/wilcoxjay/mypyvy/tree/aada097006e712d591a9f41c086b80444e941f8c/examples/fol

6. cfg-enum Examples: https://github.com/sat-group/cfg-enum/tree/permissive/benchmarks

7. I4 Examples: https://github.com/GLaDOS-Michigan/I4

8. fol-ic3 Examples: https://github.com/wilcoxjay/mypyvy/tree/pldi20-artifact/examples/fol

9. Lamport, L. The Paxos Algorithm or How to Win a Turing Award. https://lamport.azurewebsites.net/tla/paxos-algorithm.html?back-link=more-stuff.html

10. Goel, A. & Sakallah, K. A. Towards an Automatic Proof of Lamport’s Paxos. In Formal Methods in Computer-Aided Design (FMCAD), New Haven, Connecticut, October, 2021. (Accepted). Available at https://arxiv.org/abs/2108.08796

11. Padon O, Losa G, Sagiv M, Shoham S. Paxos made EPR: decidable reasoning about distributed protocols. Proceedings of the ACM on Programming Languages. 2017 Oct 12;1(OOPSLA):1-31.

12. DistAI Examples; https://github.com/VeriGu/DistAI/tree/master/protocols

Please report any corrections or usage experience via email  [(amangoel@umich.edu)](amangoel@umich.edu) or on github [(https://github.com/aman-goel/ivybench)](https://github.com/aman-goel/ivybench)
