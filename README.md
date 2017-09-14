# Haskell-encounters
This is a raw dump of my lerning sessions; during these sessions I tried to grasp misc Haskell idioms and concepts.

Gibiansky's [IHaskell kernel for IPython](https://github.com/gibiansky/IHaskell) was used to record the sessions.
Occasionally I use packages which are not available from bare IHaskell installation. I was able to import these packages after I added them to to IHaskell cabal file and updated/built the project.

For convenience I added the altered `ihaskell.cabal` file to this repo so you can quickly start using and executing code included in the notebooks from this repo.
I tried to follow the instructions in section "Where are my packages?" in IHaskell Readme file to make required packages available from IHaskell. For some reason adding dependencies to stack.yaml (as suggested in readme) did not work for me.

Remark: LANGUAGE directives when used in IHaskell affect the whole session, for instance: 

  `{-# LANGUAGE FlexibleContexts ,AllowAmbiguousTypes #-}`
  
causes persistent activation of respective switches regardless you close and then open notebook (it affects even other running notebooks in ihaskell session). The kernel must be restarted to clear these switches.

