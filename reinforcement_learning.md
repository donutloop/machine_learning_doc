# Reinforcement Learning

## Legend of Reinforcement Learning

* O = Observation 
* A = action 
* R = reward
* h = history 
* SA = Agent state
* SE = Enviroment state 
* h = O_t, A_t, R_t 

## Information state

An informationen state (a.k.a Markov state) contains all useful information from the history

* The future is independent of the past given the present
* Once the state is know, the history may be thrown away 
* The state is a sufficient statistic of the future 

## Observable Environments 

* Full observability: agent directly observes enviroment state
    * Formally, this a Markov decision process (MDP)
* Partial observability: agent indirectly observes environment 
    * Now agent state != environment state    
    * Formally, this a Partially observable Markov decision process (POM)
    * Agent must construct it's own state respresentation 
    * Beliefs of environment state

## RL agent components

* Policy: agent's behaviour function
    * it is a map from state to action 
    * Deterministic policy 
    * Stochastic policy 
* Value function: how good is each state and/or action 
    * Value function is a prediction of future reward
    * Used to evaluate the goodness/badness of states
    * And therefore to select between actions
* Model: agent's representation of the environment
    * A model predicts what the environment will do next 
    * Transitions: P predicts the next state
    * Rewards: R predicts the next (immediate) reward
