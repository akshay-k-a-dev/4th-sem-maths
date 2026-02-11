<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Exam Pattern Analysis (2023–2024 Based)

## Paper \& Scheme

- **Course**: MTS4C04 – Mathematics 4 (Complementary for BSc CS)
- **University**: Calicut
- **Time**: 2 hours
- **Maximum marks**: 60


### Section Structure (from 2023 \& 2024 QPs)

- **Section A – Short Answer**
    - Instruction: **“Answer any number of questions. Each question carries 2 marks. Ceiling is 20.”**
    - Around **12 questions** printed.
    - You may attempt all, but **only first 10 correct** effectively counted → 10 × 2 = 20.
- **Section B – 5-Mark Questions**
    - Instruction: **“Answer any number of questions. Each question carries 5 marks. Ceiling is 30.”**
    - ~7 questions printed.
    - You may attempt all, but **only best 6** count → 6 × 5 = 30.
- **Section C – 10-Mark Questions**
    - 2 questions printed.
    - **Answer any one** (no ceiling) → 1 × 10 = 10.


### Practical Pass Target (≥26 marks)

- **Section A**: aim **8–10 correct answers** → 16–20 marks
- **Section B**: aim **2–3 good answers** → 10–15 marks
- **Section C**: **one long answer** (even partial) → 3–6 marks

Total ≈ 29–35 → safe pass.

# Question Pattern Breakdown

## By Section

### Section A – 2-Mark Questions

Typical question types (seen in 2023 \& 2024):

**Module I – First Order ODEs**

- Solve very simple **separable** or **linear** differential equation.
- Check **exactness** or find parameter $k$ that makes a DE exact.

**Module II – Higher Order ODEs**

- Check **linear dependence/independence** or fundamental set of solutions.
- Use **reduction of order** to find a second solution from a given solution.
- Simple **constant-coefficient ODE** or reconstruct DE from a given solution.

**Module III – Laplace Transforms**

- Direct **Laplace transform** of simple functions.
- Simple **inverse Laplace** using partial fractions.
- Write a **piecewise** function using **unit step** and find its Laplace transform.

**Module IV – Fourier Series \& PDE**

- Show given functions are **orthogonal** on an interval.
- **Classify** a PDE as elliptic / parabolic / hyperbolic using coefficients.

***

### Section B – 5-Mark Questions

Typical patterns (2023, 2024 + supported by 2021, 2022):

**Module I**

- Solve first order DEs:
    - Linear, separable, exact, Bernoulli, or substitution-based.
    - Sometimes includes initial value condition.

**Module II**

- Solve **second-order linear ODEs with constant coefficients** (homogeneous or with forcing).
- **Cauchy–Euler** equations.
- **Boundary value problems** leading to eigenvalues \& eigenfunctions.

**Module III**

- Solve **2nd-order ODE using Laplace transform** (with given initial conditions).
- **Inverse Laplace transforms** of rational functions with parameters.

**Module IV**

- **Fourier series** on a symmetric interval $[-L,L]$.
- **Half-range sine or cosine series** on $[0,L]$.

***

### Section C – 10-Mark Question (Answer Any One)

The pattern in both 2023 and 2024:

- **Q20**: Solve a **higher-order IVP using Laplace transform**.
- **Q21**: Obtain the **Fourier series** (often piecewise-defined function on $[-L,L]$).

So Section C is effectively:

> **Option 1**: Laplace transform method for IVP
> **Option 2**: Full Fourier series expansion

# Predicted Important Question Models

Based mainly on 2023–2024, validated with 2021–2022:

1. **First-order linear ODE** (general solution or IVP).
2. **Separable ODE** solved by simple integration.
3. **Exact DE**:
    - Check exactness.
    - Find parameter $k$ for exactness.
    - Solve exact equation.
4. **Bernoulli equation** reduced to linear.
5. **Linear independence / fundamental set of solutions** (Wronskian or equivalent).
6. **Reduction of order** – find second solution given one solution.
7. **Second-order linear ODE with constant coefficients**:
    - Complementary solution via characteristic equation.
    - Particular solution via undetermined coefficients.
8. **Cauchy–Euler equation** (equidimensional form).
9. **Simple BVP** $y'' + \lambda y = 0$ with Dirichlet BCs ⇒ eigenvalues/eigenfunctions.
10. **Laplace transform** of functions (standard + combinations of exponentials and trig).
11. **Inverse Laplace** using partial fractions (linear/quadratic factors).
12. **IVP via Laplace transform** (2nd/3rd order) – stable 10-mark model.
13. **Orthogonality** of two given functions on $[a,b]$.
14. **PDE classification** via $B^2 - 4AC$.
15. **Fourier series** on $[-L,L]$ (often polynomials or simple piecewise).
16. **Half-range sine or cosine series** on $[0,L]$.

These models are the core of scoring.

# Section Wise Preparation Notes

## Module I – Ordinary Differential Equations (First Order)

### Core Concepts

- **Classification**:
    - Order, degree, linear vs nonlinear.
    - Types: separable, linear, exact, Bernoulli.
