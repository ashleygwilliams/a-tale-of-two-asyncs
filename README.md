# a-tale-of-two-asyncs
> how language values shape the features we build and the journeys we take to design them

The syntactical and conceptual affordances for asynchronous programming are the most powerful, yet also most controversial, elements and design patterns in Node.js and the greater JavaScript language ecosystem. From nested callbacks, to promises, to async/await, the ability and "ease" of writing asynchronous code has helped earn Javascript (and Node.js) both intense popularity across a large number of domains as well as intense criticism and scrutiny from programming language design experts, professional developers, and new developers alike.

In its own effort to be a first class server-side language, Rust has also embarked on it's own journey of language design for asynchronous programming. From Futures, to Tokio, to Async/Await- the Rust community has been prioritizing work to make asynchronous programming not only possible, but ergonomic and productive.

Both of these communities are tackling the same problem, in a very similar moment in time, yet they have very different technical design constraints and governance models. In this talk, we'll explore these two moments and how each community's context affects how conversations and work around async features have unfolded (or continue to unfold). By the end of the talk, we'll have a greater appreciation for the efforts involved in open source language design, the unique challenges of asynchronous programming features, and that ever illusive design concept of intuitive developer experience.
