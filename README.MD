A typical CRUD app, but in Haskell.

## Dev setup

GHC (Haskell compiler) and cabal-install (build tool)

```bash
brew install ghc

export PATH="/opt/ghc/bin:$HOME/.cabal/bin:$PATH"

ghc --version
# The Glorious Glasgow Haskell Compilation System, version 8.8.1

cabal --version
# cabal-install version 3.0.1.0
# compiled using version 3.0.1.0 of the Cabal library
```

Haskell IDE Engine (HIE)

https://github.com/haskell/haskell-ide-engine#installation-from-source

```bash
g clone https://github.com/haskell/haskell-ide-engine --recurse-submodules

cd haskell-ide-engine

cabal new-update

./cabal-hie-install hie

./cabal-hie-install data
```

## Run

```bash
cabal new-run
```
