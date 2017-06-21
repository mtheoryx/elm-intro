# What the hell is elm?

It's a functional programming language, a compiler, and a framework
for developing JavaScript applications.

Typed
Functional
Language

PURE functional language - Everything is immutable

Functional concepts are hard to grasp, so Elm was created to take advantage
of them, but not force you to fully understand the background (monads, etc).

Who is the "User"?

Front-end developers. How can they get started and get all the power ?!

Gradual learning.

You don't need to force-feed functional concepts, you can just build web
applications, and learn on the way.

ELM is WELL documented. Tutorials, example applications, etc.

**Friendly error messages!!** The compiler knows what you're trying to do,
and what you should do to be safe.

## Feature: Usability

Elm tries to use obvious names. You won't see a lot of mentions about 'monads'
in the documentation. It is focused on the core audience trying to just
build awesome stuff.

hint: monads are used all the time, but we won't call them that.

Excellent tooling! Most languages/frameworks succeed or fail based on their
tooling.

And excellent focus on documentation. It's a core focus! And a freebie when
you use a typed, functional language.

SUPER friendly error messages! Yay!

## Feature: Maintainability

Once you make a "new thing" and push it out, that's one thing. But as the core
team drifts, and new developers are working to maintain the original thing,
Dragons enter.

### How do they help this?

- Static Type Checking (aware of use cases you may not be aware of)
- Automatic Semantic Versioning (old vs new lib comparisons)

## Other

Pure functional
Interop with JavaScript (designed to work with existing JS)
Virtual DOM (like react) You update state, Elm decides
Rich error messages built-in

**Bold Claim** Zero Runtime Exceptions

While it is certainly possible that you, as a developer, can introduce
business logic errors, there are Elm applications that have been running,
in production, **for years** that have suffered zero runtime exceptions.

It just rarely happens that an Elm application runs into a situation that
it wasn't prepared to handle and fails.
