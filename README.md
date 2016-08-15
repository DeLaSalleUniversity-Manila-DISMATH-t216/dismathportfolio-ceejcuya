# dismathportfolio-ceejcuya
Clarisse Mary Joy C. Aguilar

## Week 1
On our first day of lecture, the class had discussed about Propositions. A proposition is a declarative statement that should be either true or false. Propositions have different operations as well.

These are: (example, let p and q be propositions)
- Negation     - opposite of the statement, "p," therefore, it is read as "not p"
- Conjunction  - it is "p ∧ q," read as "p and q," and is only true when both p and q are true.
- Disjunction  - it is "p ∨ q," read as "p or q," and is only false when both p and q are false. This is also called as "inclusive or"
- Exclusive Or - the exclusive or of p and q is only true when exactly one of them is true.

Moreover, we had discussed Conditional Statements which shows "if p then(→) q" and it is only false when p is true and q is false.
There are also different conditional statements formed from "p → q."

These are:
- Converse        : q → p
- Contrapositive  : ¬q → ¬p
- Inverse         : ¬p → ¬q

Biconditional Statements are shown as "p ↔ q" and is true when both p → q and q → p are true.

Afterwards, we answered some exercises from the reference book regarding the said lecture today. Since it was in alphabetical order, the loop started with my surname. I had managed to answer most questions every time it's my turn. As far as I remember, I had answered letters a and h from number 8, letter d from number 21, letter b from number 27 and almost got the right answers for letter e from number 15 and letter d from number 29.

### Homework 1 : June 16, 2016
- 31.a. p ∧ ¬p

  | p | ¬p | p ∧ ¬p |
  | :---: | :---: | :---: |
  | T | F | F |
  | F | T | F |

- 33.b. (p ⊕  q) → (p ∧ q)

  | p | q | (p ⊕  q) | p ∧ q) | (p ⊕  q) → (p ∧ q) |
  | :---: | :---: | :---: | :---: | :---: |
  | T | T | F | T | T |
  | T | F | T | F | F |
  | F | T | T | F | F |
  | F | F | F | F | T |
  
- 35.c. (p → q) ∨ (¬p → q)

  | p | q | ¬p | p → q | ¬p → q | (p → q) ∨ (¬p → q) |
  | :---: | :---: | :---: | :---: | :---: | :---: |
  | T | T | F | T | T | T |
  | T | F | F | F | T | T |
  | F | T | T | T | T | T |
  | F | F | T | T | F | T |
  
- 37.d. (p → q) ∧ (¬p → r)

  | p | q | r | ¬p | p → q | ¬p → r | (p → q) ∧ (¬p → r) |
  | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
  | T | T | T | F | T | T | T |
  | T | T | F | F | T | T | T |
  | T | F | T | F | F | T | F |
  | T | F | F | F | F | T | F |
  | F | T | T | T | T | T | T |
  | F | T | F | T | T | F | F |
  | F | F | T | T | T | T | T |
  | F | F | F | T | T | F | F |

## Week 2
- Firstly, we had discussed about compound propositions. Compound propositions are expressions formed from propositional variables with the use of logical operators. The three kinds of compound propositions are:

  | Compound Proposition | Definition |
  | :---: | :---: |
  | Tautology | compound proposition is always true |
  | Contradiction | compound proposition is always false |
  | Contingency | compound proposition is neither Tautology nor Contradiction |
  
- From these compound propositions, logical equivalences are derived. They are compound propositions having the same truth values in all possible cases. The table below shows a list of the logical equivalences that will be often used.

  | Name | Logical Equivalence |
  | :---: | :---: |
  | Identity Laws | p ∧ T ≡ p |
  | | p ∨ F ≡ p |
  | Domination Laws | p ∨ T ≡ T |
  | | p ∧ F ≡ F |
  | Idempotent Laws | p ∨ p ≡ p |
  | | p ∧ p ≡ p |
  | Double Negation Law | ¬(¬p) ≡ p |
  | Commutative Laws | p ∨ q ≡ q ∨ p |
  | | p ∧ q ≡ q ∧ p |
  | Associative Laws | (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)
  | | (p ∧ q) ∧ r ≡ p ∧ (q ∧ r) |
  | Distributive Laws | p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r) |
  | | p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |
  | De Morgan's Laws | ¬(p ∧ q) ≡ ¬p ∨ ¬q |
  | | ¬(p ∨ q) ≡ ¬p ∧ ¬q |
  | Absorption Laws | p  (p ∧ q) ≡ p |
  | | p ∧ (p ∨ q) ≡ p |
  | Negation Laws | p ∨ ¬p ≡ T |
  | | p ∧ ¬p ≡ F |
  | *Implication Equivalence | p → q ≡ ¬p ∨ q |
  
