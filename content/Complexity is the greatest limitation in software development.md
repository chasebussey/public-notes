---
publish: true
---

Software engineering, by nature, has a different set of constraints to other engineering disciplines. Rather than dealing with physical artifacts, we are encoding concepts for interpretation and execution by the computer. In order to effectively modify the systems built from those concepts, we have to be able to *understand* them, which makes complexity the chief limitation for most software development teams (excluding, for instance, firmware and robotics engineers for whom more of the laws of physics have regular bearing).

Complexity here represents the difficulty of understanding the system. As complexity increases and reasoning about the system becomes harder, the amount of information that needs to be available to the programmer also increases[^1], and since [[Working memory is a performance-limiting factor]] this leads to two primary issues:
1. The rate of change slows down
2. The incidence of bugs likely increases
A second-order effect of these primary issues is the eventual increase in process overhead that is likely to arise in the corporate setting as a result of increased bug rate (or sometimes in an attempt to speed delivery, but I've seen that less).

This all leads to the primary goal of system design, per John Ousterhout, which is to eliminate the complexity that can be removed by design, and to encapsulate the complexity that cannot such that is isolated from the bulk of the system (and ideally exposed via a reasonable interface).

[^1]: I can't prove it, but this increase is likely exponential, reminding me of the exponential increase in communication overhead mentioned by Brooks in *The Mythical Man-Month*.

---------
## References
Ousterhout, John (2018). *A Philosophy of Software Design*. 