
# Hamiltonian Clock Derivation

This document outlines the derivation of the Hamiltonian constraint in the Waveframe v2.0 model, where the scalar field φ defines the emergent time coordinate.

## 1. Starting Point: Action

We begin with the canonical scalar field action minimally coupled to gravity:

S = ∫ d^4x √−g [ (1/2)(∂_μ φ)(∂^μ φ) − V(φ) ]

## 2. Homogeneous Cosmology Assumption

Assume a spatially flat metric with scalar field φ(t) only depending on time:

ds² = −dt² + a(t)² dx²  
φ = φ(t)

Then the Lagrangian becomes:

L = a³ [ (1/2) φ̇² − V(φ) ]

## 3. Canonical Momentum

The conjugate momentum to φ is:

π_φ = ∂L/∂φ̇ = a³ φ̇

## 4. Hamiltonian Density

The Hamiltonian is:

H = π_φ φ̇ − L  
  = a³ [ (1/2) φ̇² + V(φ) ]

Substitute φ̇ = π_φ / a³:

H = (1/2a³) π_φ² + a³ V(φ)

This is the Hamiltonian density for a scalar field in cosmology.

## 5. Hamiltonian Constraint

In general relativity, the total Hamiltonian is constrained to vanish (for a closed system):

H_total = 0

So we have:

(1/2a³) π_φ² + a³ V(φ) = 0

This is the Hamiltonian constraint. It connects φ, its momentum, and the scale factor a.

## 6. Reinterpreting φ as Time

To use φ as the clock, we define t ≡ φ and invert the relationship to express dynamics with respect to φ.

We now write the scale factor a(φ), and define an effective time metric:

ds² = −α(φ)² dφ² + a(φ)² dx²

The lapse function α(φ) maps scalar field evolution to proper time.

## 7. Effective Friedmann Equation

From the Hamiltonian constraint:

(da/dφ)² = (1/3 M_Pl² α(φ)²) [ (1/2) − V(φ) ]

This equation governs the evolution of the universe in φ-time.

## 8. Summary

- The Hamiltonian constraint relates energy density and geometry.
- By treating φ as time, we derive evolution equations in φ-space.
- This forms the foundation for Waveframe v2.0's emergent time cosmology.