- On our second meeting for the week, we had discussed about Quantifiers. Quantification expresses a predicate, which is a property that the subject of the statement can have, that is true over a range of elements. There are two types of Quantifiers:

  | Quantifier | Definition | Statement | When True | When False |
  | :---: | :---: | :---: | :---: | :---: |
  | Universal | P(x) for all values of x in the domain | ∀xP(x) | P(x) is true for every x | There is an x for which P(x) is false |
  | Existential | There exists an element x in the domain such that P(x) | ∃xP(x) | There is an x for which P(x) is true | P(x) is false for every x |

- Some logical equivalences were also derived from Quantifiers. These are:
  
  | Logical Equivalence |
  | :---: |
  | ¬(∀xP(x)) ≡ ∃x¬P(x) |
  | ¬(∃xP(x)) ≡ ∀x¬P(x) |

- Furthermore, we had a reading assignment about Nested Quantifiers. They are complex quantifiers which usually happen in Mathematics, Computer Science and other courses involving logic. It is highly important that we take note about the order of the quantifiers, unless all the given are universal quantifiers or all are existential quantifiers. The table below shows the definition of the quantifications of two variables:

  | Statement | When True | When False |
  | :---: | :---: | :---: |
  | ∀x∀yP(x,y) | P(x,y) is true for every pair x, y. | There is a pair x, y for which P(x, y) is false. |
  | ∀y∀xP(x,y) | | |
  | ∀x∃yP(x,y) | For every x there is a y for which P(x,y) is true. | There is an x such that P(x,y) is false for every y. |
  | ∃x∀yP(x,y) | There is an x for which P(x,y) is true for every y. | For every x there is a y for which P(x,y) is false. |
  | ∃x∃yP(x,y) | There is  pair x, y for which P(x,y) is true. | P(x,y) is false for every pair x, y. |
  
- Lastly, we discussed about the Rules of Inference. Here, we were taught how to prove through an argument, which is a sequence of statements that end with a conclusion. To make argument valid, the conclusion must follow from the truth of the premises of the argument itself. Premises are preceding statements. There is also what we call, invalid arguments, which are led by incorrect reasonings that are called fallacies. Another way to prove an argument is valid is through the use of the truth table. However, if an argument involves more than three different propositional variables, the truth table method becomes a tedious approach. Hence, we can do the rules of inference which we first establish the validity of some relatively simple argument forms. The table below shows different kinds of rules of inference:

  | Name | Tautology |
  | :---: | :---: |
  | Modus Ponens | (p ∧ (p → q)) → q |
  | Modus Tollens | (¬p ∧ (p → q)) → ¬p |
  | Hypothetical Syllogism | ((p → q) ∧ (q → r)) → (p → r) |
  | Disjunctive Syllogism | ((p ∨ q) ∨ ¬p) → q |
  | Addition | p → (p ∨ q) |
  | Simplification | (p ∧ q) → p |
  | Conjunction | ((p) ∧ (q)) → (p ∧ q)
  | Resolution | ((p V q) ∧ (¬p V r)) → (q V r) |
  
#### Answered parts in recitation:
Chapter 1.3. Propositional Equivalences

- 7.a. Jan is not rich or not happy.
- 15 (¬p ∧ (p → q)) → ¬p is Tautology. (Through Truth Table:)

  | p | q | ¬p | p → q | (¬p ∧ (p → q)) | (¬p ∧ (p → q)) → ¬p |
  | :---: | :---: | :---: | :---: | :---: | :---: |
  | T | T | F | T | F | T |
  | T | F | F | F | F | T |
  | F | T | T | T | T | T |
  | F | F | T | T | T | T |
  
