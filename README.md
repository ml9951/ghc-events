This is a modified version of GHC Events that adds support for  Manticore events
============================

To install:
 
    git clone https://github.com/ml9951/ghc-events.git
    git checkout manticore-events
    cabal install

You should then be able to build ThreadScope to visualize Manticore events

Note that you will have to install this package prior to installing
ThreadScope so that it uses *this* package instead of downloading the
mainstream version on Hackage
