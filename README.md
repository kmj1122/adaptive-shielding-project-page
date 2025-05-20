# Project Page: Runtime Safety through Adaptive Shielding

This repository hosts the project page for the paper: "Runtime Safety through Adaptive Shielding: From Hidden Parameter Inference to Provable Guarantees."

**Live Project Page:** [https://kmj1122.github.io/adaptive-shielding-project-page/](https://kmj1122.github.io/adaptive-shielding-project-page/)

## Abstract
Variations in hidden parameters, such as a robot’s mass distribution or friction, pose safety risks during execution. We develop a runtime shielding mechanism for reinforcement learning, building on the formalism of constrained hidden-parameter Markov decision processes. Function encoders enable real-time inference of hidden parameters from observations, allowing the shield and the underlying policy to adapt online. The shield constrains the action space by forecasting future safety risks (such as obstacle proximity) and accounts for uncertainty via conformal prediction. We prove that the proposed mechanism satisfies probabilistic safety guarantees and yields optimal policies among the set of safety-compliant policies. Experiments across diverse environments with varying hidden parameters show that our method significantly reduces safety violations and achieves strong out-of-distribution generalization, while incurring minimal runtime overhead.

## Setup
This page is built using the "Academic Project Page Template" by Eliahu Horwitz. The content is primarily in `index.html` and assets are in the `static/` directory.

To view the page locally, you can usually open `index.html` in a web browser. For deployment, GitHub Pages is recommended.

For questions about the research, please refer to the contact information on the project page or in the paper.