- 17 ¬(p ↔ q) ≡ p ↔ ¬q are logically equivalent. (Through Truth Table:)

  | p | q | p ↔ q | ¬(p ↔ q) | ¬q | p ↔ ¬q |
  | :---: | :---: | :---: | :---: | :---: | :---: |
  | T | T | T | F | F | F |
  | T | F | F | T | T | T |
  | F | T | F | T | F | T |
  | F | F | T | F | T | F |
  
- Special Exercise:

  | (p ∧ (p → q)) → q | Logical Equivalence used |
  | :---: | :---: |
  | p ∧ (¬p V q)) → q | Implication Equivalence |
  | (p ∧ ¬p) V (p ∧ q) → q | Distribution Law |
  | F V (p ∧ q) → q | Negation Law |
  | (F V p) ∧ (F V q) → q | Distribution Law |
  | (p ∧ q) → q | Identity Law |
  | ¬(p ∧ q) V q | Implication Equivalence |
  | ¬p V (¬q V q) | De Morgan's Law and Associative Law |
  | ¬p V T ≡ T | Domination Law |
  
Chapter 1.4. Predicates and Quantifiers

- 1.a. True b. True c. False
- 7.a. All comedians are funny.
- 9.d. ∀x¬(P(x) V Q(x))
- 13.a. ∀n(n + 1 > n) ≡ T
- 15.d. ∃n(n^2 < 0) ≡ F
- 17.f. negation then conjunction

Chapter 1.5. Nested Quantifiers

- 3.d. There exist some students who received an e-mail from the whole class.

Chapter 1.6. Rules of Inference

