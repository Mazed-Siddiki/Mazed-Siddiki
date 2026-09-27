# Md Abdul Mazed Siddiki

MSc in Artificial Intelligence and Robotics, CY Cergy Paris Université / ENSEA, graduated September 2026 after a research internship at the **ETIS Laboratory**.

I work where computer vision meets computational neuroscience: taking a raw visual signal and asking whether a biologically plausible learning rule can develop the kind of representation a brain actually uses.

## Master's research: artificial speed cells from optical flow

Speed cells in the entorhinal cortex fire in proportion to how fast an animal is moving, and recent work shows their tuning also rescales with the geometry of the surroundings. No computational model had reproduced that from vision alone.

My thesis builds one. A single camera in the CARLA simulator gives optical flow, the flow is projected onto the road plane to recover speed in metres per second, and an unsupervised Hebbian-Oja network learns from that signal with no speed labels at any point. The units that emerge reproduce the documented properties of real speed cells. A second input variant, which keeps the scene geometry instead of dividing it out, also reproduces the environment sensitivity, verified with paired statistics, seed sweeps, hyperparameter sweeps and held-out environments.

## Interests

Computer vision · self-supervised and representation learning · bio-inspired and neuro-inspired models · trustworthy and fair machine learning

## Selected work

- **Speed cells from optical flow** (MSc thesis, ETIS) — unsupervised Hebbian-Oja population trained on monocular optical flow in CARLA
- **Facial emotion representation learning** (MSc research project, ETIS) — supervised autoencoder and variational autoencoder architectures, derived from first principles including the ELBO and the reparameterisation trick
- **Algorithmic fairness in income prediction** — bias audit and mitigation with IBM AIF360, improving disparate impact from 0.305 to 0.637
- Earlier coursework in PySpark and Databricks, multimodal learning, R and Tableau visualisation, and classical machine learning

## Background

- MSc Artificial Intelligence and Robotics, CY Cergy Paris Université / ENSEA, 2025 to 2026
- BSc Software Engineering, Sichuan University, China, on a full Belt and Road Initiative scholarship

Currently looking for PhD positions and research roles in computer vision and representation learning.

## Contact

mdabdulmazed.siddiki@ensea.fr
