##Q: how to install Doctest by using cabal

1. Install haskell platform
  Go to website https://www.haskell.org/platform/ and follow the instruction to install haskell platform

2. update the list of package in hackage
  1) open your terminal
  2) using command: cabal update
  3) stay in terminal

3. install doctest package
  1) using comman:cabal install doctest

-- You may think everything is done.. No! 
-- You should add the installation directory into you PATH, or you will get a error said "-bash: doctest: command not found"
  
3.find installation directory of doctest
    when you choose the installer of Haskell platform 
    if you choose core installer, 
      your installation directory might be in:  /Users/<username>/.cabal/bin
    if you choose full installer,
      your installation firectory might be in:  ~/Library/Haskell/bin
     
    The way that I used to find installation directory is:
    using command line step by step 
    - cd .cabal
    - cd bin
    - ls   -- you will see the doctest is in your directory
    - pwd  -- print working directory
    - copy the path
    
 4.add your installation directory into your PATH permanently
  

    
    
   