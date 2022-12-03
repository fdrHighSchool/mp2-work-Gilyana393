# FizzBuzz
#### Respond to the following:

1. Fill out the following truth table:

| P  | Q  | P && Q | P \|\| Q |
|:--:|:--:|:------:|:--------:|
| T  | T  |    T   |    T     |
| T  | F  |    F   |    T     |
| F  | T  |    F   |    T     |
| F  | F  |    F   |    F     |


2. Prove a version of DeMorgan's Law:

| P  | Q  | P \|\| Q | ! (P \|\| Q) | !P | !Q | !P && !Q |
|:--:|:--:|:--------:|:------------:|:--:|:--:|:--------:|
| T  | T  |    T     |      F       | F  | F  |   F      |
| T  | F  |    T     |      F       | F  | T  |   F      |
| F  | T  |    T     |      F       | T  | F  |   F      |
| F  | F  |    F     |      T       | T  | T  |   T      |

3. What does DeMorgan's state and how did you prove it for the case above?
  * **YOUR WRITING HERE**
  NOT(P OR Q) == NOT(P) AND NOT(Q)
  We see that the boolean results(TRUE or FALSE) are the same for !(P || Q) and !P && !Q for all possible P and Q
