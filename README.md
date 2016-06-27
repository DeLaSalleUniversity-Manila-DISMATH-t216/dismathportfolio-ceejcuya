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
  | T V (q V r) ≡ T | Domination Law |
  
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
  | ¬E |
  
  | Solution |
  | :---: |
  | (A ∧ W) → P ≡ (¬A V ¬W) → ¬P |
  | |
  | |
  | ¬A → I ≡ A V I |
  | (¬A V ¬W) ∧ (A V I) → (¬W V I) |
  | |
  | |
  | ¬W → M ≡ W V M |
  | (¬W V I) ∧ (W V M) → <b>(I V M)</b> |
  | |
  | |
  | E → (¬I ∧ ¬M) ≡ ¬E → ¬(¬I ∧ ¬M) |
  | ¬E → <b>(I V M)</b> |
  | |
  | |
  | Argument is <b>VALID</b>. |
