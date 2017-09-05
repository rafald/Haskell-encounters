# Haskell-encounters
This is just dump of my lerning sessions when I tried to grasp misc Haskell idioms and cncepts.

Gibiansky's [IHaskell kernel for IPython](https://github.com/gibiansky/IHaskell) was used to record the sessions.
Occasionally I use packages which are not available from bare IHaskell installation. Follow the instructions in section "Where are my packages?" in IHaskell Readme file to make required packages available from IHaskell. For instance to be able import Composition or Data.Aeson pakages alter the following section in stack.yaml yours IHaskell local repo:
`
extra-deps: 
    - composition-1.0.2.1
    - aeson-1.1.2.0

`

Remark: LANGUAGE directives when used in IHaskell affect the whole session, for instance: 

  `{-# LANGUAGE FlexibleContexts ,AllowAmbiguousTypes #-}`
  
causes persistent activation of respective switches regardles you close, open notebooki (it affects even other open notebooksi TODO double chack this). The kernel must be restarted to clear these switches
