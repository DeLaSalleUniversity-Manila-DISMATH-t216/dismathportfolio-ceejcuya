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
  If x < y : max(x,y) + min(x,y) = <b>y + x
