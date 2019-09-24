## LegoOS

# Background
Limitation of Monolithic Servers
1, inefficient resource utilization
2, poor hardware elasticity(cannot reconfigure at run time)
3, coarse failure domain
4, bad support for heterogeneity

OS should also be aggregated
OS for Resource Disaggregation
Limitation of using one kernel: 
1, high latency
2, not able to exploit device local computation power
3, making processors the SPOF(single point of failure)

Multikernel solutions:
don't manage distributed resources and handle failures

# Complete Disaggregation

A complete disaggregation of processor, memory, and
storage means that when managing one of them, there
will be no local accesses to the other two

# The splitkernel OS architecture