- example of Modus Tollens: Punu is not cute and if she is cuddly then she is cute, therefore, Punu is not cuddly.
- Special Exercise:

  | ((p V q) ∧ (¬p V r)) → (q V r) | Logical Equivalence used |
  | :---: | :---: |
  | ¬((p V q) V (¬p V r)) → (q V r) | De Morgan's Law |
  | ¬((p V ¬p) V (q V r)) → (q V r) | Associative Law |
  | ¬(T V (q V r) → (q V r) | Negation Law |
  | ¬(¬(T V (q V r) V (q V r) | Implication Equivalence |
  | T V (q V r) V (q V r) | Double Negation Law |
  | T V (q V q) V (r V r) | Associative Law |
  | T V (q V r) | Idempotent then Associative Law |
  | T V (q ∨ r) ≡ T | Domination Law |
  
#### Homework 2 : June 23, 2016
Chapter 1.5.
- 5.a. Sarah Smith has visited www.att.com.
- 7.b. There exists some students who like Korean cuisine and all students like Mexican cuisine.
- 9.c. ∃y∀x L(x,y)
- 9.f. ∃x∀y(L(x,y) ↔ x=y)

Chapter 1.6.
- 35 Superman problem

  | Let | Definition |
| :---: | :---: |
| A | superman is able |
| W | superman is willing |
| I | superman is impotent |
| P | superman prevents evil |
| M | superman is malevolent |
| E | superman exists |

  | per statement |
  | :---: |
  | (A ∧ W) → P |
  | ¬A → I |
  | ¬W → M |
  | ¬P |
  | E → (¬I ∧ ¬M) |
  | ∴ ¬E |
  
  | Solution | Rule of Inference / Logical Equivalence used |
  | :--- | :---: |
  | ¬P<br> (A ∧ W) → P<br> ∴ ¬(A ∧ W) | Modus Tollens of ¬P and (A ∧ W) → P |
  | ¬(A ∧ W) ≡ ¬A ∨ ¬W ≡ ¬W ∨ ¬A | De Morgan's Law and Commutative Law|
  | ¬W → M ≡ W → M | Implication Equivalence of ¬W → M |
  | W ∨ M<br> ¬W ∨ ¬A<br> ∴ M ∨ ¬A ≡ ¬A ∨ M | Resolution of ¬W ∨ ¬A and W → M and Commutative Law of M ∨ ¬A |
  | ¬A → I ≡ A ∨ I | Implication Equivalence of ¬A → I |
  | A ∨ I<br> ¬A ∨ M<br> ∴ I ∨ M | Resolution of A ∨ I and ¬A ∨ M |
  | I ∨ M ≡ ¬(I ∨ M) ≡ ¬I ∧ ¬M | De Morgan's Law |
  | ¬(¬I ∧ ¬M)<br> E → (¬I ∧ ¬M)<br> ∴ ¬E | Modus Tollens of ¬I ∧ ¬M and ¬E |
  | ∴ ¬E | Therefore Argument is <b>VALID</b> |

## Week 3
We have further discussed about the Rules of Inference and to do this we had answered some questions from the book to exercise and familiarize ourselves more about the said lesson. We tackled about using rules of inference to build arguments which led us to the homework from last week which was number 35 or the Superman problem.

From the Example/Exercises part of Chapter 1.6, I have been able to answer the following:

- From Example 7 on Using Rules of Inference to Build Arguments, I have able to answer what the next step should be after applying Contraposition, which is Hypothetical Syllogism of ¬q → ¬p and ¬p → r, which gives ¬q → r.

- Exercise 4e If I worked all night on this homework, then I can answer all the exercises. If I answer all the exercises, I will understand the material. Therefore, if I worked all night on this homework, then I will understand the material.
  
  | Let | Statement |
  | :---: | :---: |
  | p | I work all night on this homework |
  | q | I can answer all the exercises |
  | r | I will understand the material |
  
  | Statement | Equivalence |
  | :--- | :---: |
  | If I worked all night on this homework, then I can answer all the exercises. | p → q |
  | If I answer all the exercises, I will understand the material. | q → r |
  | If I worked all night on this homework, then I will understand the material. | p → r |
  
  | Solution | Rule of Inference used |
  | :---: | :---: |
  | ((p → q) ∧ (q → r)) → (p → r) | <b>Hypothetical Syllogism</b> |

- Example: If you get 100% in Finals, then you get 4.0 grade. You get 4.0 grade. Therefore, you got 100% in Finals.
  Answer: If we convert this to logical equivalence, this will become q ∧ (p → q) → p.  Though this statement is not valid for it is not Tautology, where it should be and always true. To prove this, Truth Table method is used:
  
  | p | q | p → q | q ∧ (p → q) |
  | :---: | :---: | :---: | :---: |
  | T | T | T | T |
  | T | F | F | F |
  | F | T | T | T |
  | F | F | T | F |

  With the truth table shown above, it clearly states that this is not Tautology, therefore it is <b>Fallacy</b>. And it is also not valid because the equivalence should be <b>q ∧ (p → q) → q</b> to match the truth table.
  
After concluding Chapter 1.6 by answering some problems, we then go to the next part which is Chapter 1.7 or Introduction to Proofs. A proof is a valid argument that establishes the truth of a mathematical statement and may use the hypotheses of the theorem. For this section, the methods of proof discussed are used to prove mathematical theorems. A theorem is a statement that can be shown to be true. They may also be referred to as facts or results. Less important theorems are sometimes called propositions. A less important theorem that is helpful in the proof of other results is called lemma. Proving through a series of lemmas help us understand proofs which are complicated. A corollary is a theorem that can be established directly from a theorem that has been proved. A conjecture is a statement that is being proposed to be a true statement. This is usually based on some partial evidence or intuition.

| Methods of Proving | Definition |
| :---: | :--- |
| Direct Proof | if p → q, prove p is true |
| Proof by Contraposition | if p → q ≡ ¬q → ¬p, prove ¬q is true |
| Proof by Contradiction | p is true when ¬p → (r ∧ ¬r) is true for some proposition r |
| Vacuous Proof | p → q must be true when p is false |
| Proofs of Equivalence | prove a biconditional statement p ↔ q by showing p → q and q → p are both true |

Chapter 1.7 answered parts :

- 1 Use a Direct Proof to show that the sum of two odd integers is even.
  
  | Let | be |
  | :---: | :--- |
  | n | a + c |
  | a | 2b + 1 |
  | c | 2d + 1 |
  
  | Solution | |
  | ---: | :--- |
  | n = | a + c |
  | a + c = | ((2b + 1) + (2d + 1)) |
  | a + c = | 2 (b + d + 1) |
  | let k = | b + d + 1 |
  | <b>n =</b> | <b>2*k</b> |

- 15 Use proof by contraposition to show that if x + y ≥ 2 where x and y are real numbers, then x ≥ 1 or y ≥ 1.
  
  | Let | be |
  | :---: | :--- |
  | p | x + y ≥ 2 |
  | q | x ≥ 1 ∨ y ≥ 1 |

  By contraposition : p → q ≡ ¬q → ¬p
  
  | Let | be |
  | :---: | :--- |
  | ¬p | x + y < 2 |
  | ¬q | x < 1 ∧ y < 1 |
  
  | Solution | |
  | ---: | :--- |
  | if x < 1 and y < 1 | then x + y < 2 |
  | x + y < 1 + 1 = | x + y < 2 |
  | <b>x + y < 2 =</b> | <b>x + y < 2</b> |

## Week 4
In the first part of the week, the class continued the lecture on Chapter 1.7 by practicing further some exercises from the book since introduction to proofs is really a complicated topic, most especially if the problems involved irrational numbers.

Answered Parts for Chapter 1.7:

- 29 Prove or disprove that if m and n are integers such that mn = 1, then either m = 1 and n = 1, or else m = −1 and n = −1.

  Solution: If <i>p</i> then <i>q</i>.
  
  | p | q |
  | ---: | :--- |
  | mn = 1 | ((m=1)∧(n=1))∨((m=-1)∧(n=-1)) |
  
  Isolating m : m = 1/n<br>
  
  Substituting m on (m=1)∧(n=1) :<br>
  (m=1/n) ∧ (n=1)<br>
  (m=1/1) ∧ (n=1)<br>
  (m=1) ∧ (n=1)<br>
    
  Substituting m on (m=-1)∧(n=-1) :<br>
  (m=1/n) ∧ (n=-1)<br>
  (m=1/-1) ∧ (n=-1)<br>
  (m=-1) ∧ (n=-1)<br>
    
  Therefore, we proved that if m and n are integers such that mn = 1, then either m = 1 and n = 1, or else m = −1 and n = −1 to be true.
  
We then move to Chapter 1.8 and had only a brief introduction and answered an exercise to familiarize ourselves.
Chapter 1.8 is about Proof Methods and Strategy. First, we learn about Exhaustive Proof. This proof exhaust all possibilities and is a special type of proof by cases for each case or possibility involves checking a single example. Secondly, we learn about Proof by Cases and like on the first one, this should cover all possible cases that arise in a theorem. The third one is the Uniqueness Proof. This proof has two parts, the Existence and the Uniqueness.
  
Answered Exercise for Chapter 1.8 :

- 1 Prove that n^2 + 1 ≥ 2n when n is a positive integer with 1 ≤ n ≤ 4.

  Solution :<br>
  <b>at n=1:</b><br>
  1^2 + 1 ≥ 2^1<br>
  2 ≥ 2<br>
    
 <b>at n=2:</b><br>
  2^2 + 1 ≥ 2^2<br>
  5 ≥ 4<br>
    
  <b>at n=3:</b><br>
  3^2 + 1 ≥ 2^3<br>
  10 ≥ 8<br>
  
  <b>at n=4:</b><br>
  4^2 + 1 ≥ 2^4<br>
  17 ≥ 16<br>

For the second meeting, we continued on Chapter 1.8 by each of us answering different exercises from the book.

Answered Part:<br>
- 3 Prove that if x and y are real numbers, then max(x, y) + min(x, y) = x + y. [Hint: Use a proof by cases, with the two cases corresponding to x ≥ y andx < y, respectively.]

  Solution :<br>
  If x ≥ y : max(x,y) + min(x,y) = <b>x + y</b><br>
  If x < y : max(x,y) + min(x,y) = <b>y + x</b><br>
  x + y = y + x are equal due to commutative property.<br><br>
  
- We further had our discussion on sets. A set is an unordered collection of objects and these objects are called elements or members. There are two ways to describe a set, one is the roster method, which is able to list all the members oa set, and the other is the set builder method, which is for larger values which usually reach infinity. Below is the table of commonly used sets when set builder method is used,<br>
  
  | Set Letter | Definition |
  | :---: | :---: |
  | N | set of natural numbers |
  | Z | set of integers |
  | Z+ | set of positive integers |
  | Q | set of rational numbers |
  | R | set of real numbers |
  | R | set of positive real numbers |
  | C | set of complex numbers |
  
- We then recall the notation for intervals of real numbers. Given that a and b are real numbers,<br>

  | Interval | Definition |
  | :---: | :---: |
  | [a,b] | x such that a ≤ x ≤ b<br>also called as <b>CLOSED INTERVAL</b> |
  | [a,b) | x such that a ≤ x < b |
  | (a,b] | x such that a < x ≤ b |
  | (a,b) | x such that a < x < b<br>also called as <b>OPEN INTERVAL</b> |

- We discussed the definition of an Empty set as well. It is a special set that has no elements. This is also known as a null set and is denoted by ∅. The empty set can also be denoted by {}. Whereas a set with one element is called a singleton set.

- Sets can be represented graphically by using Venn diagrams. The universal set U contains all the elements or objects and is represented by a rectangle.

- Subsets are situations where the elements of one set are also the elements of the second set. Given that A and B are sets, and that A is a subset of B, we therefore use the notation A ⊆ B.

- For instance there are exactly n distinct elements in set S where n is a positive integer. We then denote this as S is a finite set and n is the cardinality of S, which is |S|.

- Power sets are made to consider all such combinations of elements of a set S. The power set of S is further denoted by P(S).

Answered parts for Chapter 2.1:

- 1a List the members of the set {x | x is a real number such that x2 = 1}.<br>
  answer : <b>1 and -1</b>

- 3c Determine whether the first is a subset of the second, the second is a subset of the first, or neither is a subset of the other: the set of flying squirrels, the set of living creatures that can fly.<br>
  answer : <b>the set of flying squirrels is a subset of the set of living creatures that can fly.</b>

- 6 Suppose that A = {2, 4, 6}, B = {2, 6}, C = {4, 6}, and D = {4, 6, 8}. Determine which of these sets are subsets of which other of these sets.<br>
  answer : <b>B is a subset of A and C is a subset of D.</b>

- 9b Determine whether this statement is true or false : ∅ ∈ {0}.<br>
  answer : <b>False</b>

- 10b Determine whether this statement is true or false : ∅ ∈ {∅, {∅}}.<br>
  answer : <b>True</b>

- 11b Determine whether this statement is true or false : {x} ⊆ {x}.<br>
  answer : <b>True</b>

- 27b Let A = {a, b, c, d} and B = {y, z}. Find : B × A.<br>
  answer : <b>B x A = {(y,a),(y,b),(y,c),(y,d),(z,a),(z,b),(z,c),(z,d)}</b>

- 30 Suppose that A × B = ∅, where A and B are sets. What can you conclude?<br>
  answer : <b>A = Ø or B = Ø</b>

## Week 5
We discussed Chapter 5.1 which is Mathematical Induction. This was said to be included for our first quiz which was on July 14, 2016, Thursday. There are two steps in completing mathematical induction. The first one is the basis step, where we show that P(1) is true and the second step will be the inductive step, where we show or prove that for all positive integers k, if P(k) is true, then P(k+1) is also true. The opposite of induction is deduction, where we start from general or theory to specific, whereas the induction is from specific to general or theory.<br>

Answered parts Chapter 5.1 :<br>

- 3e Let P(n) be the statement that 12 + 22 +· · ·+n2 = n(n + 1)(2n + 1)/6 for the positive integer n : Complete the inductive step, identifying where you use the inductive hypothesis.<br>
  Solution : <br>
  
  | P(n) | = 1^2 + 2^2 + ... + n^2 | = (n * (n+1) * (2n+1))/6 |
  | :---: | ---: | :--- |
  | P(n+1) | = 1^2 + 2^2 + ... + n^2 + (n+1)^2 | = ((n+1) * (n+2) * (2(n+1)+1))/6 |
  | P(n+1) | = P(n) + (n+1)^2 | = ((n+1) * (n+2) * (2(n+1)+1))/6 |
  | P(n+1) | = ((n * (n+1) * (2n+1))/6) + ((n+1)^2) | = ((n+1) * (n+2) * (2(n+1)+1))/6 |
  | P(n+1) | = ((2n^3 + n^2 + 2n^2 + n)/6) + (n^2 + 2n + 1) | = (2n^3 + 6n^2 + 4n + 3n^2 + 9n + 6)/6 |
  | P(n+1) | = (2n^3 + 3n^2 + n + 6n^2 + 12n + 6)/6 | = (2n^3 + 6n^2 + 4n + 3n^2 + 9n + 6)/6 |
  | P(n+1) | = (2n^3 + 9n^2 + 13n + 6)/6 | = (2n^3 + 9n^2 + 13n + 6)/6 |

- <i>July 14 - QUIZ 1 ; July 19 - CALL OFF</i>

## Week 6
After our first quiz, we had discussed about Chapter 2.3 which is all about Functions. Functions are also known or called as mappings or transformations. A function has two parts, the first one is the domain whereas the other is called codomain. There are three types of functions: <br>

| Type | Definition |
| :---: | :--- |
| One-to-One (Injunction) | functions that never assign the same value to two different domain elements. |
| Onto (Surjection) | every member of the codomain is the image of some element of the domain. |
| One-to-One Correspondence (Bijection) | function is both one-to-one and onto |

Answered Parts for Chapter 2.3:<br>

- 3a Determine whether f is a function from the set of all bit strings to the set of integers if : f(S) is the position of a 0 bit in S.
  answer : <b>Not a function</b>

- 4c Find the domain and range of these functions : the function that assigns to a bit string the number of one bits in the string.<br>
  answer : <b>Domain : bit string ; Range : positive integers</b><br><br>

<B>Homework:</B>
- 13 Which functions in Exercise 12 are onto?<br>
  answer :

  | Item | Answer |
  | :---: | :---: |
  | a) f (n) = n − 1 | ONTO |
  | b) f (n) = n2 + 1 | NOT ONTO |
  | c) f (n) = n3 | NOT ONTO |
  | d) f (n) = ┌n/2┐ | ONTO |
  
