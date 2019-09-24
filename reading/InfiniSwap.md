## Efficient Memory Disaggregation with INFINISWAP

# Problem
Memory intensive applications' performance deteriorates badly if 
working sets don't fully fit in memory.

Former solution:
memory disaggregation aims at exposing a global memory bank to all machines
to increase their effective memory capacities.
BUT they need new architecture, hardware design and new programming models
which makes them infeasible

# Main Contribution
INFINISWAP, a remote memory paging system 
