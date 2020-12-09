# Collection of Distributed Protocol Verification Problems

Compiled by Aman Goel [(amangoel@umich.edu)](amangoel@umich.edu)  and  Karem A. Sakallah [(karem@umich.edu)](karem@umich.edu) , University of Michigan


#### Description
42 safety checking problems ([Ivy](https://github.com/microsoft/ivy) files, as well as in [PYV](https://github.com/wilcoxjay/mypyvy) and [VMT](http://www.vmt-lib.org/) format), that can be classified as follows:

- **tla:** 
A set of 5 problems converted from the TLA+ Examples repository [1, 2, 3]. Problems include transaction commit, two-phase commit, etc.

- **ex:** 
A set of 14 problems collected from various openly-available resources [4, 5, 6]. Problems include toy consensus, decentralized lock, simple election, etc.

- **i4:** 
A set of 7 problems collected from benchmark suite accompanying the tool I4 [7]. Problems include chord ring, database chain replication, two-phase commit, etc.

- **mypyv:** 
A set of 16 problems collected from benchmark suite accompanying the tool fol-ic3 [8]. Problems include hybrid reliable broadcast, learning switch, firewall, etc.


#### References
1. Transaction Commit TLA+ Examples: https://github.com/tlaplus/Examples/tree/master/specifications/transaction_commit

2. TeachingConcurrency TLA+ Examples: https://github.com/tlaplus/Examples/tree/master/specifications/TeachingConcurrency

3. Consensus TLA+ Examples: https://github.com/tlaplus/Examples/blob/fca227eb2bda8b811cda68d92d512ca266e4412f/specifications/PaxosHowToWinATuringAward/Consensus.tla

4. Ivy Examples: https://github.com/microsoft/ivy/tree/master/examples/ivy

5. mypyvy Examples: https://github.com/wilcoxjay/mypyvy/tree/aada097006e712d591a9f41c086b80444e941f8c/examples/fol

6. cfg-enum Examples: https://github.com/sat-group/cfg-enum/tree/permissive/benchmarks

7. I4 Examples: https://github.com/GLaDOS-Michigan/I4

8. fol-ic3 Examples: https://github.com/wilcoxjay/mypyvy/tree/pldi20-artifact/examples/fol


Please report any corrections or usage experience via email  [(amangoel@umich.edu)](amangoel@umich.edu) or on github [(https://github.com/aman-goel/ivybench)](https://github.com/aman-goel/ivybench)
