$$

$$

# MATH 375 



* Prove by contradiction that there are infinitely many primes.


$$
\text{Let's assume there are finite primeb numbers.}
  \newline \text{So there are total n primes.}
  \newline p_{1}\dots p_{n} 
  \newline \text{Let A be the product of all prime numbers} 
  \newline A = p_{1} \times p_{2} \dots \times p_{n}
  \newline \text{and there is number B which is }
  \newline B = A+1
  \newline \text{Since there are only n prime numbers the B should not be a prime number}
  \newline \text{Therefore the B should be divided by one of the prime nubers in } p_1\dots p_2
  \newline \text {However there is no prime numbers that can divide B } 
  \newline \text{ Since A is the product of all prime numbers A can be divided by any prime numbers}
  \newline \text{But 1 cannot be divided by any primenumber from }p_1 \dots p_n 
  \newline B \div p_k = \frac{p_1\times p_2 \dots p_n}{p_k} + \frac{1}{p_k}
  \newline \text{Therefore B can be divided by 1 and itself only and by the definition of prime number}
  \newline \text{B is a prime number.}
  \newline \text {The assumption that there are finite prime number is wrong, therefore there are infinite prime numbers}
$$

  

* Prove the following formula by induction: 1+3+5+ ⋯ +(2n−1)=n^2
  $$
  \text {For } n=1
  \newline (2\times 1 - 1) = 1^2 \text{ }\text{is correct}
  \newline \text{Let's assume that the equation is true for n}
  \newline 1+3+5+\dots +(2n-1) = n^2
  \newline \text{And prove the statement is true for n+1}
  \newline 1+3+5+\dots (2(n+1)-1) = (n+1)^2
  \newline 1+3+5+\dots (2(n+1)-1) 
  \newline = 1+3+5+\dots +(2n-1) + (2(n+1)-1)
  \newline = n^2 + (2(n+1)-1)\text{ (by the assumption)}
  \newline = n^2 + 2n +1
  \newline n^2 +2n +1 \text{is equal to } (n+1)^2
  \newline \text{by the induction the formula is correct}
  $$
  



* Prove the following formula by induction: 
  $$
  1^3+2^3+ ⋯ +(n−1)^3<\frac{n^4}{4}<1^3+2^3+ ⋯ +n^3
  $$

  $$
  \newline \text{Assume n is a positive integer}
  \newline \text{For } n=1
  \newline (1-1)^3 < \frac{1^4}{4} < 1^3 \text { is true}
  \newline \text{Now we assume that the equation is true for n}
  \newline 1^3+2^3+ ⋯ +(n−1)^3<\frac{n^4}{4}<1^3+2^3+ ⋯ +n^3
  \newline \text{And prove the equation is true for n+1}
  \newline 1^3+2^3+ ⋯ +(n−1)^3+((n+1)-1)^3<\frac{(n+1)^4}{4}<1^3+2^3+ ⋯ +n^3+(n+1)^3
  \newline \text {making the equation simple}
  \newline 1^3+2^3+ ⋯ +(n−1)^3+((n+1)-1)^3 = 1^3+2^3+ ⋯ +(n−1)^3+n^3
  \newline \frac{(n+1)^4}{4} = \frac{n^4+4n^3+6n^2+4n+1}{4}
  \newline 1^3+2^3+ ⋯ +n^3+(n+1)^3 = 1^3+2^3+ ⋯ +n^3 + n^3+3n^2+3n+1
  \newline \text{we have to prove this  inequality equation}
  \newline 1^3+2^3+ ⋯ +(n−1)^3+n^3<\frac{n^4+4n^3+6n^2+4n+1}{4}<1^3+2^3+ ⋯ +n^3 + n^3+3n^2+3n+1
  \newline
  \newline \text{first the left part}
  \newline 1^3+2^3+ ⋯ +(n−1)^3+n^3<\frac{n^4+4n^3+6n^2+4n+1}{4} \text{ we can remove } n^3 \text{ from the both side}
  \newline 1^3+2^3+ ⋯ +(n−1)^3 < \frac{n^4+4n^3+6n^2+4n+1}{4} - n^3 = \frac{n^4+6n^2+4n+1}{4}
  \newline 1^3+2^3+ ⋯ +(n−1)^3 < \frac{n^4}{4} + \frac{6n^2+4n+1}{4}
  \newline \frac{6n^2+4n+1}{4} \text{ is positive since n is the positive integer and}
  \newline \text{by the assumption }1^3+2^3+ ⋯ +(n−1)^3 < \frac{n^4}{4} \text{ is also true}
  \newline \text{Therefore }1^3+2^3+ ⋯ +(n−1)^3+n^3<\frac{n^4+4n^3+6n^2+4n+1}{4} \text{ is true}
  \newline 
  \newline \text{Now we are going to prove the right part of the equation }
  \newline \frac{n^4+4n^3+6n^2+4n+1}{4}<1^3+2^3+ ⋯ +n^3 + n^3+3n^2+3n+1
  \newline \text{remove }n^3+1.5n^2+n+0.25 \text{ from the both side}
  \newline \frac{n^4+4n^3+6n^2+4n+1}{4} - (n^3+1.5n^2+n+0.25) = \frac{n^4}{4}
  \newline 1^3+2^3+ ⋯ +n^3 + n^3+3n^2+3n+1 - (n^3+1.5n^2+n+0.25) = 1^3+2^3+ ⋯ +n^3 +1.5n^2+2n+0.75
  \newline \text{by the assumption } \frac{n^4}{4}<1^3+2^3+ ⋯ +n^3 \text{ is true}
  \newline \text{Since n is positve integer } 1.5n^2+2n+0.75 \text{ is also positive }
  \newline \text{Therefore } \frac{n^4+4n^3+6n^2+4n+1}{4}<1^3+2^3+ ⋯ +n^3 + n^3+3n^2+3n+1 \text{ is true}
  \newline
  \newline \text{Finally } 1^3+2^3+ ⋯ +(n−1)^3+((n+1)-1)^3<\frac{(n+1)^4}{4}<1^3+2^3+ ⋯ +n^3+(n+1)^3 \text{ is true}
  \newline
  \newline \text{by the induction the equation} 1^3+2^3+ ⋯ +(n−1)^3<\frac{n^4}{4}<1^3+2^3+ ⋯ +n^3 \text{ is true}
  $$
  
  



* $$
  \newline \text {Let } P(n) \text{ denote the following statement: }1+2+ \dots +n=\frac{1}{8}(2n+1)^2
  $$

  - *(a) Prove that if P(k) is true for an integer k then P(k+1)is also true.*
    $$
    \newline \text{Since we are assumming P(k) is true }
    \newline 1+2+ \dots +k = \frac{1}{8}(2k+1)^2 \text{ is true}
    \newline
    \newline P(k+1) \rightarrow 1+2+ \dots +k+k+1 = \frac{1}{8}(2(k+1)+1)^2
    \newline \frac{1}{8}(2(k+1)+1)^2 = \frac{1}{8}(2k+3)^2=\frac{1}{8}(4k^2+12k+9)=\frac{1}{8}(2k+1)^2+\frac{1}{8}(8k+8)
    \newline \text{by the assumption }\frac{1}{8}(2k+1)^2=1+2+ \dots +k
    \newline
    \newline \text{Therefore }\frac{1}{8}(2(k+1)+1)^2 =1+2+ \dots +k+\frac{1}{8}(8k+8)=1+2+ \dots +k+k+1
    \newline \text{In conclusion }1+2+ \dots +k+k+1 = \frac{1}{8}(2(k+1)+1)^2 \text{ is true}
    $$
    
  - *(b) Criticize the statement: "By induction it follows that P(n) is true for all n."*
    $$
    \newline \text{However the statement "By induction it follows that P(n) is true for all n." is not true}
    \newline \text{The first step of proving by induction is showing the base case is correct.}
    \newline \text{In this case we have to show that P(1) is true as a base case.}
    \newline \text{However } P(1) \rightarrow 1= \frac{1}{8}(2\times1+1)^2 \text{ is false.}
    \newline \text{Since the base case is not true we can't say that "By induction it follows that P(n) is true for all n." }
    $$
    
  - *(c) Amend P(k) by changing equality to an inequality that is true for all positive integer n.*
    $$
    \newline \text{Changing equality }
    \newline 1+2+ \dots +n=\frac{1}{8}(2n+1)^2
    \newline \text{to inequality}
    \newline 1+2+ \dots +n<\frac{1}{8}(2n+1)^2
    \newline 
    \newline \text{Proving amended P(k) is true for all positive integer n by induction}
    \newline
    \newline \text{Step.1}
    \newline \text{Check base case is true}
    \newline \text{for }n=1 
    \newline 1 < \frac{1}{8}(2\times1+1)^2= \frac{9}{8} \text{ is true}
    \newline
    \newline \text{Step.2}
    \newline \text{Assume that }n=k\text{ is true and prove }n=k+1 \text{is also true} 
    \newline \text{By the assumption } 1+2+ \dots +k<\frac{1}{8}(2k+1)^2 \text{ is true}
    \newline 
    \newline \text{For }n=k+1
    \newline 1+2+ \dots +k +k+1<\frac{1}{8}(2(k+1)+1)^2
    \newline 1+2+ \dots +k +k+1<\frac{1}{8}(4k^2+12k+9)=\frac{1}{8}(2k+1)^2+(k+1)
    \newline \text{we can remove } k+1 \text{ from the both side of the inequality equation}
    \newline 1+2+ \dots +k<\frac{1}{8}(2k+1)^2 \text{ by the assumption the inequality is true}
    \newline \text {Therefore by the induction Amended }P(k) \text{ is true for all positive integer n}
    $$
    
    $$
    
    $$
    

