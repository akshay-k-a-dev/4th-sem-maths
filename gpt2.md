
# MATHEMATICS – 4 EXAM MASTER GUIDE (Simplified & Scoring Focused)

---

# Exam Pattern (Based on 2023–2024 Papers)

## Section Structure

| Section | Question Type | Marks | Strategy |
|----------|-------------|------------|------------|
| Section A | Short Answer | 2 Marks Each | Fast scoring |
| Section B | Medium Problems | 5 Marks Each | Method-based solving |
| Section C | Long Problem | 10 Marks | Deep calculation (Laplace OR Fourier usually) |

---

# Most Repeated Question TYPES (Not Exact Questions)

These are pattern-based repeated models.

## HIGH PROBABILITY

1. First order ODE (Exact / Linear / Bernoulli)
2. Second order ODE with constant coefficients
3. Laplace Transform IVP (10 Mark Favourite)
4. Fourier Series Expansion (10 Mark Favourite)
5. Inverse Laplace using Partial Fractions
6. PDE Classification
7. Separation of Variables (Heat/Wave)

---

# SECTION A – FAST SOLVING MODELS

---

## TYPE 1 – Check Exact Differential Equation

### Standard Question Pattern
Check whether the equation is exact. If exact, find solution.

### Step-by-Step Method

### Step 1
Write equation in form:


M(x,y) dx + N(x,y) dy = 0


### Step 2
Find:



∂M/∂y
∂N/∂x



### Step 3
Compare:



If ∂M/∂y = ∂N/∂x → EXACT
Else → NOT EXACT



### Step 4 (If Exact)

Integrate M w.r.t x



Ψ(x,y) = ∫M dx + h(y)



Differentiate Ψ w.r.t y and compare with N to find h(y)

### Step 5
Final Solution:



Ψ(x,y) = C



---

### Common Mistakes
- Forgetting h(y)
- Partial derivative errors

---

## TYPE 2 – Linear First Order ODE

### Standard Form
```

dy/dx + P(x)y = Q(x)



### Step-by-Step Method

Step 1 → Identify P(x)

Step 2 → Find Integrating Factor


IF = e^(∫P dx)



Step 3 → Multiply equation by IF

Step 4 → Convert into:


d/dx [ y × IF ] = Q × IF



Step 5 → Integrate both sides

Step 6 → Find y

---

## TYPE 3 – Bernoulli Equation

### Standard Form


dy/dx + P(x)y = Q(x) yⁿ



### Steps

Step 1 → Divide by yⁿ

Step 2 → Substitute
```

z = y^(1-n)



Step 3 → Convert into Linear ODE

Step 4 → Solve using Integrating Factor

---

# SECTION B – 5 MARK SOLUTION MODELS

---

## TYPE 4 – Second Order ODE (Constant Coefficients)

### General Form


ay'' + by' + cy = 0



### Step-by-Step

Step 1 → Write Characteristic Equation


ar² + br + c = 0



Step 2 → Solve roots

### Case 1 – Distinct Real Roots


y = C₁e^(r₁x) + C₂e^(r₂x)



### Case 2 – Repeated Roots


y = (C₁ + C₂x)e^(rx)



### Case 3 – Complex Roots


y = e^(αx)[C₁ cos βx + C₂ sin βx]



---

## TYPE 5 – Undetermined Coefficients

Used when RHS contains:
- Polynomial
- Exponential
- Trigonometric

### Steps

Step 1 → Solve homogeneous part → y_c

Step 2 → Guess Particular Solution y_p

Step 3 → Substitute in equation

Step 4 → Solve constants

Step 5 → Final Answer


y = y_c + y_p



---

# SECTION C – 10 MARK LONG QUESTIONS

---

# ⭐ LAPPLACE TRANSFORM FULL 10 MARK SOLUTION MODEL

---

## Standard Question Type
Solve ODE using Laplace Transform with initial conditions.

---

## MASTER STEP-BY-STEP METHOD

---

### Step 1 → Take Laplace of Entire Equation

Remember:



