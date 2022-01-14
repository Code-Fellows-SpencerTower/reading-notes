# Linked Lists

## [Big O](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)

- method to describe the efficiency of an algorithm/function
- efficiency determined by 2 factors: Space and Time
  - Running time
    - amount of time a function takes to complete
  - Memory space
    - amount of memory a function uses to store data / instructions

- used to describe "worst case" efficiencey of an algorithm

- **4 key areas:**
  - **Input size**
    - size of parameter values read by function
    - actual size of each parameter
    - represented by `n`
    - higher number = increased Space and Time
  - **Units of measurement**
    - Time:
    - time in milliseconds
      - wont consider for Big O, since diff machines have different run times
    - number of operations
    - number of basic operations
      - the most time cosuming operations
    - Space:
      - space needed for the function
      - space needed for input data
      - space needed for output data
      - space needed for working space during operations
  - **Orders of growth**
  - **Best case, worst case, and average case**

## Linked Lists

- Linked list:
  - sequence of nodes connected to eachother
  - each one references the next in the link
- Singly:
  - number of references belonging to a node
- Doubly:
  - when a node is linked to the next and previous nodes
