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

Week 5
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
