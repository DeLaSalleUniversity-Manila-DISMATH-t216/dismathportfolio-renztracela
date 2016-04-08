# dismathportfolio-renztracela
dismathportfolio-renztracela created by Classroom for GitHub

#WEEK 1
- First day of school. Dismath was the very first subject.
- Some higher batch is telling that this course is quite confusing and hard.
- When Sir Cabatuan introduced DISMATH, I thought it would be just like understanding some logical questions.
- He also introduced us to words like Propositions, Logical Deduction, Axioms.
- Sir Cabatuan also said that in DISMATH, emotions should not get in the way of logic.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

#WEEK 2

- In algebra we have different laws, also here in DISMATH we have also several laws.
- I learned the different kinds of equivalence

|                           Equivalence                          |         Name        |
|:--------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p  //     p v F ≡ p               |    Identity laws    |
|                       p v T ≡ T  //    p ∧ F ≡ F               |   Domination laws   |
|                       p v p ≡ p //     p ∧ p ≡ p               |   Idempotent laws   |
|                            ¬(¬p) ≡ p                           | Double negation law |
|                   p v q ≡ q v p // p ∧ q ≡ q ∧ p               |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) // (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) //  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q // ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p // p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T // p ∧ ¬p ≡ F                   |    Negation laws    |

- The superman homework was kinda hard and confusing but still I have managed doing it.
- Sometimes, I get lost on the topic because I get confused easily
- We were introduced to a new topic: **Quantifiers**. The two types of quantification are the following:
  * Universal Quantifiers = "For All"
  * Existential Quantifiers = "There Exists"
  
#Week 3
- I learned about rules of inference, It is easier to solve more complex problem with the use of rules of inference.

|         Name         |   Rule of Inference  |            Tautology           |
|:--------------------:|:--------------------:|:------------------------------:|
|    Modus Ponens      |      p, p→q ∴q       |        (p ∧ (p → q)) → q       |
|      Modus Tollens   |     ¬q, p→q ∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
|Hypothetical Syllogism|     p→q, q→r ∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|Disjunctive Syllogism |      p∨q, ¬p ∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|      Addition        |       p ∴p ∨ q       |           p → (p ∨ q)          |
|      Simplication    |       p ∧ q ∴p       |           (p ∧ q) → p          |
|       Conjunction    |      p, q ∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|      Resolution      | p ∨ q, ¬p ∨ r ∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

- I learned also about Methods of Proof.
- The First one is Direct Proof.
- I. **Direct Proof**.
- Steps:
  *   1. Assume *p* is T.
  *   2. Show that *q* is also T.

#Week 4
- I learned about the other Methods of Proof
- II. **Proof by Contraposition**.
- Steps:
  *   1. Assume *¬q* is T
  *   2. Show that *¬p* is also T.
- III. **Vacuous Proof**.
- Which is basically ¬p → (p→q)
- Steps:
  *   1. Show that *¬p* is T **OR** *p* is F.
  *   2. *p→q* is T when *¬p* is **OR** *p* is F.
- IV. **Trivial Proof**
- Basically, q → (p→q)
- Steps:
  *   1. Show that *q* is T.
  *   2. p→q is therefore T when *q* is T
- V. **Proof by Contradiction**
- Prove that the premises will end up FALSE or in Contradiction
- Steps:
  *   1. Assume **ALL PREMISES** to be FALSE.
  *   2. Show that these premises will end up in a Contradiction.
- I also learned about what rational number is.
- The real number *r* is *rational* if there exist integers p and q with q≠0 such that **r = p/q**. Otherwise, it is an *irrational number*.
- Q = {a/b | a, b ∈ ℤ} where b≠0, a & b have no common factor other than ±1

#Week 5
- VI. **Proof by Equivalence** (Biconditionals):
  - P ↔ Q ≡ (P → Q) ∧ (Q → P)
  - Steps:
    - Show P → Q is true.
    - Show Q → P is true.
  - *Substitution* is not considered a proof.
- VII, **Mathematical Induction**:
  - Steps:
    1. Show P(1) or P(0) to be true.
    2. Assume P(k) is true.
    3. Show P(k+1) to be true.

#WEEK 6

