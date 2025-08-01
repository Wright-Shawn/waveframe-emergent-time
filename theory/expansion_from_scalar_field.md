# Expansion Driven by Scalar Field Dynamics

## Overview

In the Waveframe v2.0 model, the scalar field \( \phi \) defines not just energy, but **cosmic time itself**. To make this concrete, we numerically solve for the expansion of the universe driven entirely by \( \phi \) through the Friedmann equation.

We show that even with no radiation or matter content, the energy in the scalar field (kinetic + potential) is sufficient to generate spacetime expansion. This confirms the model’s core claim: **time and expansion emerge from internal scalar dynamics.**

---

## 1. Coupled Equations

We solve the following system:

**Klein-Gordon (field evolution):**
\[
\ddot{\phi} + 3H\dot{\phi} + \frac{dV}{d\phi} = 0
\]

**Friedmann (expansion from energy):**
\[
H^2 = \frac{1}{3} \left( \frac{1}{2} \dot{\phi}^2 + V(\phi) \right)
\]

**Scale Factor:**
\[
\frac{da}{dt} = aH
\]

Assuming \( M_{\text{Pl}} = 1 \), we integrate these simultaneously.

---

## 2. Initial Conditions

We choose:
- \( \phi(0) = 2.5 \)
- \( \dot{\phi}(0) = 0 \)
- \( a(0) = 1 \)
- Potential: \( V(\phi) = \Lambda^4 [1 - \cos(\phi/f)] \) with \( \Lambda = 0.5 \), \( f = 1.0 \)

---

## 3. Results

### 🔭 Scale Factor Evolution

![Scale Factor](../figures/a_t_evolution.png)

This figure shows how the universe expands as a function of scalar field time. The expansion is **smooth but not exponential**, indicating that φ injects energy in a controlled, cyclic way. The absence of a "big bang" singularity aligns with Waveframe's **emergent time** structure.

---

### 🌡️ Hubble Parameter Evolution

![Hubble Parameter](../figures/h_t_evolution.png)

The Hubble parameter \( H(t) \) evolves dynamically in response to φ’s energy content. Initially large due to potential energy, it decays as φ rolls down and oscillates—resulting in a **cooling expansion phase**.

---

## 4. Physical Interpretation

This behavior mirrors features of:
- **Inflation** (early high H)
- **Dark energy** (late-time scalar energy dominance)
- **Emergent time** (no external clock; φ is the only variable with internal motion)

But unlike standard models, **this evolution is internally sourced**—there are no added fluids or fine-tuned components.

---

## 5. Next Steps

Now that \( a(t) \) is derived, we can:
- Reconstruct \( H(z) \) by inverting the relationship
- Compute observational quantities: \( \mu(z) \), \( f\sigma_8(z) \), etc.
- Test for periodicity and recurrence in the waveform (e.g. scalar-driven cyclic cosmology)
- Simulate multiple waveform peaks to represent epochs

We now treat φ as a **self-contained clock and energy source**, completing the core loop of the Waveframe v2.0 hypothesis: **time and expansion are both emergent, oscillatory, and driven by internal field structure.**

---