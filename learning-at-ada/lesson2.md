# Problem Solving
Ada Build - Learning at Ada: Lesson 2

Five essential elements of an algorithm: input, output, finiteness, definiteness, and effectiveness

## Algorithms

An algorithm is a series of steps to solve a problem. We use algorithms everyday without realizing it. An algorithm is the procedure we follow to complete a task. Each step can be broken down to different degrees of preciseness. 

For computers, these instructions (algorithms) need to be extremely precise because a computer cannot make assumptions or inferences.

### 5 Essential Properties of an Algorithm
Computer scientist Donald Knuth defines an algorithm as a set of steps or rules with 5 basic properies: finitness, definiteness, inputs, outputs, and effectiveness. 

When we write an algorithm, we need to be as precise as necessary to produce our intended output. It's important to address all 5 properties. 
### Input
An algorithm starts its computation from an initial state. This state may be expressed as input values given to the algorithm before it starts. 
### Output
An algorithm must produce a result with a specific relation to the inputs. 
### Finiteness
An algorithm must start and stop. The rules that an algorithm applies must also conclude in a reasonable amount of time. What's defined as "reasonable" depends on the nature of the algorithm but an algorithm cannot take an infinite amount of time to complete its task. Knuth calls this property the finiteness of al algorithm. 
### Definiteness
The actions that an algorithm performs cannot be open to many interpretations. Each step must be precise and unambiguous. Knuth terms this quality definiteness. For example, an algorithm cannot iterate a "bunch" of times. The number of times must be precisely expressed - such as 2 times or 10000 times.
### Effectiveness 
The steps of an algorithm must be sufficiently simple that they could be expressed. These steps must make sense for the quantities used. 

### Testing
Once we have an algorithm, we want to test it out. This is done by having the computer follow the instructions we have provided and see if the result is what we intended. 

Although the instructions worked for one particular case, we should consider how the algorithm would handle if given different inputs. Often times, some of our test cases fail or our desired output is reached but not in the most efficient way possible. This means that while our algorithm works, it doesn't work well. Refining or refactoring the algorithm involves making our algorithm better so that it works for more test cases or more efficiently solves our problems. 