* **SUMMATION**
    - The notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.
    - Example: ∑<sup>a</sup><sub>i=m </sub> = 1 + 2 + 3 + ... + n
    - We also proved the theorem: The sum of the first n powers of two is _2<sup>n</sup>-1_.

* **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers
    - Example: Find _f(1), f(2), f(3), f(4)_ of the following recursive function.

* **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.
    - Examples:
        - What is the recursive algorithm _n!_?
        - Give a recursive algorithm for computing _a<sup>n</sup>_, where _a_ is a nonzero real number and _n_ is a nonnegative integer.

* **PROGRAM CORRECTNESS**
    - We need a proof to show that the program always gives the correct output.
        - PROGRAM VERIFICATION
            - Proof of correctness of programs
            - Uses the rules of inference and various proof techniques including mathematical induction
            - It is said to be correct if it produces the correct output for every possible input:
                1. Show that the correct answer is obtained if the program terminates (Partial Correctness)
                2. Show that the program always terminates
        - PARTIAL CORRECTNESS
            - Two propositions are used to specify what it means for a program to produce the correct output:
                1. Initial Assertion - _p_ - gives the properties that the input values must have
                2. Final Assertion - _q_ - gives the properties that the output of the program should have, if the program did what it was told

* **HOARE TRIPLE**
    - p{s}q
    - A program, _S_, is said to be partially correct with respect to the initial assertion _p_ and the final assertion _q_ if whenever _p_ is true for the input values of _S_ and _S_ terminates, then _q_ is true for the output values of _S_.
    - Example: Given the initial assertion _p: x=1_ and the final assertion _q: z=3_, show the partial correctness of the program segment: </br> y = 2 </br> z = x + y

