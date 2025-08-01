# Hamiltonian Constraint and φ as Clock

## Objective

Demonstrate how the scalar field φ can act as a physical clock by deriving the Hamiltonian constraint in a minisuperspace cosmological model. This formalizes the core Waveframe v2.0 claim: **time is not fundamental, but emergent from the dynamics of φ**.

---

## 1. Action

We start with the action for a real scalar field φ minimally coupled to gravity in a spatially flat FRW background:

S = ∫ d⁴x √−g [½ ∂_μ φ ∂^μ φ − V(φ)]

With metric:

ds² = −N(t)² dt² + a(t)² d⃗x²

where:
- N(t) is the lapse function,
- a(t) is the scale factor,
- φ = φ(t) is homogeneous.

---

## 2. Minisuperspace Reduction

The action becomes:

S = ∫ dt [−3 a ẋ² / N + ½ a³ φ̇² / N − a³ N V(φ)]

---

## 3. Canonical Momenta

πₐ = ∂𝓛/∂ȧ = −6 a ȧ / N  
π_φ = ∂𝓛/∂φ̇ = a³ φ̇ / N

---

## 4. Hamiltonian

ℋ = πₐ ȧ + π_φ φ̇ − 𝓛  
= N [−πₐ² / (12a) + π_φ² / (2a³) + a³ V(φ)]

Hamiltonian constraint:

ℋ = 0  
⇒ −πₐ² / (12a) + π_φ² / (2a³) + a³ V(φ) = 0

---

## 5. Reparameterize Time as φ

If φ is monotonic:  
`t ≡ φ` and `d/dt = φ̇ d/dφ`

Then:

da/dφ = (ȧ / φ̇) = (πₐ / π_φ) ⋅ (1 / a²)

Now use the Hamiltonian constraint to eliminate πₐ:

(da/dφ)² = [12 / a³] ⋅ [1 / (π_φ² / (2a³) + a³ V(φ))]

This defines the dynamics of a(φ), completing the system without reference to coordinate time t.

---

## 6. Validity Conditions

- φ must be strictly or piecewise monotonic.
- π_φ ≠ 0 to avoid degeneracy.
- N(t) can be gauge-fixed to define φ-time.

---

## 7. Implications

This shows that time and metric evolution can be re-expressed entirely in terms of φ’s evolution — validating the use of φ as a clock and grounding Waveframe’s emergent time structure.