## Week 7
We continued our discussion on Chapter 2.3 which is about Functions by answering some exercises and our homework from the book.
We also discussed briefly the floor and ceiling functions :<br>

| Floor and Ceiling function | Definition |
| :---: | :---: |
| └x┘ | n if and only if n ≤ x < n + 1 |
| ┌x┐ | n if and only if n − 1 < x ≤ n |
| └x┘ | n if and only if x − 1 < n ≤ x |
| ┌x┐ | n if and only if x ≤ n < x + 1 |
| └-x┘ = -┌x┐ | |
| ┌-x┐ = -└x┘ | |
| └x + n┘ = └x┘ + n | |
| ┌x + n┐ = ┌x┐ + n | |

Answered parts for Chapter 2.3 :<br>

- 20a Give an example of a function from N to N that is : one-to-one but not onto.<br>
  answer : <b>n + 1</b>

- 20d Give an example of a function from N to N that is : neither one-to-one nor onto.<br>
  answer : <b>n * 0</b>

- 22a Determine whether each of these functions is a bijection from R to R : f (x) = −3x + 4.<br>
  answer : <b>Bijection</b>

## Week 8
For this week, we have studied about Algorithms.An Algorithm is a finite sequence of instructions for performing a computation or for solving a problem. As an instruction gets larger or bigger, we often forget the basics of an algorithm. With this, we can check the said instruction using the properties of algorithm.

