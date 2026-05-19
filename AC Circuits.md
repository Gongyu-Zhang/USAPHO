## AC circuits in USAPhO: important, but not every year

AC circuits are part of the broader **E&M → circuits/resonance** category. In 2016–2025 USAPhO, they appear **occasionally**, but when they appear, they are usually **advanced and conceptual**, not just plug-in impedance problems.

### Most relevant USAPhO problems

|        Year | Problem                                        | AC / circuit relevance                                                             |
| ----------: | ---------------------------------------------- | ---------------------------------------------------------------------------------- |
| **2016 A2** | High-gain / op-amp-style circuit               | Feedback circuits, RC behavior, signal processing style                            |
| **2018 A2** | Nonlinear I-V device with resistors/capacitors | Circuit dynamics, nonlinear response                                               |
| **2024 A1** | LC oscillator with radiative loss              | Oscillating circuits, energy transfer, damping                                     |
| **2024 B3** | RLC quality factor measurement                 | Most directly AC-circuit related: resonance, damping, Q factor, frequency response |

So, AC circuits are **not a dominant topic**, but they are **high-value** because they combine E&M, differential equations, resonance, and energy methods.

---

## What you should know for USAPhO AC circuits

### 1. Basic phasor/impedance ideas

You should know:

[
Z_R = R
]

[
Z_L = i\omega L
]

[
Z_C = \frac{1}{i\omega C}
]

For a series RLC circuit:

[
Z = R + i\omega L + \frac{1}{i\omega C}
]

or

[
Z = R + i\left(\omega L - \frac{1}{\omega C}\right)
]

Current amplitude:

[
I_0 = \frac{V_0}{|Z|}
]

where

[
|Z| = \sqrt{R^2 + \left(\omega L - \frac{1}{\omega C}\right)^2}
]

---

### 2. Resonance

For an ideal LC or RLC circuit, resonance occurs when

[
\omega L = \frac{1}{\omega C}
]

so

[
\omega_0 = \frac{1}{\sqrt{LC}}
]

At resonance, the inductive and capacitive reactances cancel.

For a series RLC circuit:

[
Z = R
]

so the current is maximized.

---

### 3. Energy in LC circuits

USAPhO often prefers energy reasoning over memorized formulas.

Energy in capacitor:

[
U_C = \frac{1}{2}CV^2 = \frac{Q^2}{2C}
]

Energy in inductor:

[
U_L = \frac{1}{2}LI^2
]

In an ideal LC oscillator, energy oscillates between electric-field energy in the capacitor and magnetic-field energy in the inductor.

[
\frac{Q^2}{2C} + \frac{1}{2}LI^2 = \text{constant}
]

The charge obeys

[
\frac{d^2Q}{dt^2} + \frac{1}{LC}Q = 0
]

so

[
Q(t) = Q_0 \cos(\omega_0 t + \phi)
]

---

### 4. Damping and quality factor

For a weakly damped RLC circuit,

[
Q_{\text{factor}} \approx \frac{\omega_0}{\Delta \omega}
]

where (\Delta \omega) is the resonance width.

For a series RLC circuit,

[
Q_{\text{factor}} = \frac{\omega_0 L}{R}
]

also

[
Q_{\text{factor}} = \frac{1}{\omega_0 RC}
]

These are especially relevant to **2024 B3**, which focused on resonance and quality factor.

---

## How important is it?

I would rank AC circuits as:

| Importance       | Topic                                             |
| ---------------- | ------------------------------------------------- |
| Very high        | Mechanics, electrostatics, magnetism, induction   |
| High             | DC circuits, LC/RLC oscillations, resonance       |
| Medium-high      | AC phasors and impedance                          |
| Medium           | Op-amp-style/high-gain circuit models             |
| Lower but useful | Transmission lines, filters, detailed electronics |

For USAPhO preparation, do **not** spend weeks on AP-style AC circuit drill problems. Instead, focus on:

1. LC/RLC energy exchange
2. resonance frequency
3. damping and quality factor
4. impedance and phase
5. driven oscillators
6. interpreting frequency-response graphs

The most USAPhO-like AC-circuit skill is understanding **circuits as physical oscillators**, not just doing impedance algebra.
