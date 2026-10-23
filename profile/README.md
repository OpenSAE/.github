<p align="center">
  <img src="https://raw.githubusercontent.com/OpenSAE/.github/main/opensae_banner.png" alt="OpenSAE — From learned features to faithful explanations" width="100%" />
</p>

<p align="center">
  <strong>Building open foundations for understanding and evaluating LLMs.</strong>
</p>

<p align="center">
  <a href="https://atheavenma.github.io/opensae/index.html"><strong>🌐 Official Website</strong></a> · <a href="https://huggingface.co/OpenSAE"><strong>🤗 Hugging Face</strong></a>
</p>

---

## Mission

OpenSAE advances the science of how neural networks represent information and how their internal structures shape behavior. We develop theory, methods, and open research tools to make explanations testable and interventions reproducible.

Sparse autoencoders are a central starting point, connecting our work to broader questions in mechanistic interpretability and representation learning.

## Research Directions

At OpenSAE, we study how neural networks represent information and how those representations shape model behavior. Our research focuses on:

- Understanding what learned features represent and how they are organized within neural networks.

- Investigating how individual features and their interactions influence model behavior.

- Studying how representations change across inputs and contexts, and what remains consistent.

- Developing tools and rigorous evaluations to test the reliability of explanations and interventions.

## Research & Infrastructure

- 🧱 [**SAEBase**](https://github.com/OpenSAE/SAEBase)

    Research infrastructure for understanding, testing, and modifying SAE features in LLMs.

- 🧩 [**Behavioral Compositionality of Sparse Autoencoder Representations**](https://github.com/OpenSAE/SAE-Behavioral-Compositionality)

    Measures how much model behavior depends on interactions among its SAE features.

- 🔀 [**Representation Redistribution in Sparse Autoencoders**](https://github.com/OpenSAE/Redistribution-Sensitivity-Score)

    Detects consistent shifts in SAE feature activity when the same request is presented differently.

- 🧭 [**Sparse Autoencoders Do Not Guarantee Local Features**](https://github.com/OpenSAE/SAE-Input-Localization)

    Shows that SAE features can look simple while depending on many interacting inputs.

## Opportunities

We share research, code, evaluation protocols, and tools to support an open, rigorous, and reproducible understanding of LLMs. If you're interested in our research and would like to join OpenSAE, please contact us at hma232@wisc.edu.