- **General forms**:
    - Separable: $\frac{dy}{dx} = g(x)h(y)$.
    - Linear: $\frac{dy}{dx} + P(x)y = Q(x)$.
    - Exact: $M(x,y)dx + N(x,y)dy = 0$ with $M_y = N_x$.
    - Bernoulli: $\frac{dy}{dx} + P(x)y = Q(x)y^n$.
- **Initial Value Problems (IVPs)**: apply condition $y(x_0) = y_0$.


### Important Formulas / Definitions

- **Integrating factor for linear DE**:

$$
IF = e^{\int P(x)\,dx}
$$

Solution:

$$
y \cdot IF = \int Q(x)\cdot IF\,dx + C
$$
- **Exactness condition**:

$$
\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}
$$
- **Bernoulli substitution**:

$$
\frac{dy}{dx} + P(x)y = Q(x)y^n,\ n\ne 0,1 \Rightarrow v = y^{1-n}
$$


### Concept Summary Bullets

- Recognize DE type quickly (separable vs linear vs exact).
- Always rewrite to standard linear form before finding IF.
- For exact: treat solution as level curves of a potential function $\phi(x,y)$.
- For IVPs: solve general solution first, then apply initial condition.


### Common Mistakes

- Forgetting to include constant of integration.
- Miscomputing integrating factor exponent.
- For exact equations: skipping the “function of other variable” step.


### How Examiners Frame Questions (Module I)

- **Section A**:
    - Quick solving of a simple linear/separable ODE.
    - Parameter $k$ to make an equation exact.
- **Section B**:
    - More complex DE (exact or Bernoulli or substitution) with full solution.

***

## Module II – Higher Order Differential Equations

### Core Concepts

- **Linear 2nd-order ODE**:

$$
a_2(x)y'' + a_1(x)y' + a_0(x)y = g(x)
$$
- **Constant coefficients**:

$$
a y'' + b y' + c y = g(x)
$$

Characteristic equation: $a r^2 + b r + c = 0$.
- **Non-homogeneous solution structure**:

$$
y = y_c + y_p
$$

where $y_c$ solves the homogeneous equation and $y_p$ is a particular solution.
- **Cauchy–Euler**:

$$
x^2 y'' + a x y' + b y = g(x)
$$

Try $y = x^m$ for homogeneous part.
- **Reduction of order**:
    - Given solution $y_1(x)$ of homogeneous equation.
    - Find second solution $y_2 = v(x)y_1(x)$.
- **Wronskian**:

$$
W(y_1,y_2) = \begin{vmatrix} y_1 & y_2 \\ y_1' & y_2' \end{vmatrix}
$$

Non-zero on interval ⇒ linearly independent.
- **Boundary value problems**:
    - Typical model: $y'' + \lambda y = 0$ with $y(0)=0, y(L)=0$.


### Important Formulas

- Cases for characteristic roots $r$:
    - Distinct real $r_1,r_2$: $y_c = c_1 e^{r_1 x} + c_2 e^{r_2 x}$.
    - Repeated $r$: $y_c = (c_1 + c_2 x)e^{rx}$.
    - Complex $a \pm ib$: $y_c = e^{ax}(c_1\cos bx + c_2\sin bx)$.
- **Reduction of order shortcut**:

$$
y_2(x) = y_1(x)\int \frac{e^{-\int P(x)\,dx}}{[y_1(x)]^2}\,dx
$$

For equation in standard form:

$$
y'' + P(x)y' + Q(x)y = 0
$$
- **BVP eigenvalues** for $y'' + \lambda y = 0$ with $y(0)=0, y(L)=0$:
    - $\lambda_n = (n\pi/L)^2,\ n=1,2,\dots$
    - $y_n(x) = \sin(n\pi x/L)$


### Concept Summary Bullets

- Master the **three root cases** of characteristic equation.
- Skill with **undetermined coefficients** for $g(x)$ as polynomial / exponential / trig.
- **Cauchy–Euler**: power-law behaviour; convert to algebra in $m$.
- Know how eigenvalue problems produce **discrete spectrum**.


### Common Mistakes

- Wrong sign in characteristic equation or roots.
- Forgetting to multiply trial $y_p$ by $x$ (or higher power) when it overlaps with $y_c$.
- Ignoring trivial solution in BVP; not enforcing non-triviality.


### How Examiners Frame Questions (Module II)

- **Section A**:
    - Linear independence / Wronskian.
    - Reduction of order using one given solution.
- **Section B**:
    - Solve non-homogeneous constant-coefficient ODE.
    - Cauchy–Euler equation.
    - Simple eigenvalue BVP.

***

## Module III – Laplace Transforms

### Core Concepts

- **Definition**:

$$
\mathcal{L}\{f(t)\} = \int_0^\infty e^{-st} f(t)\,dt
$$
- **Linearity**:

$$
\mathcal{L}\{af + bg\} = aF(s) + bG(s)
$$
- **Standard transforms**:
    - $\mathcal{L}\{1\} = \frac{1}{s}$
    - $\mathcal{L}\{t^n\} = \frac{n!}{s^{n+1}}$
    - $\mathcal{L}\{e^{at}\} = \frac{1}{s-a}$
    - $\mathcal{L}\{\sin at\} = \frac{a}{s^2 + a^2}$
    - $\mathcal{L}\{\cos at\} = \frac{s}{s^2 + a^2}$
- **Derivatives**:
    - $\mathcal{L}\{y'\} = sY(s) - y(0)$
    - $\mathcal{L}\{y''\} = s^2Y(s) - s y(0) - y'(0)$
    - $\mathcal{L}\{y'''\} = s^3Y(s) - s^2y(0) - s y'(0) - y''(0)$
- **Shifts and unit step**:
    - $\mathcal{L}\{e^{at}f(t)\} = F(s-a)$
    - $f(t) = g(t-a)u(t-a) \Rightarrow \mathcal{L}\{f\} = e^{-as}G(s)$
- **Inverse Laplace**:
    - Partial fraction decomposition + use of standard inverse transforms.


### Concept Summary Bullets

- Memorize basic table and derivative formulas.
- Be comfortable with **partial fractions**.
- Understand how to convert DE + initial conditions into algebraic equation in $Y(s)$.


### Common Mistakes

- Sign errors in initial-value terms in derivative transforms.
- Wrong factoring or decomposition in partial fractions.
- Confusing shift directions ($s-a$ vs $s+a$, $e^{-as}$ factors).


### How Examiners Frame Questions (Module III)

- **Section A**:
    - Direct $\mathcal{L}\{f(t)\}$ for standard $f(t)$.
    - $\mathcal{L}^{-1}\{F(s)\}$ using simple expressions.
    - Represent piecewise $f(t)$ by unit step + find Laplace.
- **Section B**:
    - Solve 2nd-order linear ODE using Laplace transforms.
    - Inverse Laplace of rational function in reasonably non-trivial form.
- **Section C**:
    - Large IVP (2nd or 3rd order) solved via Laplace.

***

## Module IV – Fourier Series \& PDE

### Core Concepts

- **Inner product**:

$$
\langle f,g\rangle = \int_a^b f(x)g(x)w(x)\,dx
$$
- **Orthogonality**:
    - $f,g$ orthogonal if $\langle f,g\rangle = 0$.
- **Fourier series on $[-L,L]$**:

$$
f(x) \sim \frac{a_0}{2} + \sum_{n=1}^\infty \left(a_n\cos\frac{n\pi x}{L} + b_n\sin\frac{n\pi x}{L}\right)
$$

where

$$
a_0 = \frac{1}{L}\int_{-L}^L f(x)\,dx,\quad
a_n = \frac{1}{L}\int_{-L}^L f(x)\cos\frac{n\pi x}{L}\,dx,\quad
b_n = \frac{1}{L}\int_{-L}^L f(x)\sin\frac{n\pi x}{L}\,dx
$$
- **Half-range cosine series (even extension)** on $[0,L]$:

$$
f(x) \sim \frac{a_0}{2} + \sum_{n=1}^\infty a_n\cos\frac{n\pi x}{L}
$$

with

$$
a_0 = \frac{2}{L}\int_{0}^L f(x)\,dx,\quad
a_n = \frac{2}{L}\int_0^L f(x)\cos\frac{n\pi x}{L}\,dx
$$
- **Half-range sine series (odd extension)** on $[0,L]$:

$$
f(x) \sim \sum_{n=1}^\infty b_n\sin\frac{n\pi x}{L}
$$

with

$$
b_n = \frac{2}{L}\int_0^L f(x)\sin\frac{n\pi x}{L}\,dx
$$
- **PDE classification** for

$$
A u_{xx} + B u_{xy} + C u_{yy} + \dots = 0:
$$
    - Compute $D = B^2 - 4AC$:
        - $D>0$: hyperbolic
        - $D=0$: parabolic
        - $D<0$: elliptic


### Concept Summary Bullets

- Use symmetry: even $f$ ⇒ cosine series only; odd $f$ ⇒ sine series only.
- Memorize coefficient formulas and interval length $L$.
- For orthogonality, set up and evaluate simple integrals.


### Common Mistakes

- Wrong value of $L$ or limits.
- Missing 1/L or 2/L factors.
- Forgetting that even functions have only cos terms, odd have only sin terms.


### How Examiners Frame Questions (Module IV)

- **Section A**:
    - Orthogonality and PDE classification.
- **Section B**:
    - Full Fourier or half-range expansions.
- **Section C**:
    - Fourier series of a piecewise function.


# Problem Type Solution Frameworks (Detailed Step-by-Step)

Each model includes:

- Problem type name
- Stepwise algorithm
- Generic **example question** with variables (no fixed numbers)

***

## 1. First-Order Linear ODE (with or without IVP)

**Problem Type Name**: First-order linear differential equation

**When it is asked**

- Section A: short “Solve …”.
- Section B: full 5-mark, sometimes IVP.

**Required concepts**

- Standard form: $\dfrac{dy}{dx} + P(x)y = Q(x)$
- Integrating factor.

**Step-by-step solving**

Step 1: Identify given data

- Recognize linear pattern and any initial condition $y(x_0)=y_0$.

Step 2: Identify required output

- General solution or particular solution (IVP).

Step 3: Select framework

- Linear integrating-factor method.

Step 4: Apply method logically

1. Rewrite DE as $dy/dx + P(x)y = Q(x)$.
2. Compute $IF = e^{\int P(x)\,dx}$.
3. Multiply both sides by $IF$:

$$
IF \cdot \frac{dy}{dx} + IF \cdot P(x) y = IF \cdot Q(x)
$$
4. Left side becomes derivative of product:

$$
\frac{d}{dx}(y \cdot IF) = Q(x)\cdot IF
$$
5. Integrate:

$$
y \cdot IF = \int Q(x)\cdot IF\,dx + C
$$
6. Solve for $y(x)$:

$$
y(x) = \frac{1}{IF}\Big(\int Q(x)\cdot IF\,dx + C\Big)
$$
7. For IVP, substitute $x=x_0, y=y_0$ to find $C$.

Step 5: Present final answer properly

- Clearly write standard form, IF, integrated expression, and final $y(x)$.

**Common traps**

- Sign mistakes in $\int P(x)dx$.
- Forgetting constant $C$ or not using IVP condition.

**Time management**

- Section A: 2–3 minutes.
- Section B: 7–8 minutes.

**Example question (variables only)**

> Solve the initial value problem

> $$
> \frac{dy}{dx} + (a x + b)\,y = c e^{d x}, \quad y(x_0) = y_0,
>
$$

> where $a,b,c,d,x_0,y_0$ are constants.

***

## 2. Separable First-Order ODE

**Problem Type Name**: Separable differential equation

**When it is asked**

- Section A (simple form).
- Section B (slightly more complicated integrals).

**Required concepts**

- Identify form $dy/dx = g(x)h(y)$.

**Step-by-step solving**

Step 1: Identify given data

- ODE of product form in x and y.

Step 2: Identify required output

- General relation between x and y.

Step 3: Select framework

- Separation of variables.

Step 4: Apply method logically

1. Rewrite:

$$
\frac{dy}{dx} = g(x)h(y) \Rightarrow \frac{dy}{h(y)} = g(x)\,dx
$$
2. Integrate both sides:

$$
\int \frac{dy}{h(y)} = \int g(x)\,dx + C
$$
3. If possible, solve explicitly for $y(x)$.

Step 5: Present final answer properly

- Implicit or explicit expression; include constant.

**Common traps**

- Forgetting to separate variables completely.
- Missing constant $C$.

**Example question**

> Solve the differential equation

> $$
> \frac{dy}{dx} = k x^m y^n,
>
$$

> where $k,m,n$ are constants with $n \neq 1$ and $m \neq -1$.

***

## 3. Exact Differential Equation (including “Find k so that exact”)

**Problem Type Name**: Exact DE and parameter for exactness

**When it is asked**

- Section A: parameter $k$ for exactness.
- Section B: full solution of exact DE.

**Required concepts**

- Exactness test: $M_y = N_x$.
- Potential function $\phi(x,y)$.

**Step-by-step solving**

Step 1: Identify given data

- Write equation as:

$$
M(x,y)\,dx + N(x,y)\,dy = 0
$$

Step 2: Identify required output

- Either parameter $k$, or full solution $\phi(x,y)=C$.

Step 3: Select framework

- Exactness test + potential function.

Step 4: Apply method logically

- **For parameter $k$**:

1. Compute $M_y$ and $N_x$.
2. Set $M_y = N_x$, solve for $k$.
- **For solving exact DE**:

1. Check $M_y = N_x$ to confirm exactness.
2. Integrate $M$ w.r.t x:
$\phi(x,y) = \int M(x,y)\,dx + h(y)$.
3. Differentiate $\phi$ w.r.t y and equate to $N(x,y)$ to find $h'(y)$.
4. Integrate to get $h(y)$.
5. Result: $\phi(x,y) = C$.

Step 5: Present final answer properly

- Show computation of $M_y$ and $N_x$ clearly.
- Final solution as $\phi(x,y) = C$.

**Common traps**

- Incorrect partial derivatives.
- Forgetting the $h(y)$ (or $g(x)$) term when integrating.

**Example question**

> (a) Find the value of the constant $k$ for which

> $$
> \big( a x^2 y + k y \big)\,dx + \big( b x y^2 + c x \big)\,dy = 0
>
$$

> is an exact differential equation, where $a,b,c$ are given constants.
> (b) Solve the resulting exact differential equation.

***

## 4. Bernoulli Equation

**Problem Type Name**: Bernoulli-type first-order DE

**When it is asked**

- Section B (5 marks) occasionally.

**Required concepts**

- Bernoulli form: $dy/dx + P(x)y = Q(x)y^n$.

**Step-by-step solving**

Step 1: Identify given data

- Confirm equation matches Bernoulli form with $n \neq 0,1$.

Step 2: Identify required output

- General solution.

Step 3: Select framework

- Bernoulli substitution.

Step 4: Apply method logically

1. Write:

$$
\frac{dy}{dx} + P(x)y = Q(x)y^n
$$
2. Divide by $y^n$:

$$
y^{-n}\frac{dy}{dx} + P(x)y^{1-n} = Q(x)
$$
3. Substitute $v = y^{1-n}$. Then:

$$
\frac{dv}{dx} = (1-n)y^{-n}\frac{dy}{dx}
$$
4. Express equation in terms of $v$ and $dv/dx$ ⇒ linear in $v$.
5. Solve the resulting linear DE using integrating factor.
6. Back-substitute $y = v^{1/(1-n)}$.

Step 5: Present final answer properly

- Show substitution clearly; give final y(x).

**Example question**

> Solve the Bernoulli differential equation

> $$
> \frac{dy}{dx} + P(x)y = Q(x) y^n,
>
$$

> where $P(x)$ and $Q(x)$ are known functions and $n \neq 0,1$.

***

## 5. Linear Independence / Fundamental Set (Wronskian)

**Problem Type Name**: Linear independence of solutions

**When it is asked**

- Section A (2 marks).

**Required concepts**

- Wronskian $W(y_1,y_2) = y_1 y_2' - y_2 y_1'$.

**Step-by-step solving**

Step 1: Identify given data

- Two (or more) functions claimed to be solutions.

Step 2: Identify required output

- Show they are linearly independent (or dependent).

Step 3: Select framework

- Compute Wronskian on given interval.

Step 4: Apply method logically

1. Compute derivatives $y_1', y_2'$.
2. Form Wronskian:

$$
W(x) = 
\begin{vmatrix}
y_1 & y_2\\
y_1'& y_2'
\end{vmatrix}
= y_1 y_2' - y_2 y_1'
$$
3. Simplify.
4. If $W(x)\neq 0$ for all x in interval, they are linearly independent.

Step 5: Present final answer properly

- Display determinant, show non-zero expression.

**Example question**

> Show that the functions

> $$
> y_1(x) = e^{a x}, \quad y_2(x) = x e^{a x},
>
$$

> where $a$ is a constant, are linearly independent on an interval $(\alpha,\beta)$.

***

## 6. Reduction of Order

**Problem Type Name**: Reduction of order to find second solution

**When it is asked**

- Section A or Section B.

**Required concepts**

- Known solution $y_1(x)$ of homogeneous 2nd-order DE.

**Step-by-step solving**

Step 1: Identify given data

- ODE in form $y'' + P(x)y' + Q(x)y = 0$, with known solution $y_1(x)$.

Step 2: Identify required output

- Second linearly independent solution $y_2(x)$.

Step 3: Select framework

- Use reduction-of-order formula.

Step 4: Apply method logically

1. Use:

$$
y_2(x) = y_1(x)\int \frac{e^{-\int P(x)\,dx}}{[y_1(x)]^2}\,dx
$$
2. Compute $\int P(x)\,dx$.
3. Form integrand $\dfrac{e^{-\int P}}{y_1^2}$.
4. Integrate and multiply by $y_1(x)$.

Step 5: Present final answer properly

- Show main steps; final $y_2(x)$ expression.

**Example question**

> The function

> $$
> y_1(x) = e^{p x}
>
$$

> is a solution of

> $$
> y'' - 2p y' + p^2 y = 0,
>
$$

> where $p$ is a constant. Using reduction of order, find a second linearly independent solution $y_2(x)$.

***

## 7. Constant-Coefficient Linear ODE (Homogeneous \& Non-homogeneous)

**Problem Type Name**: Linear ODE with constant coefficients

**When it is asked**

- Section B (5 marks).
- Used indirectly in Laplace IVP questions.

**Required concepts**

- Characteristic equation; complementary + particular solutions.

**Step-by-step solving**

Step 1: Identify given data

- ODE of type:

$$
y'' + a y' + b y = g(x)
$$

Step 2: Identify required output

- General solution (and sometimes satisfy initial conditions).

Step 3: Select framework

- Solve homogeneous part then find particular.

Step 4: Apply method logically

1. Solve characteristic equation:

$$
r^2 + a r + b = 0
$$

to get roots.
2. Form complementary solution $y_c$:
    - Distinct real: $c_1e^{r_1x} + c_2e^{r_2x}$.
    - Repeated: $(c_1 + c_2 x)e^{rx}$.
    - Complex: $e^{ax}(c_1\cos bx + c_2\sin bx)$.
3. Choose trial particular $y_p$ based on forcing $g(x)$:
    - Exponential $e^{d x}$: try $A e^{dx}$.
    - Polynomial: polynomial of same degree.
    - Sin/cos: $A\cos\omega x + B\sin\omega x$.
4. If trial overlaps with any term of $y_c$, multiply by $x$ (or $x^2$ if necessary).
5. Substitute $y_p$ and its derivatives into ODE and solve for unknown coefficients.
6. Final solution: $y = y_c + y_p$.
7. If IVP: apply given values of $y(x_0), y'(x_0)$ to find constants.

Step 5: Present final answer properly

- Clearly separate complementary and particular parts.

**Common traps**

- Not adjusting trial particular when it clashes with $y_c$.
- Algebra errors when solving for coefficients.

**Example question**

> Solve the differential equation

> $$
> y'' + a y' + b y = c e^{d x},
>
$$

> where $a,b,c,d$ are constants and the roots of $r^2 + a r + b = 0$ are distinct.

***

## 8. Cauchy–Euler Equation

**Problem Type Name**: Cauchy–Euler (equidimensional) ODE

**When it is asked**

- Section B (5 marks).

**Required concepts**

- Homogeneous equation of form:

$$
x^2 y'' + p x y' + q y = 0
$$

**Step-by-step solving**

Step 1: Identify given data

- Check for the special powers of x: $x^2 y'', x y'$.

Step 2: Identify required output

- General solution.

Step 3: Select framework

- Try $y = x^m$.

Step 4: Apply method logically

1. Assume $y = x^m$; then

$$
y' = m x^{m-1},\quad y'' = m(m-1) x^{m-2}.
$$
2. Substitute into ODE:

$$
x^2 m(m-1) x^{m-2} + p x \cdot m x^{m-1} + q x^m = 0
\Rightarrow m(m-1) + p m + q = 0
$$
3. Solve the algebraic equation in $m$:

$$
m^2 + (p-1)m + q = 0
$$
4. Use root cases to form general solution (similar to constant-coefficient ODEs).

Step 5: Present final answer properly

- State $m$-equation, its roots, and final $y(x)$.

**Example question**

> Solve the Cauchy–Euler differential equation

> $$
> x^2 y'' + p x y' + q y = x^k,
>
$$

> where $p,q,k$ are constants and $x>0$.

***

## 9. Boundary Value Problem – Eigenvalues and Eigenfunctions

**Problem Type Name**: Sturm–Liouville-type BVP

**When it is asked**

- Section B (5 marks).

**Required concepts**

- Solving $y'' + \lambda y = 0$ under boundary conditions.

**Step-by-step solving**

Step 1: Identify given data

- ODE and BCs, typically:

$$
y'' + \lambda y = 0,\quad y(0)=0,\quad y(L)=0
$$

Step 2: Identify required output

- Allowed $\lambda$ values and eigenfunctions.

Step 3: Select framework

- Case analysis on $\lambda$.

Step 4: Apply method logically

1. For $\lambda>0$, write $\lambda = \mu^2$. Then:

$$
y = A\cos\mu x + B\sin\mu x.
$$
2. Apply $y(0)=0$ ⇒ $A=0$.
3. Then $y(L) = B\sin\mu L = 0$.
4. For non-trivial solution $B\neq 0$, need $\sin\mu L = 0$:

$$
\mu L = n\pi,\ n=1,2,\dots \Rightarrow \mu_n = n\pi/L.
$$
5. Thus $\lambda_n = \mu_n^2 = (n\pi/L)^2$.
6. Eigenfunctions: $y_n(x) = \sin(n\pi x/L)$.

Step 5: Present final answer properly

- Summarize eigenvalues and eigenfunctions.

**Example question**

> Find the eigenvalues and eigenfunctions of the boundary value problem

> $$
> y'' + \lambda y = 0,\quad 0 < x < L,\quad y(0) = 0,\quad y(L) = 0,
>
$$

> where $L>0$ is constant.

***

## 10. Laplace Transform of a Function

**Problem Type Name**: Direct Laplace transform

**When it is asked**

- Section A; sometimes B with unit step.

**Required concepts**

- Use Laplace table and linearity.

**Step-by-step solving**

Step 1: Identify given data

- Function $f(t)$ in terms of exponentials/trig/powers or piecewise.

Step 2: Identify required output

- Expression $F(s) = \mathcal{L}\{f(t)\}$.

Step 3: Select framework

- For standard functions: apply table.
- For piecewise: represent with unit step.

Step 4: Apply method logically

1. Decompose $f(t)$ as sum of simpler parts (if needed).
2. Apply table transforms to each part.
3. For piecewise:
    - Express as $g(t-a)u(t-a)$.
    - Use $\mathcal{L}\{g(t-a)u(t-a)\} = e^{-as}G(s)$.

Step 5: Present final answer properly

- Show intermediate steps briefly, then final expression.

**Example question**

> Find the Laplace transform of

> $$
> f(t) = e^{a t}\left( b \cos(\omega t) + c \sin(\omega t) \right),
>
$$

> where $a,b,c,\omega$ are constants.

***

## 11. Inverse Laplace Transform (Partial Fractions)

**Problem Type Name**: Inverse Laplace via partial fractions

**When it is asked**

- Section A (short).
- Section B (if more algebra is involved).

**Required concepts**

- Factor denominator and use table of inverse transforms.

**Step-by-step solving**

Step 1: Identify given data

- $F(s)$ as ratio of polynomials (or with shifts).

Step 2: Identify required output

- $f(t) = \mathcal{L}^{-1}\{F(s)\}$.

Step 3: Select framework

- Partial fraction decomposition.

Step 4: Apply method logically

1. Factor denominator into linear/quadratic factors.
2. Write general form of partial fraction expansion.
3. Determine constants by comparison or substitution.
4. Use standard inverse transforms to write $f(t)$.

Step 5: Present final answer properly

- Show factorization, constants, and final time-domain expression.

**Example question**

> Find the inverse Laplace transform

> $$
> \mathcal{L}^{-1}\left\{\frac{s + a}{(s + a)^2 + b^2}\right\},
>
$$

> where $a$ and $b$ are constants.

***

## 12. Solve IVP Using Laplace Transform (2nd / 3rd Order)

**Problem Type Name**: IVP via Laplace transform

**When it is asked**

- **Section C: 10 marks** (every year).
- Sometimes Section B: 5-mark simpler version.

**Required concepts**

- Laplace of derivatives with initial conditions.

**Step-by-step solving**

Step 1: Identify given data

- ODE (2nd or 3rd order) + initial conditions $y(0), y'(0), \dots$.

Step 2: Identify required output

- Explicit solution $y(t)$.

Step 3: Select framework

- Apply Laplace to both sides, solve for $Y(s)$, invert.

Step 4: Apply method logically

1. Take Laplace of each term:
    - Use derivative formulas.
2. Substitute initial values and write algebraic equation in $Y(s)$.
3. Solve for $Y(s)$.
4. Simplify and decompose $Y(s)$ via partial fractions / shifts.
5. Use inverse Laplace table to obtain $y(t)$.

Step 5: Present final answer properly

- Clearly show transform step, solve, and inversion.

**Example question**

> Solve the initial value problem using Laplace transforms:

> $$
> y'' + a y' + b y = e^{c t}, \quad y(0) = y_0,\quad y'(0) = y_1,
>
$$

> where $a,b,c,y_0,y_1$ are constants.

***

## 13. Orthogonality of Functions

**Problem Type Name**: Orthogonality on an interval

**When it is asked**

- Section A: 2 marks.

**Required concepts**

- Inner product integral; result must be zero.

**Step-by-step solving**

Step 1: Identify given data

- Functions $f_1(x), f_2(x)$, and interval $[a,b]$.

Step 2: Identify required output

- Check if $\int_a^b f_1 f_2 = 0$.

Step 3: Select framework

- Compute integral.

Step 4: Apply method logically

1. Set up:

$$
I = \int_a^b f_1(x)f_2(x)\,dx
$$
2. Evaluate (often using standard trig integrals).
3. If $I = 0$, they are orthogonal.

Step 5: Present final answer properly

- Show integral and conclude with orthogonality.

**Example question**

> Show that

> $$
> f_1(x) = \sin\left(\frac{n\pi x}{L}\right),\quad
> f_2(x) = \sin\left(\frac{m\pi x}{L}\right),
>
$$

> where $n \neq m$ are positive integers and $L>0$, are orthogonal on $[0,L]$.

***

## 14. PDE Type Classification

**Problem Type Name**: Classification of second-order PDE

**When it is asked**

- Section A: quick theory check.

**Required concepts**

- Discriminant $D = B^2 - 4AC$ for

$$
A u_{xx} + B u_{xy} + C u_{yy} + \dots = 0
$$

**Step-by-step solving**

Step 1: Identify given data

- PDE form and coefficients $A,B,C$.

Step 2: Identify required output

- Type: elliptic, parabolic, or hyperbolic.

Step 3: Select framework

- Compute discriminant.

Step 4: Apply method logically

1. Read off $A,B,C$.
2. Compute:

$$
D = B^2 - 4AC.
$$
3. Classify:
    - $D>0$: hyperbolic
    - $D=0$: parabolic
    - $D<0$: elliptic

Step 5: Present final answer properly

- Clearly show value/sign of D and type.

**Example question**

> Consider the partial differential equation

> $$
> A u_{xx} + B u_{xy} + C u_{yy} = 0,
>
$$

> where $A,B,C$ are constants with $A \neq 0$. Classify this equation as elliptic, parabolic, or hyperbolic in terms of the sign of $B^2 - 4AC$.

***

## 15. Full Fourier Series on $[-L,L]$

**Problem Type Name**: Fourier series on symmetric interval

**When it is asked**

- Section B or Section C.

**Required concepts**

- Fourier coefficients and symmetry.

**Step-by-step solving**

Step 1: Identify given data

- Function $f(x)$ on $-L < x < L$.

Step 2: Identify required output

- Fourier series.

Step 3: Select framework

- Use formulas; check if even/odd to simplify.

Step 4: Apply method logically

1. Check if $f$ is even / odd:
    - Even: $f(-x)=f(x) \Rightarrow b_n=0$.
    - Odd: $f(-x)=-f(x) \Rightarrow a_0=a_n=0$.
2. Compute:

$$
a_0 = \frac{1}{L}\int_{-L}^L f(x)\,dx
$$

$$
a_n = \frac{1}{L}\int_{-L}^L f(x)\cos\frac{n\pi x}{L}\,dx
$$

$$
b_n = \frac{1}{L}\int_{-L}^L f(x)\sin\frac{n\pi x}{L}\,dx
$$
3. Plug into series:

$$
f(x) \sim \frac{a_0}{2} + \sum_{n=1}^\infty \big(a_n \cos\frac{n\pi x}{L} + b_n \sin\frac{n\pi x}{L}\big)
$$

Step 5: Present final answer properly

- Write explicit formulas for coefficients and the series.

**Example question**

> Obtain the Fourier series of the function

> $$
> f(x) = k x,\quad -L < x < L,
>
$$

> where $k$ and $L$ are positive constants.

***

## 16. Half-Range Sine / Cosine Series on $[0,L]$

**Problem Type Name**: Half-range Fourier series

**When it is asked**

- Section B or C.

**Required concepts**

- Cosine series (even extension) and sine series (odd extension).

**Step-by-step solving**

Step 1: Identify given data

- Function $f(x)$ defined on $0 < x < L$ only.

Step 2: Identify required output

- Half-range sine or cosine series (as specified in question).

Step 3: Select framework

- Use appropriate formulas.

Step 4: Apply method logically

- **Cosine series** (even extension):

1. Use:

$$
a_0 = \frac{2}{L}\int_0^L f(x)\,dx,\quad
a_n = \frac{2}{L}\int_0^L f(x)\cos\frac{n\pi x}{L}\,dx
$$
2. Series:

$$
f(x) \sim \frac{a_0}{2} + \sum_{n=1}^\infty a_n\cos\frac{n\pi x}{L}
$$
- **Sine series** (odd extension):

1. Use:

$$
b_n = \frac{2}{L}\int_0^L f(x)\sin\frac{n\pi x}{L}\,dx
$$
2. Series:

$$
f(x) \sim \sum_{n=1}^\infty b_n \sin\frac{n\pi x}{L}
$$

Step 5: Present final answer properly

- Show key integrals and final series.

**Example question**

> Find the half-range sine series representation of

> $$
> f(x) = k x,\quad 0 < x < L,
>
$$

> where $k$ and $L$ are positive constants.

***

# Scoring Strategy \& Time Allocation Plan

## Time Allocation (2 Hours)

- **Section A (20 marks max)** – 35–40 minutes
    - Aim to attempt **10–12** questions.
    - Prioritize:
        - Simple linear/separable DEs.
        - Exactness parameter problems.
        - Wronskian / independence.
        - Direct Laplace / inverse Laplace.
        - Orthogonality and PDE classification.
- **Section B (30 marks max)** – 45–50 minutes
    - Choose **4–5 strongest models**:
        - 1 first-order DE (linear/exact/Bernoulli).
        - 1 constant-coefficient or Cauchy–Euler DE.
        - 1 Laplace-based ODE or inverse Laplace.
        - 1 Fourier / half-range series.
    - Spend about 9–10 minutes per chosen question.
- **Section C (10 marks, choose 1)** – 25–30 minutes
    - Choose **either**:
        - Laplace IVP (if more comfortable with transforms), or
        - Fourier series (if integrals are easier for you).
    - Write full step-by-step solution; even partial but structured work gets marks.


## Pass-Focused Target (26+)

- Section A: 8 correct answers → 16 marks
- Section B: 2 good full answers (10 marks) + 1 partial (2–3 marks) → 12–13
- Section C: partial attempt → 3–5 marks

Total ≈ 31–34 marks → comfortably above 26.

# Priority Based Study Plan (Night Before Exam)

### Highest Yield Topics (in order)

1. **Laplace + Constant-Coefficient ODEs (Modules II \& III)**
    - Practice at least **2 full IVP problems** via Laplace (one 2nd order, one 3rd order).
    - Drill derivative transform formulas and partial fractions.
    - Re-revise characteristic roots and undetermined coefficients.
2. **Fourier Series (Module IV)**
    - Do **1 full Fourier series** on $[-L,L]$.
    - Do **1 half-range sine or cosine series** on $[0,L]$.
    - Memorize coefficient formulas and parity tricks (even/odd).
3. **First-Order DEs (Module I)**
    - Solve **1 linear IVP**, **1 separable**, **1 exact + find k**, and **1 Bernoulli** using the frameworks above.
4. **Quick Concept Revision for Section A**
    - Orthogonality integral pattern.
    - PDE classification rule $B^2 - 4AC$.
    - Wronskian independence idea.
    - Standard Laplace transform table.
    - Basic definitions (order/degree/linearity).

If time is tight, **focus on the problem-type frameworks + variable examples** in this document:
mentally map each model so that in the exam you only have to “plug in” the concrete numbers/functions into the same algorithm.