| Property of Algorithm | Definition |
| :---: | :--- |
| Input | An algorithm should have input values from a specified set |
| Output | Each set of input values should have some output values produced and these should be the solution to the problem |
| Definiteness | Each step of the algorithm must be defined precisely |
| Correctness | An algorithm should produce the produce the correct output values for each set of input; mainly focuses on the output |
| Finiteness | An algorithm should produce the desired output after a finite or limited number of steps |
| Effectiveness | Each step of the algorithm must be performed possibly and exactly ; mainly focuses both on the procedure and the output |
| Generality | The procedure should be applicable for all problems of the desired form, not just for a particular set of input values |

We then discussed about searching and sorting algorithms. Stated below are the kinds of searching and sorting algorithms:

| Searching Algorithm | Definition |
| :---: | :--- |
| Linear Search | also known as sequential search<br> begins by comparing an input x to a set from A1 to AN. If x is equal to A1 then the solution will be the location of A1. If not, then x will be compared to the next value which is A2. The process will continue until x has successfully found its match in the sequence. |
| Binary Search | begins by comparing the element to be located to the middle term of the list. The list is then splitted into two smaller groups. The search continues by restricting the search to the appropriate group based on the comparison of the element to be located and the middle term. If the number of elements is odd, then we follow ┌(x/2)┐ to determine where to split the elements into two groups. |

