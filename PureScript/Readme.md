### PureScript
PureScript is a functional programming language that compiles to JavaScript. It is heavily inspired by Haskell, and its syntax and design are similar to Haskell, making it a great choice for developers familiar with Haskell or those looking to explore a more functional approach to writing JavaScript code.

|_Language_|PureScript|
|-|-|
|_Developer_||
|_First appeared_||
|_Filename extension_|.purs|

```HelloWorld.purs
module Main where

import Prelude
import Effect (Effect)
import Effect.Console (log)

main :: Effect Unit
main = log "Hello, World!"
