# BPTM
# BPTM: Biophysical Phase Transition Model

## Overview

The Biophysical Phase Transition Model (BPTM) is a computational neuroscience framework developed to investigate how environmental volatility influences motivational responsiveness, learning efficiency, and adaptation.

The project was created as part of an independent research study examining the relationship between environmental unpredictability and incentive sensitivity among adolescents and young adults living in urban environments.

Rather than treating motivation as a fixed personality trait, the BPTM proposes that motivational responsiveness emerges from continuous interactions between an individual and the stability of their environment. The framework combines concepts from computational neuroscience, reward prediction theory, environmental psychology, and behavioral adaptation into a single predictive model.

## Research Question

Can environmental volatility reduce motivational responsiveness, and does a critical threshold exist beyond which individuals transition into a less adaptive motivational state?

## Core Hypothesis

The model proposes that increasing environmental volatility gradually reduces an individual's sensitivity to rewards and incentives.

Once environmental volatility exceeds a critical threshold, motivational responsiveness becomes significantly less efficient, producing a state referred to within the model as motivational numbness.

## Main Variables

### Volatility Index (VI)

A measure of environmental unpredictability.
VI is derived from self-reported instability in daily routines, planning, behavioral consistency, and emotional predictability. Higher values indicate environments that are more difficult to predict.

### Incentive Sensitivity Index (ISI)

A measure of motivational responsiveness.

ISI estimates how strongly an individual responds to goals, rewards, opportunities, and future outcomes. Higher values indicate greater motivational sensitivity.

### Learning Responsiveness Coefficient (α)

A responsiveness efficiency measure calculated as:

α = ISI / VI

Within the BPTM framework, α represents the amount of motivational responsiveness preserved per unit of environmental volatility.

### Population Ambition Deficit (PAD)

A population-level estimate of motivational capacity lost after environmental volatility exceeds the identified threshold.
PAD provides a way to translate individual motivational changes into potential social and economic consequences.

### Resilience Coefficient (Rc)

The discrepancy between observed motivational sensitivity and model-predicted motivational sensitivity.

Rc quantifies how closely individual outcomes align with expected responses to environmental volatility and may reflect additional protective factors not included in the current model.

## Findings From The Initial Study

Sample Size: N = 50

Key observations included:

* Mean Volatility Index (VI): 3.66
* Weak-to-moderate negative correlation between VI and ISI (R ≈ -0.36)
* Evidence for a behavioral transition near VI = 3.0
* Approximately 6.43% reduction in motivational responsiveness above the threshold
* Adaptive-state responsiveness approximately twice that observed in the high-volatility state
* Monte Carlo simulations suggested that the observed PAD estimate remained relatively stable under repeated sampling

Importantly, the results suggest that environmental volatility may not simply lower motivation uniformly. Instead, volatility appears to increase differences between individuals, separating those who remain resilient from those who experience motivational decline.

## Software Platform

This repository includes an interactive research platform built with Streamlit.

The platform allows users to:

* Upload survey datasets
* Calculate BPTM variables automatically
* Visualize relationships between VI and ISI
* Explore adaptive and numbness states
* Estimate PAD values
* Perform piecewise regression analysis
* Run Monte Carlo population simulations
* Evaluate predictive model performance
* Export processed datasets

## Why This Matters

Many educational, social, and economic interventions assume that motivation is primarily determined by personal effort or available opportunities. The BPTM explores an alternative possibility:

Environmental stability itself may function as a hidden component of human capital. If motivation depends partly on environmental predictability, then improving educational outcomes may require not only increasing opportunities but also reducing environmental volatility.

## Current Status

The BPTM should be considered an exploratory framework.

The model requires:

* Larger sample sizes
* Cross-cultural validation
* Longitudinal testing
* Independent statistical review
* Replication across different populations

The current results should therefore be interpreted as preliminary evidence rather than definitive proof.

## Future Directions

Future work will focus on:

* National-scale validation studies
* Urban versus rural comparisons
* Longitudinal tracking of motivational change
* Integration with educational outcomes
* Investigation of resilience factors
* Development of policy applications

---

## Author

Independent student researcher investigating the relationship between environmental volatility, learning responsiveness, and motivational adaptation through computational modeling. Studied at programs such as Neuromatch Computational Neuroscience, MIT OCW linear algebra courses and Duke Medical Neuroscience program

---

## License

This repository is intended for academic, educational, and research purposes.

