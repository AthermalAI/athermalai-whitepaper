# AthermalAI White Paper: The Stochastic-Decay Bit (sd-bit)

This repository contains the white paper detailing the scholastic model for the AthermalAI project.

**The full paper is available as AthermalAI White Paper.pdf in this repository.**

## Abstract

Modern stochastic computing, particularly in hardware-based probabilistic neural networks, relies on p-bits (probabilistic bits) that generate random fluctuations. The dominant p-bit models are "thermal," meaning their stochasticity is derived from thermal noise in a circuit. While functional at room temperature, this approach is fundamentally susceptible to thermal drift, requiring significant energy overhead for noise amplification, stabilization, and continuous calibration.

This paper proposes a novel hardware-native p-bit, the **Stochastic-Decay bit (sd-bit)**, which offers an "athermal" alternative. The sd-bit derives its stochasticity not from temperature-dependent thermal noise, but from the temperature-independent quantum decay of a microscopic, low-activity isotope integrated directly into the chip substrate.

We present a scholastic model for the sd-bit, analogous to the 1970s Intel soft-error problem, where random particle strikes are a controlled feature, not a bug. We detail the device's proposed hardware architecture, its mechanism of action, and the governing physics. We demonstrate that the time-averaged behavior of an sd-bit, governed by a Poisson process, naturally and robustly emulates a Bernoulli distribution.

The primary advantage of this model is its stability. By grounding its probabilistic behavior in a fundamental physical constant (the decay rate $\lambda$) instead of a fluctuating environmental variable (temperature $T$), the sd-bit eliminates thermal drift, simplifies calibration, and promises a more energy-efficient and scalable foundation for future probabilistic processing units (PPUs).

## License

This work is released under the **MIT License**. See the `LICENSE` file for details.
