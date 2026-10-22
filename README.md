## Sara Shahin

Machine learning researcher working on generative models for sparse,
high-dimensional spatiotemporal data. PhD candidate at Queen Mary University
of London, supervised by Axel Rossberg.

My work is on conditional generative modelling: recovering full system states
from partial, noisy observations, with ensemble-based uncertainty. The methods
are domain-agnostic. I currently test them on species distribution data, and
have previously worked on multimodal classification and automated assessment.

Methods I work with: denoising diffusion models, graph neural networks,
temporal transformers, U-Net architectures, ensemble calibration,
individual-based and ODE simulation.
Stack: Python, PyTorch, NumPy, CuPy, Numba, scikit-learn, Keras, Docker, Git.

### Selected work

**MetaDiffusion**: a 79.6M-parameter conditional diffusion model that
reconstructs multi-species range maps from sparse occurrence records, with
ensemble-based uncertainty. A graph neural network encodes species
interactions, a temporal transformer handles dynamics, and a U-Net denoiser
generates the map. Trained on 240 simulated metacommunities, so every
reconstruction can be checked against the true range. On held-out
communities, reconstructed ranges match the truth in size, fragmentation and
spread (Kolmogorov-Smirnov distances 0.13, 0.23, 0.095).
Poster B-S.B.31, ECCB 2026 · [Paper](https://zenodo.org/records/22175909) ·
[Code](https://github.com/sarashahin/PSD-Metacommunity-Dispersal_AI) ·
[DOI 10.5281/zenodo.23195560](https://doi.org/10.5281/zenodo.23195560)

**PSD metacommunity framework**: a simulation technique unifying four
modelling paradigms as limiting cases of one process, running roughly two
orders of magnitude faster than the ODE approach it replaces. Preprint:
[10.64898/2026.04.21.719942](https://doi.org/10.64898/2026.04.21.719942)

**Multimodal fake news detection**: joint text and image classification for
misinformation detection.

**Automated grading (NART)**: automated scoring of a standardised
assessment instrument.

### Publications

- Sara Shahin, Axel G. Rossberg. *MetaDiffusion: A process-aware conditional
  diffusion model for multi-species spatial range reconstruction from sparse
  observations.* Poster B-S.B.31, ECCB 2026.
  [Poster](https://eccb.performedia.com/poster/b-s-b-31-metadiffusion-a-process-aware-conditional-diffusion-model-for-multi-species-spatial-arranged-reconstruction-from-sparse-observations/)
- Sara Shahin, Jacob D. O'Sullivan, Axel G. Rossberg. *A modelling framework
  unifying four paradigms of metacommunity theory.* bioRxiv preprint, 2026.
  [doi:10.64898/2026.04.21.719942](https://doi.org/10.64898/2026.04.21.719942)
- Shashank Pulijala, Sara Shahin, Tapadhir Das, Raj Mani Shukla. *Evaluation
  of Ensemble Learning for Mitigating Adversarial Attacks in Industrial Object
  Detection.* IEEE conference paper, 2024.
  [doi:10.36227/techrxiv.171561173.31420188/v1](https://doi.org/10.36227/techrxiv.171561173.31420188/v1)

### Education

- PhD, Spatio-temporal process-aware models for biodiversity prediction,
  Queen Mary University of London, 2025 to present
- MSc Artificial Intelligence, Anglia Ruskin University, 2023 to 2024, Distinction
- BSc Machine Learning and Artificial Intelligence, Goldsmiths, University of
  London, 2020 to 2023, First Class

### Awards

- Alan Turing Institute Data Study Group, selected PhD researcher, Sept 2025
- Open Source Summit Europe 2025, fully funded scholarship, Amsterdam
- Bertelsmann Scholarship, Genomic Data Science track
- Women in Computer Science and Engineering, sponsored delegate, Milan

### Elsewhere

ORCID [0009-0000-7847-6242](https://orcid.org/0009-0000-7847-6242) ·
[LinkedIn](https://www.linkedin.com/in/sara-shahin-ai/) ·
[s.shahin@qmul.ac.uk](mailto:s.shahin@qmul.ac.uk) ·
Queen Mary University of London
