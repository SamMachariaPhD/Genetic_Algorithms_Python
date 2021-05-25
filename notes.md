# Hands-on Genetic Algorithms with Python

## Section 1: The basics of Genetic Algorithms

### 1. An Introduction to Genetic Algorithms

- Drawing inspiration from Charles Darwin's theory

- Evolutionary computation
  - Genetic algorithms

  1. What are genetic algorithms?
  - A family of search algorithms.
  - By mimicking Darwinian natural selection and reproduction, these algorithms
  can produce high-quality solutions pertaining search, optimization, and learning
  that would otherwise be hard to come by.
  - Suitable for problems with large number of parameters and complex math
  representations.
  - Darwinian evolution
    - *Variation/Mutation:* Individual traits may vary (randomly).
    - *Inheritance:* Some traits are passed on to the offspring.
    - *Resemblance:* Offspring resemble their parents more than unrelated other.
    - *Selection:* Survival of the fittest to reproduce.
    - *Crossover/Recombination:* Offspring have a mix of their parents traits.

- The genetic algorithm analogy
  - Whereas Darwinian evolution maintains a population of individual specimens,
  genetic algorithms maintains a population of possible solutions (individuals).

  - Genotype
  This is a collection of genes that are grouped into chromosomes.
  This collection facilitates reproduction and mutation.
  Each chromosome of the offspring will carry a mix of genes from parents genotype.
  e.g. A single gene: `010111010`

  - Population
  A collection of solution for the problem at hand is maintained.
  e.g. A population: `010111010 000101010 110111110 010011011 010110000`

  - Fitness function
  Aka target function. The function/problem we seek to optimize/solve.
  Individuals are evaluated every time based on the fitness function.

  2. The theory behind genetic algorithms.
  3. Differences between genetic algorithms and traditional algorithms.
  4. Advantages and limitations of genetic algorithms.
  5. When to used genetic algorithms.