<b>Sorting</b> is putting these elements into a list in which the elements are in a certain or desired order.

| Sorting Algorithm | Definition |
| :---: | :--- |
| Bubble Sort | It puts a list into increasing order by successively comparing adjacent elements, interchanging them if they are in the wrong order. To carry out the bubble sort, the basic operation is performed by interchanging a larger element with a smaller one following it, starting at the beginning of the list, for a full pass. The procedure is repeated until the sort is complete. |
| Insertion Sort Algorithm | To sort a list with n elements, the insertion sort begins with the second element. It compares this second element with the first element and inserts it before the first element. The third element is then compared with the first element and if it is larger than the first element, it is compared with the second element. It is inserted into the correct position among the first three elements. |

We further discussed about greedy algorithms. They are algorithms that make what seems to be the best choice. We further discussed this by having an example on coins.

Answered parts in Chapter 3.1 :

- definition of algorithm
- definition of finiteness
- example on binary search
- example on insertion sort
- Applying greedy algorithm on coins : How to make 77 cents?<br>
  Answer :<br>
  
  | Coins | Quantity |
  | :---: | :---: |
  | Quarter | 3 |
  | Penny | 2 |

- 2b Determine which characteristics of an algorithm described in the text (after Algorithm 1) the following procedures have and which they lack.<br>
  Answer : <b>Effectiveness</b><br>

