# findingBestAttitude
Prisoner's Dilemma, finding the best simulation for real world
Use C++ 17

# To do list
- what if other agents can recognize other's previous decision
- previous decision memeory can be reset.
- All people can make mistake
- Test for different rounds and generations.
- People can recognize the situation(the opponnent agents) so that people might understand the decision of CHEAT.
- CHANGE THE RULE of Natural Selection. 
  - People can die because of mental problems.
  - People can die accidentally.
  
- People has discount factor for expected return. That means people prefer immediate return.

- Use RL and find the best method for this. Like GAN.
  

# Package Design
- evolution
  - agent
    - Agent Interface
    - else class
    
  - environment
    - Tournament class
    
  - match
    - Match class
- People
  - Individual class
  - Population class

Main
Test
