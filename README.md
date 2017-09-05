# Haskell-encounters
This is just dump of my lerning sessions when I tried to grasp misc Haskell idioms and cncepts.

Gibiansky's [IHaskell kernel for IPython](https://github.com/gibiansky/IHaskell) was used to record the sessions.
Occasionally I use packages which are not available from bare IHaskell installation. Follow the instructions in section "Where are my packages?" in IHaskell Readme file make required packages available from IHaskell.

Remark: LANGUAGE directives in IHaskell when executed affect the whole session, f.e. 
{-# LANGUAGE FlexibleContexts ,AllowAmbiguousTypes #-}
causes persistent activation of respective switches regardles you close, open reopen notebook. The kernel must be restarted to clear these switches
