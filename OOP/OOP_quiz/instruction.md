# Quiz Instruction
This quiz is a simplified version of 2016 presidential election. Write a definition for a class named `Candidate` with the following methods:

1. An `__init__` method that initializes `name`, `winning_states` and number of `votes`.
2. A `__str__` method that returns a string representation of this candidate, including `name` and winning state(s).
3. A method named `win_state` that takes a string of state abbreviation, adds it to `winning_states` and update `votes`.
4. A special method that overloads the operator `>` to compare votes of two candidates.

### Please DO NOT change code in main method!

---
### The expected outputs should be like below:

    Donald Trump wins 
    Hillary Clinton wins CA 

    After election:
    Donald Trump wins FL TX 
    Hillary Clinton wins CA MA 
    Does Trump win?
    True