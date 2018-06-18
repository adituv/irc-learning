# irc-client

This is intended as a learning project for Haskell program architecture and
best practices.  I have never really done a project I would consider medium-
to-large scale before, so I intend to do that here and by doing so explore
various tradeoffs and architectural techniques.

Some current solutions I am aware of that I want to explore:

* mtl
  * lifted-base
  * unliftio

* simple-effects (as an alternative to mtl)

* Streaming IO
  * conduit
  * pipes

* Some sort of logging.  monad-logger?
