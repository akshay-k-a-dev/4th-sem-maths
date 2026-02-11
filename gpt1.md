# Exam Pattern Analysis (2023–2024 Based)

**Primary sources used:** 2023 and 2024 question papers (dominant), validated against 2021–2022 papers. See the scanned papers: 2023 QP and 2024 QP.  . (I reference 2021–22 examples where they confirm trends.)  

## Key conclusions (evidence-backed)

* **Section structure (stable in 2023–2024):**

  * **Section A:** Short questions (2 marks each in 2023–24; earlier/year variations had 3 marks but the 2023–24 standard is 2 marks). Ceiling per Section A: 20.  
  * **Section B:** Medium questions (5 marks each). Ceiling around 30.  
  * **Section C:** One long question (10–11 marks) where the student answers **one** of two options.  
* **Total marks:** 60 (External). Time: 2 hours.  
* **Question types recurring:** short computations/definitions, exactness checks, integrating factors, Laplace transforms (direct and inverse), ODE initial value problems (IVP) solved by Laplace, higher-order constant-coefficient ODEs, variation of parameters, undetermined coefficients, Cauchy–Euler, Fourier series (full-range and half-range; cosine/sine expansions), basic PDE classification (parabolic/elliptic/hyperbolic), separation of variables for heat/wave.  
* **Examiner trends (2023–24):**

  * Emphasis on **Laplace transforms** for initial value problems and for transforms involving piecewise/unit step functions.  
  * **Fourier expansions** frequently ask expansion of simple polynomials or piecewise functions and half-range cosine/sine series.  
  * PDE questions usually limited to **classification** and **separation of variables** for the heat/wave equation; BVPs are straightforward eigenvalue problems. 
* **Difficulty pattern:** Section A tests recall and quick computation; Section B tests standard solution techniques; Section C demands one extended calculation (Laplace IVP or Fourier expansion).  

---

# Question Pattern Breakdown

| Section |                      Q-type | Marks per Q |                         No. of Qs (typ.) | Ceiling | Typical topics                                                                                                                                                |
| ------- | --------------------------: | ----------: | ---------------------------------------: | ------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| A       | Short answer/verify/compute | 2 (2023–24) | ~10–12 (answer any number up to ceiling) |      20 | ODE check, integrating factor, Laplace transform (single), PDE classification, orthogonality tests.                                                           |
| B       |    Standard problem-solving |           5 |            5–7 (answer any with ceiling) |      30 | First-order exact/separable/linear; 2nd-order constant-coeff; Variation of parameters; Laplace inverses; Fourier half-range; Separation of variables (PDE).   |
| C       |      Long answer (choose 1) |       10–11 |                         2 (answer any 1) |   10–11 | Laplace-solved IVP OR Fourier series full-range expansion.                                                                                                    |

**Mark-distribution rule-of-thumb for time planning:** allocate ~2/3 of time to Sections B+C (since they carry ~40 marks) and the rest to Section A.

---

# Predicted Important Question Models

> Predictions strictly anchored to 2023–24 patterns (dominant evidence cited in each bullet).

1. **Laplace IVP** — Solve a 2nd-order linear ODE with constant coefficients using Laplace transforms, given y(0), y'(0), and a forcing function of the form (1+e^{-t}) or piecewise/unit-step. *(Observed in both 2023 and 2024 Section C/B).*  

2. **Fourier expansion of a simple polynomial or piecewise function** — full-range or half-range cosine/sine series on interval ([-π,π]) or ([-2,2]). *(2023 & 2024 include such problems in Section C/B).*  

3. **First-order exactness/integrating factor** — check exactness or compute integrating factor for an equation like (M(x,y),dx + N(x,y),dy = 0). *(Seen in Section B/A across years).*  

4. **Variation of parameters / Undetermined coefficients** — find particular integrals for nonhomogeneous constant-coefficient ODEs. *(Seen in B in 2023–24).*  

5. **Laplace transform operational properties & convolution** — inverse Laplace using convolution theorem for rational products, or transform of piecewise functions. *(2023 & 2024 Section B questions).*  

6. **Cauchy–Euler equation** — given an Euler-type ODE, find general solution; sometimes provide one solution and ask for second via reduction of order. *(Appears regularly in earlier papers and supports 2023 pattern).*  

