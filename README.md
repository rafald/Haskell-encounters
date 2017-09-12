# Haskell-encounters
This is a raw dump of my lerning sessions; during these sessions I tried to grasp misc Haskell idioms and concepts.

Gibiansky's [IHaskell kernel for IPython](https://github.com/gibiansky/IHaskell) was used to record the sessions.
Occasionally I use packages which are not available from bare IHaskell installation. Follow the instructions in section "Where are my packages?" in IHaskell Readme file to make required packages available from IHaskell. For instance to be able import Composition or Data.Aeson pakages alter the following section in stack.yaml yours IHaskell local repo:
`
extra-deps: 
    - composition-1.0.2.1
    - aeson-1.1.2.0
`
For convenience I added altered `ihaskell.cabal` file to this repo for quick setup.

Note that kernel does not have to be necessairly restarted after `stack build` incorporated new packages.

Remark: LANGUAGE directives when used in IHaskell affect the whole session, for instance: 

  `{-# LANGUAGE FlexibleContexts ,AllowAmbiguousTypes #-}`
  
causes persistent activation of respective switches regardles you close, open notebooki (it affects even other open notebooksi TODO double chack this). The kernel must be restarted to clear these switches


