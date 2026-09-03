# Diffusion for Mood Transfer in Music using Top-K CQT

---

**Research Mentor:** Ray Chen
**Faculty Advisor:** Dr. Christian Grant
**Institution:** University of Florida, Department of Computer & Information Science & Engineering (CISE)
**Duration:** 10 months

---

## Research Focus

This project investigates the application of diffusion models to perform mood transfer in music audio. Traditional approaches to music style transfer often rely on symbolic representations or operate in spectral domains that lose perceptually important details. Our work leverages the Constant-Q Transform (CQT), a time-frequency representation whose logarithmically spaced frequency bins align naturally with musical pitch perception, making it well suited for capturing harmonic and timbral features that convey mood.

The core idea is to train a diffusion model that learns to map the mood characteristics of one musical passage onto another while preserving the original piece's melodic and structural identity. We introduce a Top-K selection mechanism over CQT coefficients to focus the model's attention on the most salient spectral components — those that carry the strongest mood signal — rather than processing the full, high-dimensional representation. This selective approach reduces computational cost and encourages the model to learn musically meaningful transformations rather than superficial spectral shifts.

## Project Responsibilities

My responsibilities on this project span the full research pipeline. I contribute to the design and implementation of the diffusion-based mood transfer architecture, including experimenting with network configurations, loss functions, and the Top-K CQT selection strategy. I am responsible for building and curating the data pipeline — sourcing music audio, computing CQT representations, and annotating mood labels for training and evaluation.

I also conduct quantitative and qualitative evaluations of the model's outputs, comparing generated audio against baselines using both perceptual metrics and listener studies. Beyond the technical work, I participate in weekly meetings with my mentor and faculty advisor, present progress updates, and contribute to the writing of research documentation. This experience has deepened my understanding of generative modeling, audio signal processing, and the iterative nature of research.

---

## Media

<!-- Add a relevant image or video below once available -->
<!-- ![Research figure or demo](../assets/research-media.jpg) -->

*Media coming soon — will be added as the project progresses.*

---

[← Back to Portfolio](../README.md)
