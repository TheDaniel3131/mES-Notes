# Chapter 1: What is Algorithm?

- Graph Theory: To critically evaluate methods that tend to yield efficient algorithms. (Exam)

## Algorithms

- An algorithm is a sequence of clear instructions to solve a problem, which requires an input and produces an output in a finite amount of time. It must be specified correctly and completely for the computer to understand and execute it efficiently.

- A computational problem specifies the relationship between inputs and outputs. Problems can take various forms.

- An algorithmic process involves input to gather information, storage to store information, processing that includes arithmetic, repetition, or branching conditions, and output to display or provide information.

- Characteristics of an algorithm include well-defined inputs and outputs, clarity, finiteness, feasibility, and language independence.

# Chapter 2: Pseudocode

- Pseudocode is a description of a computer programming algorithm that uses structural conventions of programming languages and natural languages. It serves as a "high-level language" and aims to generalize the logic and flow of a program. It is an abstraction of a programming language and cannot be directly compiled.

- Pseudocode provides a necessary abstraction, allowing for ease of understanding and teaching. It generalizes problems into their basic algorithmic structure, focusing on how to solve the problem rather than specific programming syntax.

### Algorithm Vs. Pseudocode

- An algorithm is a systematic and logical approach that provides a step-by-step procedure. For example:

  1. Start.
  2. Enter the two numbers in variables X and Y.
  3. Calculate the sum of the two numbers and store it in variable Z.
  4. Output the result.
  5. End.

- Pseudocode, on the other hand, is a simplified version of programming code written in English. It is used to outline a program before the implementation phase. For example:
  1. Start.
  2. Input X and Y.
  3. Z = X + Y.
  4. Display Z.
  5. End.

### Classification of Algorithms

- Algorithms can be classified based on their computational complexity, efficient implementation, data structures used, design paradigm, and the fields in which they are employed.

(**Paradigm** refers to a fundamental approach or model for designing and building software systems. It provides a set of principles, concepts, and practices that guide developers in solving problems and organizing their code.)

Linear data structures:

- Lists
- Arrays
- Hash tables
- Stacks
- Queues

Graph data structures:

- Binary trees
- B-trees
- Heaps

### Classification by Design Paradigm

- Divide and Conquer: Breaking down a problem into smaller subproblems or components, solving them independently or seperately, and then combining the solutions to obtain the final result.

- Greedy: Making the best possible decision by choosing a local optimum at each stage of the algorithm.

- Search: Exploring a search space to find a desired solution. It can be used in various problem-solving scenarios, such as finding a path in a graph or searching for an element in a list. Basically, search algorithms and backtracking.

# Chapter 3: Algorithm Analysis & Asymptotic Growth Rate

- Algorithm is a step-by-step process to solve any problem which can be written in many ways. We need to analyze these algorithms to obtain the best or optimum solution.

- Algorithm expects to work fast for any input size. Small input size works the best.

- To analyze the validity of an algorithm -> Order of growth
