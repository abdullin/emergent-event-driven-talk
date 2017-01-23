

## Emergent event-driven design at SkuVault

Talk for Micro CPH


### Abstract

As software engineers we want to build software that creates value,
scales well and allows us to keep on adding new features. Ideally, at
the end of the day, it would also make us proud.

The challenge is in coming up with design that could accomplish all
that, while staying simple enough.

At SkuVault we took inspiration from the works of Eric Evans, Greg
Young and Alberto Brandolini, event-driven design, CQRS pattern, Lisps
and system simulation. We focused on capturing system contracts and
behaviors while iterating on the implementation details.

Current solution is event-based, uses C# with Lisp at the backend,
supports tenant partitions with 100+ GBs of events and processes them
at the speed of 10k per second on a small cloud node.

In this talk we'll go through the history of our design process,
learned lessons and tech stack decisions. We'll focus on key ideas and
concepts that you could take home and reuse in other projects.
