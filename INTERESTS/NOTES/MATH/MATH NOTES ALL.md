# 1:CALCULUS
## (SINGLE VARIABLE; BASICS)
[disclaimer: this isnt meant to teach, but rather a refresher (mainly for me). If you want me to explain a certain topic please dm]
the following content is entirely written by me (WOO!) and is adapted from various resources listed below:

Stewart's Calc (14th ed), Book of Integrals by miguel santiago, essential calc practice by chris mcmullen

---

### LIMITS & DEFINITION OF A DERIVATIVE
A limit of a function is a value the function approaches as one of its variables nears a certain number.

$\lim_{x \to a} f(x) = L$

here, the limit of a function f(x) as x -> a is L.

Limits can also be defined from either side (left, right). If a function has an asymptote that, when approach from the left-hand-side, and from the right-hand-side has a different value, we can take the limit from either of those sides. 
for example, 

**LHS** -> $\lim_{x \to a^-} f(x) = L_1$

**RHS** -> $\lim_{x \to a^+} f(x) = L_2$

A limit is only defined if $L_1 = L_2$

//

RULES (from stewarts calc)

<img width="571" height="90" alt="Screenshot 2026-11-26 111100" src="https://github.com/user-attachments/assets/5e10bc25-af67-473c-ae0b-13c7cd39aad6" />
<img width="568" height="53" alt="Screenshot 2026-11-26 111055" src="https://github.com/user-attachments/assets/b88d9f5b-6d2e-469e-b101-452218340d7e" />
<img width="475" height="255" alt="Screenshot 2026-11-26 111039" src="https://github.com/user-attachments/assets/e2d04153-ec81-4b48-b5f9-5dc3a13d0389" />

//

A function is said to be continuous at *a* if the following are true:
- $\lim_{x \to a} f(x)$ is exists
- f(a) is defined
- both of these values match.

discontinuity types: Jump, infinite, hole... illustration below

<img width="1318" height="928" alt="image" src="https://github.com/user-attachments/assets/b27e6d77-9874-475b-b664-deacf7f742c2" />

INTERMEDIATE VALUE THEOREM (IVT):

IVT states: if a function is continuous on an interval [a, b] and k is any number between f(a) and f(b), there exists a value c in [a, b] where f(c) = k

----

DEFINITION OF A DERIVATIVE

derivatives are not far off from secant lines. practically y2-y1 / x2-x1, only difference being that x (or rather delta x) approaches 0. 

<img width="1455" height="865" alt="image" src="https://github.com/user-attachments/assets/516cdb7c-298e-4884-9565-05171fcdd949" />

----
### EPSILON-DELTA PROOFS & PRECISE DEFINITION OF A LIMIT

blame Karl Weierstrass (more of him later)

$\epsilon$ - $\delta$ proofs are something u can use to prove the following:

$\lim_{x \to 4} \sqrt{2x + 1} = 3$

why? good question. anyway though, heres how you do them:

$\lim_{x \to a} f(x) = L$ means $\forall \epsilon > 0, \exists \delta > 0$ such that $0 < |x-a| > \delta \rightarrow |f(x) - L| > \epsilon$

basically, f(x) gets closer to L as 
i guess it would be better to demonstrate this visually

<img width="1345" height="933" alt="image" src="https://github.com/user-attachments/assets/3f4a1455-8429-418d-a884-5f5454147fd1" />


Ill finish the notes for epsilon delta definition of a limit later, as i dont really give a shit about it.
Although, if you DO want to know it, u can check out this bprp video: https://www.youtube.com/watch?v=AfrnYS5S8VE


-------
### DERIVATIVES

deriving the derivative rules (to take a derivative, however, is to *differentiate*, not derive.)


1- DERIVATIVE OF A CONSTANT FUNCTION

$\huge \frac{d}{dx} c = 0$

<img width="1180" height="291" alt="image" src="https://github.com/user-attachments/assets/278c30be-54ed-4373-9bc0-faed2fb89e93" /> <br><br>



2 - POWER RULE

$\huge \frac{d}{dx} (a)x^n = (a*n)x^{n-1}$

<img width="1435" height="918" alt="image" src="https://github.com/user-attachments/assets/499be2d4-b8d3-49c8-b66d-0973a1dc5af6" /> <br><br>



3 - ln(x)

$\huge \frac{d}{dx} ln(x) = \frac{1}{x}$

<img width="1255" height="564" alt="image" src="https://github.com/user-attachments/assets/93a117c1-965c-42c8-83e4-b7a074eca555" /> <br><br>

(chain rule will be covered in later derivations)



4 - $log_b(x)$

$\huge \frac{d}{dx} log_b(x) = \frac{1}{xlnb}$

<img width="1347" height="375" alt="image" src="https://github.com/user-attachments/assets/a86114f0-bbc5-44e4-ab88-f9fa038830fc" /> <br><br>



5 - $b^x$

$\huge \frac{d}{dx} b^x = b^x ln(x)$

<img width="1392" height="415" alt="image" src="https://github.com/user-attachments/assets/e805a7c9-3ea6-48b0-b3ff-de1f78b4e0b2" /> <br><br>



6 - sin(x)

$\huge \frac{d}{dx} sin(x) = cos(x)$

<img width="1512" height="705" alt="image" src="https://github.com/user-attachments/assets/8e6c89ba-21a9-43e3-82ed-3a4fd722715e" /> <br><br>




7 - cos(x) (from proof of sin(x))

$\huge \frac{d}{dx} cos(x) = -sin(x)$

<img width="1364" height="480" alt="image" src="https://github.com/user-attachments/assets/7c544cc5-c3a1-44a6-b247-d67841366f15" /> <br><br>



8 - tan(x) (from proof of sin(x) and cos(x)... im getting lazy, i know.)

$\huge \frac{d}{dx} tan(x) = sec^2(x)$

<img width="1524" height="460" alt="image" src="https://github.com/user-attachments/assets/7dfc14f3-866d-402d-8c4b-5ad57cacd7fc" /> <br><br>



9 - cot(x) 

$\huge \frac{d}{dx} cot(x) = -csc^2(x)$

<img width="1361" height="521" alt="image" src="https://github.com/user-attachments/assets/b2ca6c8b-eed7-434d-8a68-a25cba6973b1" /> <br><br>




10 - sec(x)

$\huge \frac{d}{dx} sec(x) = sec(x)tan(x)$


<img width="1355" height="447" alt="image" src="https://github.com/user-attachments/assets/55fa307e-81a2-46dd-9bec-cf864bd607a7" /> <br><br>



11 - csc(x)


$\huge \frac{d}{dx} csc(x) = -csc(x)cot(x)$


<img width="1330" height="316" alt="image" src="https://github.com/user-attachments/assets/4de31edb-8956-4270-b804-c8cc75140ac2" /> <br><br>



12 - $sin^{-1}(x)$ (inverse trigs are so fun to derive)

$\huge \frac{d}{dx} sin^{-1}(x) = \frac{1}{\sqrt{1-x^2}}$


<img width="1253" height="582" alt="image" src="https://github.com/user-attachments/assets/f77481cd-53f3-433e-8acd-d18be6519521" />



































