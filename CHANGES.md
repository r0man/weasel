# master

## Changes

* Requires ClojureScript 0.0-2173

## Enhancements

* Client: `weasel.repl/alive?` to determine if REPL is
  connected/connecting or dead. (#5)
* Client: `weasel.repl/connect` now takes optional callbacks
  `:on-open`, `:on-error`, `:on-close`.