L{y'} = sY - y(0)
L{y''} = s²Y - s y(0) - y'(0)



Replace derivatives using above formulas.

---

### Step 2 → Substitute Initial Conditions

Replace y(0), y'(0) values.

---

### Step 3 → Solve Algebraically for Y(s)

Bring Y(s) terms together.

---

### Step 4 → Use Partial Fractions

Break Y(s) into simpler fractions.

---

### Step 5 → Take Inverse Laplace

Use standard table:

| Expression | Result |
|-----------|-----------|
| 1/s | 1 |
| 1/(s-a) | e^(at) |
| s/(s²+a²) | cos(at) |
| a/(s²+a²) | sin(at) |

---

### Step 6 → Write Final Answer y(t)

---

## SAMPLE STRUCTURE (How to Write in Exam)

1. Taking Laplace on both sides  
2. Applying initial conditions  
3. Solving for Y(s)  
4. Partial fraction decomposition  
5. Taking inverse Laplace  
6. Final y(t)

---

### Common Mistakes

- Missing negative sign
- Wrong partial fractions
- Forgetting initial conditions

---

### Time Target
25 Minutes

---

# ⭐ FOURIER SERIES FULL 10 MARK SOLUTION MODEL

---

## Standard Question Type
Find Fourier Series for given function.

---

## MASTER STEP-BY-STEP METHOD

---

### Step 1 → Identify Interval

Usually:


(-L , L)



---

### Step 2 → Write General Fourier Series



f(x) = a₀/2 + Σ [ aₙ cos(nπx/L) + bₙ sin(nπx/L) ]



---

### Step 3 → Find a₀



a₀ = (1/L) ∫ f(x) dx



---

### Step 4 → Find aₙ

```

aₙ = (1/L) ∫ f(x) cos(nπx/L) dx

```

---

### Step 5 → Find bₙ

```

bₙ = (1/L) ∫ f(x) sin(nπx/L) dx

```

---

### Step 6 → Substitute in Series

Write final Fourier Series.

---

## FAST TRICK (Parity Check)

| Function Type | Terms Present |
|--------------|-------------|
| Even | Only Cosine |
| Odd | Only Sine |

---

### Common Mistakes

- Wrong limits
- Missing 1/L factor
- Integration mistakes

---

### Time Target
25 Minutes

---

# PDE – REPEATED TYPE SOLUTION

---

## TYPE – Classification

### Step 1
Compare equation with:
```

A uxx + B uxy + C uyy

```

### Step 2
Calculate:

```

D = B² - 4AC

```

### Step 3
Result

| D Value | Type |
|---------|---------|
| > 0 | Hyperbolic |
| = 0 | Parabolic |
| < 0 | Elliptic |

---

## TYPE – Separation of Variables (Heat Equation)

### Step 1
Assume
```

u(x,t) = X(x)T(t)

```

### Step 2
Substitute in PDE

### Step 3
Separate variables

### Step 4
Solve two ODEs

### Step 5
Apply boundary conditions

### Step 6
Write Final Series Solution

---

# MOST IMPORTANT FORMULA CHEAT SHEET

---

## Integrating Factor


e^(∫P dx)



---

## Laplace Derivative


L{y'} = sY - y(0)




## Fourier Coefficients


aₙ = (1/L) ∫ f(x) cos(nπx/L)
bₙ = (1/L) ∫ f(x) sin(nπx/L)



---

## PDE Classification


B² - 4AC



---

# SMART STUDY PRIORITY

## HIGH PRIORITY (70% Exam Weight)

✔ Laplace Transform  
✔ Fourier Series  
✔ Second Order ODE  

---

## MEDIUM PRIORITY

✔ First Order ODE  
✔ Undetermined Coefficients  
✔ Variation of Parameters  

---

## LOW PRIORITY

✔ Euler Method  
✔ Direction Fields  

---

# FINAL EXAM ATTEMPT STRATEGY

### Order to Attempt

1. Section C First  
2. Section B Next  
3. Section A Last  

---

### Time Split

| Section | Time |
|---------|--------|
| Section C | 30 min |
| Section B | 55 min |
| Section A | 25 min |

---

# FINAL REVISION CHECKLIST

✔ Practice 5 Laplace IVP problems  
✔ Practice 3 Fourier expansions  
✔ Memorize Laplace table  
✔ Memorize Fourier formulas  
✔ Solve 2 full question papers  

---

# END OF MASTER GUIDE