- 2c Determine which characteristics of an algorithm described in the text (after Algorithm 1) the following procedures have and which they lack.<br>
  Answer : <b>Input</b><br>

- 11 Describe an algorithm that interchanges the values of the variables x and y, using only assignments. What is the minimum number of assignment statements needed to do this?<br>
  Answer :<br>

  Input : x and y<br>
  Procedure:<br>
  a = x <br>
  x = y <br>
  y = a <br>
  
On the following meeting, we further discussed about the growth of functions by discussing about the Big-O notation. With the use of Big-O notation, the growth of a function is estimated without worrying about constant multipliers or smaller order terms. With the use of Big-O notation, one does not have to worry about the hardware and software used to implement in algorithm. Moreover, using this notation, one can assume that the different operations used in an algorithm take the same time, which simplifies the analysis considerably.

## Week 9
- For this week, we had further discussed about the Big-O Notation since the topic itself is very confusing. Going back to its definition, the Big-O Notation is a comparison of algorithms and it measures them through their complexity.

- The first one is the constant complexity or the Big-O of 1. For example, it displays an array with 100 elements, the graph itself does not grow. Even if the array is 1000 elements, the graph will still not grow for it is constant or displays the array only once. Moreover, the constant complexity or Big-O of 1 is the best graph because of its simplicity.

- The constants, C and k are called witnesses to the relationship f(x) is 0(g(x)). C is the multiplier whereas k is the value where the f(x) and g(x) had intersected, where g(x) has surpassed f(x). As long as any function would be able to overtake or surpass a certain function, f(x) for example, that function is still considered as Big-O.

- n! is the worst graph because the more complex the function or algorithm gets, the more time it needs.

- We had further discussed Big-Omega and Big-Theta. Big-Omega is the opposite of Big-O, if the Big-O concentrates on the upper bound, Big-Omega then is concentrated on the lower bound. Yet both the Big-O and the Big-Omega have the same disadvantage, they have many answers for there is no limit. That is why Big-Theta is formed where it is a combination of the Big-O and the Big-Omega.

Answered Parts:
- example 5 from the book
