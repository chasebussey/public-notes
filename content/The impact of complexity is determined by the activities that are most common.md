---
publish: true
---

Complexity, in Ousterhout's sense, is primarily a term related to the *difficult of making changes* to a system ([[Complexity is the greatest limitation in software development]]). As such, the impact of highly complex modules that rarely need to be changed is very low. A rough equation is presented, where $C$ is the complexity of the overall system, $c_p$ is the complexity of any given part, and $t_p$ is the time spent making modifications to that part:
$$C = \sum_{p} c_p t_p$$

This loose formula carries the corollary that isolating complexity is much the same as eliminating complexity.

-----
## References
Ousterhout, John (2018). *A Philosophy of Software Design*.