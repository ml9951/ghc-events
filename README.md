This is a modified version of GHC Events that adds support for STM Events
============================

To install:
 
    git clone https://github.com/ml9951/ghc-events.git
    git checkout stm
    cabal install

You should then be able to build ThreadScope to visualize STM events

If you would like to extend ghc-events, I have
delimited all of my changes with "BEGIN STM" and "END STM" comments,
which should serve as a helpful guideline when determining what needs
to be modified in order to add a new event.
