---
layout: default
---

# Publications

1. **[Exploiting Correlation in Finite-Armed Structured Bandits](paper_abstract)**<br/>
Submitted to The Conference on Uncertainty in Artificial Intelligence (UAI), 2019<br/><br/>
**Paper abstract:**
We consider a structured Multi-Armed bandit problem in which mean rewards of different arms are related through a hidden parameter. We propose an approach that allows generalization of classical bandit algorithms such as UCB and Thompson sampling to the structured bandit setting. Our approach is based on exploiting the structure in the problem to identify some arms as sub-optimal and pulling them only O(1) times. This results in significant reduction in cumulative regret, and in fact our algorithm achieves bounded (i.e., O(1)) regret whenever possible. We empirically demonstrate the superiority of our algorithms via simulations and experiments on the Movielens dataset. Moreover, the problem setting we study in this paper subsumes several previously studied framework such as Global, Regional and Structured bandits with linear rewards.

2. **[Energy-Delay-Distortion Problem](paper_abstract)**<br/>
Accepted at the National Conference of Communications (NCC), 2018<br/><br/>
**Paper abstract:**
An energy-limited source trying to transmit multiple packets to a destination with possibly different sizes is considered. With limited energy, the source cannot potentially transmit all bits of all packets. In addition, there is a delay cost associated with each packet. Thus, the source has to choose, how many bits to transmit for each packet, and the order in which to transmit these bits, to minimize the cost of distortion (introduced by transmitting lower number of bits) and queueing plus transmission delay, across all packets. Assuming an exponential metric for distortion loss and linear delay cost, we show that the optimization problem is jointly convex. Hence, the problem can be exactly solved using convex solvers, however, because of the complicated expression derived from the KKT conditions, no closed form solution can be found even with the simplest cost function choice made in the paper, also the optimal order in which packets should be transmitted needs to be found via brute force. To facilitate a more structured solution, a discretized version of the problem is also considered, where time and energy are divided in discrete amounts. In any time slot (fixed length), bits belonging to any one packet can be transmitted, while any discrete number of energy quanta can be used in any slot corresponding to any one packet, such that the total energy constraint is satisfied. The discretized problem is a special case of a multi-partitioning problem, where each packet's utility is super-modular and the proposed greedy solution is shown to incur cost that is at most 2-times of the optimal cost.
<br/><br/>
Paper link: [https://arxiv.org/abs/1711.05032](https://arxiv.org/abs/1711.05032)
