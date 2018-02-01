
# Genetic evolving 

## Darwinian Natural Selection

* Heredity. There must be a process in place by which children receive the properties of their parents 

* Variation. There must be a variety of traits present in the population or a means with which to introduce variation 

* Selection. There must be a mechanism by which some members of a popluation have the opportunity to be parents and pass down their genetic information and some do not. This is typically referred to as "survival of the fittest"


## Evolving Steps

* Setup variation of objects 
* Calculate and evaluate the fitness of objects
* Reproducation & Selection of objects
* Pick 2 parents to make a new set of object, choose objects with the best genetic material to enhance new generations (highest fitness)
* Make new child objects (Crossover and Mutation)
* Add the new child object to a new population
* Replace the old population with the new population and return to step two of workflow 

This workflow is executed in inside of a loop to find after many iterations the best objects

### Crossover

* Take half of the information of each parent to make a new object (Choose randomly)

* Create a "child" by combining the DNA of these two parents

### Mutation

* Take one information bit out of the new information pool and place a randomly choose information bit into the pool 

* Mutate the child's DNA based on a given proability 