* **RULES OF INFERENCE**
    - CONDITIONAL STATEMENTS </br>
        (p ∧ _condition_) {S} q </br>
        (p ∧ _¬condition_) → q </br>
        ∴ p {**if** _condition_ **then** _S_} q
        - Example: Verify that the following program segment is correct with respect to the initial assertion _T_ and the final assertion _y ≥ x_. </br>
            **if** _x>y_ **then** </br>
            _y=x_
    - IF-ELSE STATEMENT </br>
        (p ∧ _condition_) {S<sub>1</sub>} q </br>
        (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
        ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q
        - Example: **if** _x<0_ **then** </br> _abs= -x_ </br> **else** </br> _abs = x_

* **POWER SERIES**
    - ∑<sup>∞</sup><sub>n = 0</sub> a<sub>n</sub>x<sup>n</sup> </br>
        where _a<sub>0</sub>, a<sub>1</sub>, a<sub>2</sub>, ..._ is a given sequence of constants, and _x_ is a real variable.
    - Examples:
        - 1 + r + r<sup>2</sup> + r<sup>3</sup> + ... = 1/(1-r)
        - Represent as power series: 1/(1+x)
        - Find the corresponding function: 1 - x<sup>2</sup> + x<sup>4</sup> - x<sup>6</sup> + ...

#WEEK 7
* INTRODUCTION TO SET THEORY
  * Empty Set
  * ↳ { } = ∅
  * Set Builder Notation
  * {x | some property x satisfies}
* VENN DIAGRAMS
  * UNION 
   * A ⋃ B ≡ (x ∈ A) ∧ (x ∈ B) 
  * INTERSECTION
   * A ⋂ B ≡ (x ∈ A) ∨ (x ∈ B) 
  * DIFFERENCE
   * A - B
  * DIFFERENCE
   * A \ B ≡ (x ∈ A) ∧ (x ∉ B)
  * SYMMETRIC DIFFERENCE
   * A ∆ B ≡ {x | (x ∈ A) ∧ (x ∉ B) ∨ (x ∈ B) ∧ (x ∉ A)}

#WEEK 8

* **ALGORITHMS**
    - A finite set of precise instructions for performing a computation or for solving a problem.
    - **Properties of Algorithms**: </br>
        ⇾ _Input_ - has input values from a specified set </br>
        ⇾ _Output_ - solution to the problem </br>
        ⇾ _Definiteness_ - defined precisely </br>
        ⇾ _Correctness_ - produce the correct output values </br>
        ⇾ _Finiteness_ - produce the desired output </br>
        ⇾ _Effectiveness_ - perform exactly and in a finite amount of time </br>
        ⇾ _Generality_ - applicable for all problems of the desired form
* **PSEUDOCODE**
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - **Preconditions** - describe valid input
    - **Postconditions** - conditions that the output should satisfy

#WEEK 9

- For this week, we discussed the types of algorithm procedures that we can use when writing a pseudocode

* **SEARCHING ALGORITHMS** </br>
    - Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.

* **SORTING ALGORITHMS** </br>
    - Problem of assorting elements into increasing order

* **GREEDY ALGORITHMS** </br>
    - Algorithms that make what seems to be the "best" choice at each step.

- We also started on the **Growth of Functions** (Big-O Notation)

#WEEK 10
* **Big-O Notation**
        ↳- Let _f_ and _g_ be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants _C_ and _k_ such that: </br>
        |f(x)| ≤ C|g(x)| </br>
    whenever _x > k_.
* **Big-Omega and Big-Theta Notation**</br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound

#WEEK 11
## NO CLASSES

#WEEK 12
* **Graph Theory**
    - _Node_ = Vertex
    - _Edge_ = Bridge
    - _Degree_ - number of connected edge on a node
    - _Handshaking Theory_ - 2e = ∑deg(v)
    - _Path_ - sequence of edges travelling from vertex to vertex along the edges
    - _Euler Circuit_ - passess through every edge and goes back to starting point. All vertex has an even degree.
    - _Euler Path_ - simple path containing every edge of the graph. Exactly **2** vertices have an odd degree.
    - _Hamilton Path_ - passes through every vertex
    - _Hamilton Circuit_ - passes through every vertex then goes back to the starting point
    - _Adjacency Matrix_ - 1 if adjacent to the chosen vertex; 0 if non-adjacent
    - _Incidence Matrix_ - 1 when edge is incident with chosen vertex; 0 otherwise
    - _Isomorphism of Graphs_ - Identical Graphs

*Note:* Euler starts with the letter E that means that it should pass every edge while Hamilton ends with the letter N that means that it should pass every node

* **Planar Graph**
    - There are no edges that crosses in a graph
    - _Euler's Formula_ - regions = edges - vertices + 2
    - _Euler's Characteristic_ - ℵ = regions - |edges| + |vertices| = 2

* **Homeomorphic Graphs**
    - can be obtained from the same graph by a sequence of elementary subdivisions
    - _Kuratowski's Theorem_ - nonplanar if and only if it contains a subgraph homeophobic to K<sub>3,3</sub> and K<sub>5</sub>

#WEEK 13
* **Graph Coloring**
    - assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color
    - The _chromatic number_ (χ) of a graph is the least number of colors needed for a coloring of this graph.
    - _Four Color Theorem_ - the chromatic number of a planar graph is no greater than four

* **Trees**
    - connected undirected graph with no simple circuits
    - _Forest_ - multiple trees
    - _Rooted Tree_ - a tree in which one vertex has been designated as the root and every edge
		- An **ordered rooted tree** is a rooted tree where the children of each internal vertex are ordered. 
		- **leaves** - nodes that do not have children
		- **ancestors** - nodes on top
		- **descendants** - children/grandchildren
    - _Subtree_
    - _M-ary tree_ - if every internal vertex has no more than m children
        - an m-ary tree with m = 2 is called a _binary tree_

* **Modeling Computation**
    - _Language and Grammars_
        - Grammars are used to generate the words of a language and to determine whether a word is in a language
        - Compiler reads a program written in a source language and translate it into an equivalent program in a target language.
        - Formal Language is an automatic translation of one language to another. Concerned about Syntax and Semantics.
            - well defined set of rules

* **Alphabet & String**
    - common way to talk about words, numbers, etc.

* **Automata Theory**
    - All about law of computation
    - Finite Automata - simplest model of automata
        - initial state
        - final/acceptance state
        - dead/stuck state
        - transition

* **Lexical Analysis**
    - process where the stream of characters making up the source program into a sequence of "words" that make up the source code.

* **Finite State Machine**
      - S: Finite set of states
      - I: Finite input alphabet
      - O: Finite output alphabet
      - f: Transition function
      - g: Output function
      - s<sub>0</sub>: Initial state

* **Turing Machine**
      - Alan Turing, the father of computer science.
      - Imitation Game movie based on his life story.

