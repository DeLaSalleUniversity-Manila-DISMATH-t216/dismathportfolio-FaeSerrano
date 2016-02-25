# dismathportfolio-FaeSerrano
dismathportfolio-FaeSerrano created by Classroom for GitHub

#Week 1
- Introduction to Discrete Mathematics DISMATH: it was tricky and interesting. 
- We should learn to think critically in this subject.
- Example problems about knights and knaves: I got the hang of it and capture my interest in the subject.
- There are several types of truth such as scientific truth and legal truth however Dismath only deals with mathematical truth.
- I was introduce to **propositions** 
  - it is a declarative statement that can be answered by true or false
  - not proposition: "x + 1 = 11"
  - propsition: "x + 1 = 11 at x=3"
- My first encounter with symbols like  ¬  and ⊕ and they are called logical connectives where ¬  is for Negation, ∧ is for conjunction, ∨ is for disjunction,⊕ is for exclusive disjunction, → is for implication, and ↔ is for biconditional.

| **Logical Symbol**  |  **Logical Operator** | **Shorthand** | **Formula** | **Logical Expression** |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

Propositional Logic
  - The contrapositive of the statement is also equivalent of the original statement
  
| Propositional Logic |  |
| :-------: | :-------:  |
| Inverse of p → q        | ¬p → ¬q|
| Converse of p → q       | q → p  |
| Contrapositive of p → q | ¬q → ¬p|



#Week 2
- Ive learned that superman does not exist!

![Imgur](http://i.imgur.com/1e7bd3q.jpg?1)
- I learned that instead of creating a truth table *(I must admit it can be tiresome especially with plenty of variables)* we can use logical equivalences instead.
  - Laws such as Associative, Distributive and Commutative are already familiar through algebra lessons.
  - Learned new laws such as De Morgan's law, absorption, domination and idempotent laws.

|         Name        |                           Equivalence                          |
|:-------------------:|:--------------------------------------------------------------:|
|    Identity laws    |                      p ∧ T ≡ p<br>p v F ≡ p                    |
|   Domination laws   |                       p v T ≡ T<br>p ∧ F ≡ F                   |
|    Negation laws    |                     p v ¬p ≡ T<br>p ∧ ¬p ≡ F                   |
| Double negation law |                            ¬(¬p) ≡ p                           |
|   Idempotent laws   |                       p v p ≡ p<br>p ∧ p ≡ p                   |
|   Commutative laws  |                   p v q ≡ q v p<br>p ∧ q ≡ q ∧ p               |
|   Associative laws  |       (p v q) v r ≡ p v (q v r)<br>(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r)<br>p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q<br>¬(p v q) ≡ ¬p ∧ ¬q          |
|   Absorption laws   |                 p v (p ∧ q) ≡ p<br>p ∧ (p v q) ≡ p             |

- I **really** enjoyed proving logical statements :)
- End of proposition logic
- Start of predicate logic
  - I've already encountered the word predicate in english class.
  - It is amazing how other terms can be applied to Dismath.
  - concern in internal structure in terms of subject and predicate.
- Quantifiers has two kinds: Universal and Existensial.
  - Universal  (∀x) - should be true to all values.
  - Existensial (∃x) - true to atleast one value.
- I've learned three termonologies about Rules of Inference
  - Argument - sequence of statements that end with a conclusion. Ex. (p1 ∧ p2 ∧ p3 ... ∧ pn) → q
  - Valid -  conclusion of the argument must follow from the true of the preceding statements of the argument. Ex. (p1 ∧ p2 ∧ p3 ... ∧ pn) → q is TAUTOLOGY
    - tautology - statement that is always true.
  - Fallacy - an invalid argument.



#Week 3
- So far, these are the following tools that can be used to prove statements:
  - Truth Table
  - Logical equivalences
  - Quantifiers
  - Rules of Inference

