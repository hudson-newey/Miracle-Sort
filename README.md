# Miracle-Sort

A [miracle sort](https://en.wikipedia.org/wiki/Bogosort#Related_algorithms) algorithm implemented in Assembly

**Why this approach? Why use assembly?**

1. I wanted to learn assembly
2. Assembly allows us to control bits and bytes at a lower level and reduce the likelihood that the algorithm will be "optimized"
   1. into an infinite while loop, meaning the loop will never exit
   2. Modern optimizers may also simplify down the array of items into a static constant, which would result in the list being immutable / un-sortable
