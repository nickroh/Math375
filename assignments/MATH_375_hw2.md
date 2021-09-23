# MATH 375

### Geonho Roh



* **1.5 Problem#23 )** *Determine the set is a real linear space*

$$
\text{All vectors }(x,y,z)\text{ in }V_3 \text{ with }x=0 \text{ or }y=0
$$

$$
 \text{ All vector space must satistfy the axiom 1}
\\ \text{ Let } a,b\in V
\\ a = (1,0,1) \ \ b=(0,1,1)
\\ \text{if }V \text{ is an vector space } a+b\in V 
\\ a + b = (1,1,2) \text{ both }x,y \text{ is not }0
\\ \text{ Because it doesn't satisfy axiom 1 it is not a real linear space}
$$

* **1.5 Problem#30a )** (a) Prove that Axiom 10 can be deduced from the other axioms.

$$
\text{Axiom 10) For every x in V, we have lx = x.}
$$

$$
x+(-1)x=0
\\x+(-1)x+1x = 0 + 1x
\\x+(1-1)x=1x
$$

**Problem #3~#6** In each of Exercises 1 through 10, let S denote the set of all vectors (x, y, z) in V_3 whose components satisfy the condition given. Determine whether S is a subspace of V_3. If S is a subspace, compute dim S.

* **1.10 Problem#3 )**

$$
S=x+y+z=0
$$

$$
\text{To prove that }S \text{ is a subspace of }(x,y,z) \text{ in }  V_3
\\ \text{We only have to show that it satistfy the closure theorem since it is the subspace of }V_3


\\ \\ \text{Let }w_1=(a_1,b_1,c_1), \ w_2=(a_2,b_2,c_2)\ \ \ w_1,w_2 \in S
\\
\\ \text{For axiom 1  }\  w_1 + w_2 = (a_1+a_2,b_1+b_2,c_1+c_2)
\\ (a_1+a_2)+(b_1+b_2)+(c_1+c_2)=(a_1+b_1+c_1) + (a_2+b_2+c_2)=0
\\ \text{Therefore, axiom 1 is satisfied}
\\ 
\\ \text{For axiom 2 \ let } m \in \mathbb{R} \text{ and let } w_1=(a_1,b_1,c_1) \in V_3
\\ mw_1 = (ma_1,mb_2,mc_2) \text{ and}
\\ ma_1+mb_2+mc_2=m(a_1+b_1+c_1) = 0 \ \text{ Since }a_1+b_1+c_1=0
\\ \text{Therefore, axiom 2 is satisfied}
$$
$$
\text{ Since closure axioms are satisfied it is a subspace}
\\
\\ \text{The dimension of the subspace}
\\
\\ \text{let  }(a,b,c) \in V_3 \text{ and }-a=b+c
\\ \text{It means } (b+c,b,c)
\\(b+c,b,c)=b(1,1,0)+c(1,0,1) \text{ two vectors are linearly independent}
\\ \text{ So that there are two basis and the dimension is 2}
$$



* **1.10 Problem#7 )**  

$$
S=x^2-y^2=0
$$

$$
\text{To prove that }S \text{ is a subspace of }(x,y,z) \text{ in }  V_3
\\ \text{We only have to show that it satistfy the closure theorem since it is the subspace of }V_3
\\
\\ \text{Let }w_1=(a_1,b_1) \text{ and }w_2=(a_2,b_2) \text{ } \ w_1,w_2 \in V_3
\\
\\ \text{For Axiom 1}
\\ w_1+w_2 = (a_1+a_2,b_1+b_2)
\\
\\ \text{Since }S=x+y+z=0
\\ (a_1)^2-(b_1)^2 = 0

\\ \text{repeating with }(a_2,b_2)
\\(a_2)^2-(b_2)^2 = 0
\\
\\(a_1+a_2,b_1+b_2) \text{ must satisfy }
\\ (a_1+a_2)^2-(b_1+b_2)^2=0
\\(a_1)^2-(b_1)^2+(a_2)^2-(b_2)^2+2(a_1a_2-b_1b_2)=0
\\
\\ \text{Both }(a_1)^2-(b_1)^2 \ (a_2)^2-(b_2)^2 \text{ are }0
\\ \text{However }2(a_1a_2-b_1b_2) \text{ cannot be 0 }
\\ \text{Therefore axiom 1 is not satisfied and also S is not a subspace.}
$$

* **1.10 Problem#22**  *In this exercise, L(S) denotes the subspace spanned by a subset S of a linear space V. Prove each of the statements (a) through (f).*
  $$
  \text{ a)} S \subseteq L(S)
  \\
  \\ \text{Since it is a vector space }L(S) \text{ has every linear combinations of vectors of S}
  \\ \text{So }span(S) \text{ has the every elements of }S \text{ and linear combinations of }S
  \\ \text{Therefore, }S \subseteq L(S)
  $$
  
  $$
  \text{b) }\ S \subseteq T \subseteq V \ \ \text{ and if T is a subspace of V } \ L(S) \subseteq T  \ \\ \text{In other words:  L(S) is the smallest subspace of V which contains S.}
  \\
  \\ L(S)\text{ is a vector space including } S \text{ also T is a vector space including S} 
  \\ \text{Since both of them are vector space they have linear combinations of S}
  \\ \text{However L(s) has only linear combinations of S since it is spanned by S}
  \\ \text{Therefore, every vector in L(s) is included in T which means L(s) is the smallest subspace of V which contains S}
  $$
  

$$
\text{c) A subset S of V is a subspace of V if and only if L(S) = S.}
\\
\\ \text{A subspace is a vector space}
\\ \text{So for a subset to be a subspace it has to satisfy closure axioms}
\\
\\ \text{Closure axioms means that the vector space is closed under linear combination}
\\ \text{However span of a set is set of all linear combinations}
\\ \text{Therefore if there is a subset S span(S) is a subspace}
\\
\\ \text{Therefore for a subset S of V to be a subspace }
\\ \text{That means }S=L(S)
$$

$$
\text{d) If } \ S \subseteq T \subseteq V, \text{ then } L(S) \subseteq L(T)
\\
\\ \text{In problem a we proved that } S \subseteq L(S) 
\\ \text{In problem b we proved that } L(S) \subseteq T \ \text{ if }\ S \subseteq T \subseteq V
\\
\\ \text{Applying the two theorems we can say that} S \subseteq L(S) \subseteq T\subseteq L(T) \subseteq V
\\ \text{Therefore } L(S) \subseteq L(T)
$$

$$
\text{e) If S and T are subspaces of V, then so is }S \cap T
\\
\\ \text{Both S and T are subspaces}
\\ \text{Therefore both S and T has }\vec0 
\\
\\ \text{Since S and T are subspaces } \ S \cap T \text{ must be a subset of V}
\\ \text{Let } A = S \cap T
\\ \text{To prove A is a subspace we need to show it satisfy closure axioms}
$$