|  **Type**  |  **Rule of Inference**  |  **Tautology**  |
| :-------: | :--------------: | :---------: |
| Modus Ponens |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
| Modus Tollens |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
| Hypothetical Syllogism |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
| Disjunctive Syllogism |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
| Addition |  p ∴ p ∨ q  |  p → p ∨ q  |
| Simplification |  p ∧ q ∴ p  |  (p ∧ q) → p  |
| Conjunction  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
| Resolution  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

- Introduced to Methods of Proofs:
- The first rule is direct proof
 
- Direct Proof: (p → q)
  - Steps: 
    - Assume p is true
    - Prove that q is also true through step 1
- Had some sample problems that helped undestand better how to use direct proof.


#Week 4
- Proof by Contraposition/Indirect Proof: (p → q ≡ ¬q → ¬p)
  - Steps:
    - Assume ¬q is true
    - Show that ¬p is also true from the previous assumption.
- Vacuous Proof: (¬p → (p → q))
Premise:    ¬p
Conclusion: p → q
  - Show that p is false, because (p → q) must be true when p is false.
- Trivial Proof: (q → (p → q))
  - Show that q is true, then it follows that (p → q) must also be true.
- Proof by Contradiction
  - Steps:
    - Assume that the premise is not true: ¬(premise) ≡ T
    - Show that the assumption will end up in a contradiction.
- Had several examples to better understand the usage of each methods of proof.
- In proving, we must show every step and proof.
- Even assumption should have a corresponding proof to be consider valid.
- Proof by Equivalence
 - Biconditional:  p ↔ q, we show that p → q and q → p 



#Week 5
Cont of methods of proof:
- Had several examples to better understand the usage of Direct and indirect proof.
  - If n is a positive integer, then n is odd if and only if n^2 is odd.
  - For any natural number n, n is even if and only if n^2 is even.
- Counterexample - uses an example to disprove a statement
  - example: Every positive integer is the sum of the squares of two integers
    - Disprove using counterexample: 3
-Mathematical induction - treats the sequence of propositions as a domino
  - Steps:
    - *Basic step* show P(1) is true
    - *Inductive step* Assume P(k) is true
    - show p(k+1) is true
  - QED (quod erat demonstrandum) - signals the end of proof
  - Example: Prove P(n) = 1 + 2 + 3 + … + n = n(n+1)/2
  


#Week 6
- SUMMATION - notation for sum of am, am+1, ..., an is ∑ai=m ai where i is the index of summation.
  - Σ “sigma”
- RECURSIVE/INDUCTIVE DEFINITION
  - 1. Basis step: specify the value at zero
  - 2. Recursive step: Find a rule for finding its value at an integer number from the values at smaller integers.
  - example: f(0) = 3, f(n+1) = 2f(n) + 3
- RECURSIVE ALGORITHM - solves a problem by reducing it to an instance with smaller input

- PROGRAM CORRECTNES - to ensure that a program gives the correct output
  - PROGRAM VERIFICATION - A program is said to be correct if it produces the correct output for every possible input.
    - 1. Show that the correct answer is obtained if the program terminates.(Partial correctness)
    - 2. Show that the program always terminates
  - PARTIAL CORRECTNESS
    - initial assertioN (p)- gives the properties that the input values must have.
    - final assertion (q) - gives the properties that the output of the program should have, if the program did what was intended.
- HOARE TRIPLE p{S}q
  - S is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S

- **RULES OF INFERENCE**
 - *COMPOSITION RULE* </br>
  p{S1}q </br>
  q{S2}r </br>
  ______________ </br>
   ∴ p{S1;S2)r <br>
  - *CONDITIONAL STATEMENTS* </br>
  (p ∧ _condition_) {S} q </br>
  (p ∧ _¬condition_) → q </br>
  __________________________________________</br>
    ∴ p {**if** _condition_ **then** _S_} q
  - *IF-ELSE STATEMENT* </br>
  (p ∧ _condition_) {S<sub>1</sub>} q </br>
  (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
  _____________________________________ </br>
    ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q

- POWER SERIES
  - 
  


#Week 7
- Project 0.0:
 - To be passed next week, March 2, 2016
 - Individual
 - 
 
- SET THEORY
