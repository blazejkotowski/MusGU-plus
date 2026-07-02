<div align="center">

# MusGU+: A Musician-Centered Evaluation Framework and Discovery Tool for Generative Music AI

*Anonymous authors* (paper currently under review)

**MusGU+ (Music-Generative Usable+ AI)** is a musician-centered evaluation framework designed to assess how generative music models can be *adapted*, *used*, and *controlled* in real-world creative contexts.


🔍 Explore the **[MusGU+ discovery tool](https://lauraibnz.github.io/MusGU-plus/)**

[![License: MIT](https://img.shields.io/badge/License-Apache_2.0-green.svg)](LICENSE)

</div>

---

## The MusGU+ Framework

MusGU+ evaluates generative music models along three complementary dimensions, each framed around a core practical question:

- **Adaptability** — *Can I realistically adapt this model to my own data?*
- **Usability** — *Can I access, run, and integrate this model into my music-making workflow?*
- **Controllability** — *Can I guide the model in musically meaningful and interpretable ways?*

Each dimension comprises multiple criteria (e.g., hardware requirements, interface availability, conditioning inputs, control parameters) and is evaluated on a three-level scale reflecting the degree of support provided: **fully**, **partially**, **not**.

📖 Read the **[detailed evaluation criteria](https://lauraibnz.github.io/MusGU-plus/framework)**.


## A Discovery Tool for Musicians

MusGU+ is designed as an interactive discovery tool rather than a fixed leaderboard. It allows musicians to explore, filter, and compare generative music models based on specific criteria and tags, highlighting differences in adaptability, usability, and controllability. This supports early-stage exploration and informed selection of models that best fit different creative practices and workflow needs.

## Contributing

If you would like to help expand or refine MusGU+, there are two main ways to contribute:

- **Suggest a new model**. The simplest option is to open an issue using the **[Suggest a New Model](https://github.com/lauraibnz/MusGU-plus/issues/new?template=suggest-a-new-model.md)** template. A brief explanation and any relevant links are enough; maintainers will take care of the detailed evaluation. More experienced contributors can instead create a new branch, add a YAML evaluation in [`projects/`](projects) following [`projects/_template.yaml`](projects/_template.yaml), and submit a pull request.
- **Propose changes to an existing evaluation**. If you think a current model entry should be updated, corrected, or expanded, you can open an issue or submit a pull request with supporting evidence.


## Relationship to MusGO

MusGU+ builds on insights from the **[MusGO framework](https://roserbatlleroca.github.io/MusGO_framework/)**. MusGO (Music-Generative Open AI) is an openness-focused evaluation framework for music-generative AI. While MusGO focuses on transparency and responsible research practices, MusGU+ supports informed selection and practical adoption of generative music models by musicians.