7. **PDE classification and separation of variables** — classify PDE (parabolic/elliptic/hyperbolic) and solve simple heat-equation BVPs via separation (eigenfunctions, Fourier sine/cosine). *(2023–24 include classification and separable PDE problems).*  

8. **Orthogonality tests** — show two functions are orthogonal on a given interval (simple integrals). *(Frequent in Section A across years).*  

---

# Section Wise Preparation Notes

A compact, exam-focused guide for each syllabus module (Module numbering follows syllabus).

---

## Module I — Ordinary Differential Equations (First-order)

**Core concepts**

* Definitions: order/degree, linear vs nonlinear, IVP, singular solution, solution curve.
* Methods: separable, linear first-order, exact equations, integrating factors, substitutions (homogeneous, Bernoulli).
* Direction fields (qualitative).

**Important formulas / reminders**

* Linear first order: (y' + P(x)y = Q(x)). Integrating factor: (\mu(x) = e^{\int P(x),dx}). Solution: (y\mu = \int Q\mu,dx + C).
* Bernoulli: (y' + P(x)y = Q(x) y^n). Substitute (z = y^{1-n}).
* Exactness: (M(x,y)dx + N(x,y)dy = 0) exact if (M_y = N_x). If not exact, look for IF: (\mu(x)) or (\mu(y)) via (\frac{M_y-N_x}{N}) test or (\frac{N_x-M_y}{M}) test.

**Concept summary (bullets)**

* Check linearity and separability first.
* Always check exactness before forcing a substitution.
* For integrating factor, attempt simple (\mu(x)) or (\mu(y)) before more complex forms.

**Common mistakes**

* Forgetting domain restrictions (e.g., (y=0) lost in dividing).
* Skipping constant-of-integration handling when finding integrating factor.
* Sign errors in integrating factor exponent.

**How examiner frames questions**

* Short-check (Section A): "Check whether ... is exact" or "Write the integrating factor".
* Medium (Section B): Solve specified first-order equations or reduce to separable variables. 

---

## Module II — Higher Order ODEs (Second & Higher order)

**Core concepts**

* Homogeneous linear equations with constant coefficients and solution forms (real distinct, repeated, complex conjugates).
* Wronskian and linear independence.
* Methods: undetermined coefficients, variation of parameters, reduction of order, Cauchy–Euler.
* Boundary value problems and eigenfunctions (basic).

**Important formulas**

* Characteristic equation for constant coefficients: replace (D^n) by (r^n).
* For repeated root (r) of multiplicity (m): multiply by (x^k) terms in solutions.
* Variation of parameters formula (2nd order): if (y_1,y_2) are fundamental solutions, particular solution (y_p = -y_1 \int \frac{y_2 g}{W}dx + y_2 \int \frac{y_1 g}{W}dx) where (g(x)) is RHS and (W) is Wronskian.

**Concept bullets**

* Use undetermined coefficients for RHS of exponential/polynomial/trig and their linear combos.
* If RHS matches homogeneous solution, multiply trial by (x^m) to get a valid guess.
* Use reduction of order when one solution is given.

**Common mistakes**

* Failing to check resonance (RHS overlaps homogeneous solution).
* Wrong Wronskian sign or forgetting to compute (W) correctly.
* Using undetermined coefficients beyond its valid class.

**Exam framing**

* Section B: find particular integral or apply variation of parameters; convert Euler equation to constant coefficient via substitution (x=e^t) or standard ansatz. 

---

## Module III — Laplace Transforms

**Core concepts**

* Laplace transform: ( \mathcal{L}{f(t)}(s) = \int_0^\infty e^{-st} f(t),dt).
* Linearity, transforms of derivatives, shifting theorems (first and second), unit step (Heaviside), convolution theorem, Dirac delta.
* Inverse Laplace via partial fractions, shifting, convolution.

**Important formulas**

* (\mathcal{L}{f'(t)} = sF(s) - f(0)), (\mathcal{L}{f''(t)} = s^2F(s) - sf(0)-f'(0))
* First shift: (\mathcal{L}{e^{at}f(t)} = F(s-a)).
* Unit step: (\mathcal{L}{u_c(t)f(t-c)} = e^{-cs}F(s)) (with appropriate function shift).
* Convolution: (f*g \leftrightarrow F(s)G(s)).

**Concept bullets**

* Always write initial conditions and apply transforms to derivatives correctly.
* For piecewise functions, express using unit steps before transforming.

**Common mistakes**

* Incorrect sign for (s) shift.
* Mishandling initial conditions when transforming derivatives.
* Forgetting to revert to time-domain with correct shift interpretation.

**Exam framing**

* Section A/B: simple transforms/inverses and unit-step expressions. Section C: Laplace solution of ODE IVP.  

---

## Module IV — Orthogonal Functions, Fourier Series & PDEs (Separation of Variables)

**Core concepts**

* Inner product (\langle f,g\rangle = \int_a^b f(x)g(x),dx). Orthogonality, orthonormal sets.
* Fourier series coefficients (a_0,a_n,b_n), half-range expansions.
* PDE classification by second-order PDE discriminant; method of separation for heat/wave/Laplace.

**Important formulas**

* Fourier coefficients on ([-L,L]):

  * (a_0 = \frac{1}{L}\int_{-L}^{L} f(x),dx), (a_n = \frac{1}{L}\int_{-L}^{L} f(x)\cos\frac{n\pi x}{L}dx)
  * (b_n = \frac{1}{L}\int_{-L}^{L} f(x)\sin\frac{n\pi x}{L}dx)
* PDE classification: For (A u_{xx} + B u_{xy} + C u_{yy}), discriminate (B^2 - 4AC):

  * (>0) hyperbolic, (=0) parabolic, (<0) elliptic.

**Common mistakes**

* Incorrect limits in half-range expansions.
* Forgetting normalization factors (check definitions used in the syllabus).
* Mistaking classification because of algebraic simplification errors.

**Exam framing**

* Short: "Show orthogonality" or "Show PDE is parabolic." Medium/Long: expand in Fourier or solve separation-of-variables BVPs.  

---

# Problem Type Solution Frameworks (Detailed Step-by-Step)

Below: every important problem type (observed/predicted) with a reproducible algorithm and exam-writing template. Use these templates under timed conditions.

---

## 1) Short ODE check / exactness / integrating factor (Section A / B)

**When asked:** Verify exactness or find integrating factor; sometimes solve resulting ODE.

**Required concepts:** Exact differential criteria, partial derivatives (M_y,N_x), integrating factor (\mu(x)) or (\mu(y)).

**Step-by-step solving procedure (algorithmic):**

* **Step 1:** Identify (M(x,y),dx + N(x,y),dy = 0).
* **Step 2:** Compute (M_y) and (N_x).
* **Step 3:** If (M_y = N_x) → exact. Else compute (\frac{M_y - N_x}{N}) to test for (\mu(x)) or (\frac{N_x - M_y}{M}) for (\mu(y)).
* **Step 4:** If (\mu(x)) depends only on (x), set (\mu(x) = e^{\int \text{that} ,dx}). Similarly for (\mu(y)).
* **Step 5:** Multiply equation by (\mu), re-check exactness, then integrate: find (\Psi(x,y)) with (\Psi_x=M) and (\Psi_y=N). Include constant (C).
* **Step 6:** Present implicit/explicit solution.

**Answer writing template (concise):**

1. State (M,N).
2. Show (M_y) and (N_x). Conclude exact/not exact.
3. Show integrating factor (if needed) and compute (\mu).
4. Multiply and integrate: (\Psi(x,y)=\int M,dx + h(y)). Determine (h(y)) via (\Psi_y=N).
5. Final solution (\Psi(x,y)=C).

**Common traps**

* Using wrong test for IF; dividing by expression that could be zero.
* Missing constant-of-integration when integrating (M) w.r.t (x).

**Time:** 6–8 minutes for a 5-mark question.
**Scoring tips:** Show all derivative checks; include explicit integration steps and final implicit/equality form.

---

## 2) Separable / Linear First-Order ODE and Bernoulli

**When asked:** Solve first-order ODE of separable or linear/Bernoulli type.

**Required concepts:** Separation, integrating factor, substitution for Bernoulli.

**Procedure:**

* **Step 1 (Identify):** Recognize separable: can be written (g(y)dy = f(x)dx). Recognize linear: (y' + P(x)y = Q(x)). Bernoulli: (y' + P(x)y = Q(x) y^n).
* **Step 2 (Transform):** For separable, integrate both sides. For linear, compute (\mu = e^{\int Pdx}) and multiply. For Bernoulli, substitute (z=y^{1-n}).
* **Step 3 (Integrate):** Integrate and solve for (y). Apply initial condition if given.
* **Step 4 (Present):** Give general solution (y = \ldots) and comment on domains.

**Template (short):** Show identification, show integrating factor/substitution, integrate, solve constant, show final (y).

**Common traps:** Dropping absolute values in logs; mixing variables when integrating.

**Time:** 6–8 minutes (5-mark).

---

## 3) Higher-order ODE: Homogeneous with constant coefficients

**When asked:** Solve (a_n y^{(n)} + \dots + a_1 y' + a_0 y = 0).

**Required concepts:** Characteristic polynomial, roots multiplicity, complex roots.

**Procedure:**

* **Step 1:** Form characteristic equation (a_n r^n + \dots + a_0 = 0).
* **Step 2:** Solve for roots. Distinguish: distinct real, repeated real, complex conjugate.
* **Step 3:** Write complementary function (y_c): sum of exponentials and polynomial factors for multiplicity.
* **Step 4:** If nonhomogeneous, find particular (y_p) using undetermined coefficients (or variation of parameters).
* **Step 5:** Combine (y = y_c + y_p). Apply ICs for constants.

**Template (exam):** Show characteristic equation → list roots → write basis solutions → general solution → apply ICs.

**Traps:** Neglecting multiplicity factor (x^m) for repeated roots or using wrong ansatz for (y_p).

**Time:** 8–12 minutes depending on degree.

---

## 4) Undetermined Coefficients & Variation of Parameters (Particular integrals)

**When asked:** Find a particular integral for given RHS types.

**Required concepts:** Trial functions for exponential/polynomial/trig; variation integral formula.

**Procedure (undetermined coefficients):**

* **Step 1:** Identify RHS type.
* **Step 2:** Propose trial (y_p). If RHS is solution of homogeneous, multiply trial by (x^m) where (m) is multiplicity.
* **Step 3:** Plug into ODE, equate coefficients, solve for unknown constants.
* **Step 4:** Present (y_p) and full solution.

**Procedure (variation of parameters 2nd order):**

* **Step 1:** Find fundamental solutions (y_1,y_2).
* **Step 2:** Compute Wronskian (W).
* **Step 3:** Use formulae for (u_1', u_2') and integrate to get (u_1,u_2).
* **Step 4:** (y_p = u_1 y_1 + u_2 y_2).

**Template:** Clearly separate (y_c) and (y_p). Display solved constants cleanly.

**Traps:** Messy algebra; failing to multiply by (x) in resonance.

**Time:** 10–15 minutes (5-mark undetermined; 12–18 for variation).

---

## 5) Laplace Transform (Direct & Inverse; solving IVPs)

**When asked:** Compute transforms/inverses or use Laplace to solve ODE IVP.

**Required concepts:** Linear properties; transforms of derivatives; shifting; convolution; unit-step.

**Procedure (Laplace IVP):**

* **Step 1:** Take Laplace on both sides: replace (y',y'') with algebraic forms using initial values.
* **Step 2:** Solve algebraic equation for (Y(s)).
* **Step 3:** Decompose (Y(s)) using partial fractions / shift / convolution.
* **Step 4:** Use inverse Laplace to find (y(t)). If unit-step used, apply shift theorem to get piecewise expressions.

**Template (exam):**

1. Write transforms of derivatives with initial values.
2. Solve for (Y(s)).
3. Perform partial fractions or identify known transforms.
4. Write (y(t)) with proper domain/shift.

**Common traps:** Mishandling initial values; wrong partial-fraction decomposition; incorrect mapping of (e^{-as}F(s)) back to unit-step.

**Time:** 12–18 minutes (Section C style).

**Scoring tip:** Show intermediate (Y(s)) step clearly — examiners award for algebraic set-up even if inverse step has small arithmetic error.

---

## 6) Inverse Laplace via Convolution / Unit-step

**When asked:** Inverse Laplace of product that is not easily separable.

**Concepts:** Convolution theorem: (\mathcal{L}^{-1}{F(s)G(s)} = f*g).

**Procedure:**

* **Step 1:** Recognize factors as transforms of known functions.
* **Step 2:** Use convolution integral ( (f*g)(t) = \int_0^t f(\tau)g(t-\tau)d\tau ).
* **Step 3:** Compute integral; simplify.

**Template:** Identify (f(t),g(t)), write convolution integral, evaluate integral, give final expression.

**Time:** 8–12 minutes.

---

## 7) Fourier Series (Full and Half-range)

**When asked:** Expand (f(x)) on ([-L,L]) or do half-range expansion.

**Required concepts:** Compute coefficients (a_0, a_n, b_n); parity considerations for simplifying integrals.

**Procedure:**

* **Step 1:** State interval and (L). Write formulas for (a_0,a_n,b_n).
* **Step 2:** If function is even/odd, use simplifications (odd → only sine terms; even → only cosine).
* **Step 3:** Compute integrals stepwise; simplify using orthogonality.
* **Step 4:** Present series: (f(x) \sim \frac{a_0}{2} + \sum a_n \cos\frac{n\pi x}{L} + b_n \sin\frac{n\pi x}{L}).
* **Step 5:** If asked, mention Gibbs phenomenon or convergence point if piecewise.

**Template (exam):** show integral calculations for first few coefficients (no need to show every algebraic simplification), write final series neatly.

**Common traps:** Forgetting the factor (1/L) or (1/\pi) depending on conventions; wrong substitution for half-range.

**Time:** 12–18 minutes for full 10–11 mark question.

**Scoring tip:** Compute (a_0) cleanly and show first few nonzero coefficients explicitly — examiners often award for correct coefficient work even if later algebra messy.

---

## 8) PDE Classification & Separation-of-Variables (Heat/Wave)

**When asked:** Classify PDE and/or solve using separation.

**Required concepts:** Discriminant (B^2 - 4AC) for classification; separation ansatz (u(x,t)=X(x)T(t)); eigenvalue problems with boundary conditions.

**Procedure (classification):**

* **Step 1:** Write coefficients (A,B,C) from PDE.
* **Step 2:** Compute (D = B^2 - 4AC). State type: hyperbolic/parabolic/elliptic.

**Procedure (separation):**

* **Step 1:** Assume (u(x,t)=X(x)T(t)). Substitute and separate to form (\frac{T'}{\alpha T} = \frac{X''}{X} = -\lambda).
* **Step 2:** Solve spatial eigenvalue problem (X'' + \lambda X = 0) with BCs to get eigenfunctions.
* **Step 3:** Solve temporal ODE for each (\lambda). Superpose series expansion to satisfy initial condition.
* **Step 4:** State final series solution (u(x,t)=\sum A_n e^{-\alpha \lambda_n t} \sin(n\pi x/L)) etc.

**Template:** Clearly show separation step → eigenvalue problem → eigenfunctions and coefficients via orthogonality → final series and comment on convergence.

**Traps:** Missing sign of separation constant; ignoring boundary conditions.

**Time:** 12–15 minutes (5–10 mark depending on depth).

---

# Scoring Strategy & Time Allocation Plan (2-hour exam)

**Total time:** 120 minutes. Target strategy (maximize score):

* **Section C (one long question, 10–11 marks):** 25–30 minutes.

  * Rationale: High mark density; often Laplace IVP or Fourier expansion — allocate focused time.

* **Section B (five 5-mark problems; ceiling 30):** 50–55 minutes total → ~10–11 minutes per question.

  * Strategy: Attempt the five easiest/high-confidence problems first. If a problem is stalling >12 mins, move on and return if time permits.

* **Section A (short answers; ceiling 20):** 25–30 minutes.

  * Strategy: Answer quick 2-mark items fast (2–3 minutes each). These are reliable marks.

* **Final review:** 5–10 minutes to re-check algebra, signs, ICs in solutions.

**Concrete minute-by-minute plan**

* First 5 minutes: quick scan of the paper; mark easiest B/C problems.
* 30–35 min: Section C.
* 55–60 min: Solve two or three of Section B (best fits).
* 25–30 min: Section A.
* Remaining: finish Section B leftovers and review.

**Scoring optimization tips**

* Show all intermediate algebraic steps clearly — partial credit is common.
* For Laplace problems: even if inverse transform messy, full marks often given for correct (Y(s)) algebra.
* For Fourier: present final coefficients explicitly; write first few terms to demonstrate pattern.
* Use orthogonality relations to compute coefficients succinctly; mention parity to save computation.

---

# Priority Based Study Plan (6-week intensive before exam)

Apply 80/20: focus on high-probability topics from 2023–24 pattern.

## Week-by-week (SMART goals)

**Week 1 — Must (High priority)**
Goal: Master Laplace transforms for IVPs + transforms of piecewise/unit-step.

* *Specific:* Finish 20 solved Laplace IVPs (including shifts & convolution).
* *Measurable:* Solve 4 per day; timed (30–45 min each).
* *Achievable:* Use past papers (2023–24).  
* *Relevant:* Highest weight in Section C/B.
* *Time-bound:* 7 days.

**Week 2 — Must (High priority)**
Goal: Fourier series (full and half-range) – compute 10 expansions.

* Practice even/odd simplifications, half-range cosine/sine. Use 2023–24 examples as blueprint. 

**Week 3 — Must**
Goal: Second-order ODEs (constant coefficients): homogeneous + undetermined coefficients + variation of parameters. Do 15 varied problems.

**Week 4 — Must/Medium**
Goal: First-order methods: exactness, integrating factors, Bernoulli, separable. Complete 12 questions. Analyze mistakes.

**Week 5 — Medium**
Goal: PDE basics — classification + solve simple heat-equation separation problems and eigenfunction expansions.

**Week 6 — Review & Mock Exam**

* Two full timed mocks replicating exact pattern (Section A,B,C) using problems taken from 2023–24 and earlier for validation. Review errors and re-do tough ones.

**Daily micro-plan (90–120 minutes/day)**

* 45–60 min: focused problem solving on today's topic.
* 20–30 min: revisit errors and formula sheet.
* 15–30 min: timed short question practice (Section A style).

---

# Quick Formula & Concept Sheet (single-page revision)

* **Linear 1st order:** (y'+P(x)y=Q(x)), (\mu=e^{\int Pdx}).
* **Bernoulli:** (y' + P y = Q y^n) → (z = y^{1-n}).
* **Exactness:** (M_y = N_x). IF candidate (\mu(x) = e^{\int \frac{M_y-N_x}{N}dx}).
* **2nd order characteristic:** (r^2 + ar + b = 0) → roots → solutions (e^{rx}), (x e^{rx}), (e^{\alpha x}\cos\beta x), etc.
* **Variation of parameters (2nd order):** (y_p = -y_1 \int \frac{y_2 g}{W}dx + y_2 \int \frac{y_1 g}{W}dx).
* **Laplace of derivative:** (\mathcal{L}{y'}=sY-y(0)); (\mathcal{L}{y''}=s^2Y-s y(0)-y'(0)).
* **Shifting:** (\mathcal{L}{e^{at}f(t)}=F(s-a)). Unit step: (u_c(t)f(t-c) \leftrightarrow e^{-cs}F(s)).
* **Convolution:** (f*g \leftrightarrow F(s)G(s)).
* **Fourier (−L,L):** (a_n=\frac{1}{L}\int_{-L}^{L} f(x)\cos\frac{n\pi x}{L},dx); (b_n=\frac{1}{L}\int_{-L}^{L} f(x)\sin\frac{n\pi x}{L},dx).
* **PDE classification:** (B^2-4AC) sign determines type.

---

# Final checklist before exam

* Memorize integrals for basic transforms: (1, t, e^{at}, \sin bt, \cos bt).
* Memorize Fourier coefficient formulas and parity shortcuts.
* Practice 5 full Laplace IVPs and 3 Fourier series under timed conditions.  
* Keep one clean A4 sheet of core formulas for last-minute review.

---

# Appendices — Direct links to referenced exam papers (scanned)

* 2023 paper (used for pattern): scanned file. 
* 2024 paper (used for pattern): scanned file. 
* 2021 and 2022 for validation: scanned files.  

---

