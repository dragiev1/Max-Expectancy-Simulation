# Simulation for Maximum Expectancy Nth Coupon Problem

This is a Monte-Carlo simulation to see the behaviors of which an of extension of the nth coupon problem portay. 

**Proposal**: $\max_{law(\mathbb{R})}(\mathbb{E}_{law(\mathbb{R})}[T])$ | $\mathbb{P}(i \in P) = \frac{s}{n}$?

Given the condition of fairness: $\mathbb{P}(i \in P) = \frac{s}{n}$, where $s$ is the number of coupons inside a packet $P$ and n is the number of unique coupons possible, this removes the ability of choosing a "rareness" score to a card.
Otherwise, this question becomes trivial. 

**Question**: Which packet distribution *maximizes* $\mathbb{E}[T]$ in respect to time when considering fairness. 


##
### Simulation:

We begin tackling this problem by finding a hint to guide us in the right direction. Such a hint will hopefully be shined to light by utilizing the Monte-Carlo simulation method.

For now, lets list all the possible distribution laws we will use in this simulation and determine any fixed parameters we will also use. 

Fix $s=3$ and $n=12$. 

_(Recall that  $s$ is the number of coupons in each packet and $n$ is the total unique number of coupons)_ 

