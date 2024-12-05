---
publish: true
---
One of the most important skills in software engineering _seems_ to be knowing when to engage with an abstraction at its face, and when to break into the black box of that abstraction. It's common to run into issues with a leaky or otherwise malfunctioning abstraction and overlook the root cause as a function of not breaking open the black box.

Conversely, not knowing when to accept an abstraction as a black box and reason about it _while understanding_ that you're eliding the lower-level details is incredibly important for getting anything done in a codebase of more than trivial complexity. Part of the reason [[Conceptual integrity is the most important consideration in system design]] is that our concepts become our abstractions, and when the cohesion of our abstractions is low it is difficult to navigate the abstraction ladder.

This is probably a case of [[Everything is chunking]] as applied to the software engineering domain.