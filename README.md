# A Workflow for Infectious Disease Modelling

[![Build and Deploy Paper](https://github.com/seabbs/infectious-disease-modelling-with-multiple-datasources/actions/workflows/build-paper.yml/badge.svg?branch=main)](https://github.com/seabbs/infectious-disease-modelling-with-multiple-datasources/actions/workflows/build-paper.yml)
[![DOI](https://zenodo.org/badge/991854282.svg)](https://doi.org/10.5281/zenodo.19097427)

> **Note**: This repository is synchronised with Overleaf. The main branch reflects the current state of the manuscript.

**[Read the paper](https://seabbs.github.io/infectious-disease-modelling-with-multiple-datasources/paper.pdf)** (PDF) | **[Supplementary information](https://seabbs.github.io/infectious-disease-modelling-with-multiple-datasources/supplementary.pdf)** (PDF)

## Abstract

Infectious disease models can be used to inform critical public health decisions, yet often do not follow systematic development and validation practices.
The infectious disease modelling community has been slow to adopt rigorous model development and criticism cycles such as the Bayesian workflow, even as these approaches have become increasingly used in other domains. Recent outbreaks have demonstrated some domain-specific challenges that infectious disease modelling faces, including evolving research questions, new or poorly characterised data sources, and adapting surveillance systems.
Here, we suggest the adoption of a workflow for developing and evaluating infectious disease models, which builds on existing generic Bayesian workflows but focuses on domain-specific challenges. This workflow is designed for anyone developing an infectious disease model, and for users of model outputs who need to be able to evaluate modelling studies. At each stage, we provide recommendations based on our experience. We begin by outlining an approach for characterising epidemiological data source properties through a structured checklist. We then present an iterative workflow that applies the Bayesian workflow to the infectious disease domain, with the checklist informing decisions throughout each workflow stage. The workflow proposed here includes defining the research question, development of Directed Acyclic Graph representations of process and observation models in a state-space framework, model modularisation, inference and computation choices, model specification and validation, integration method selection, and real-world considerations.
Throughout, we identify feedback loops where later decisions impact earlier choices. We also give guidance on using the workflow in evolving settings, such as outbreaks, and on how to report its use. To demonstrate this workflow, we provide a schematic case study that progressively integrates data sources for estimating transmission intensity.
At each stage, we give examples of navigating real-world trade-offs between model complexity, computational feasibility, and inferential goals.
This case study highlights how different data types can provide complementary information but may also impact workflow choices.
Our suggested framework emphasises parsimony, modularity, interpretability, and model criticism. By proposing domain-specific workflow practices, we aim to provide a foundation for improving the quality and transparency of infectious disease modelling, particularly during outbreaks where flexible, but principled, approaches are essential.

## Authors

![Team Photo](figures/team-photo.jpg)

## Repository Structure

```
├── main.tex              # Main manuscript file
├── supplementary.tex     # Supplementary information
├── figures/              # Manuscript figures and plots
├── supplement_figures/   # Supplementary figures
├── resources/            # Supporting materials and context for LLMs
└── README.md            # This file
```

## Citation

```bibtex
@misc{abbott2026workflow,
  title = {A Workflow for Infectious Disease Modelling},
  author = {Abbott, Sam and Li, Xiahui and Alahakoon, Punya and
            Temfack, Dhorasso and Bracher, Johannes and
            G{\"u}nther, Felix and Van Elsland, Sabine and
            Lison, Adrian and Hay, James and Eales, Oliver and
            Kenah, Eben and McCaw, James and Shearer, Freya and
            Funk, Sebastian and Sofonea, Mircea T. and
            Nouvellet, Pierre and De Angelis, Daniela and
            Plank, Michael J. and Cori, Anne and
            Presanis, Anne},
  year = {2026},
  doi = {10.5281/zenodo.19097427},
  url = {https://seabbs.github.io/infectious-disease-modelling-with-multiple-datasources/paper.pdf}
}
```

## Contact

For questions about this manuscript, please contact:
- Sam Abbott (sam.abbott@lshtm.ac.uk)
- Anne Cori (a.cori@imperial.ac.uk)
- Anne Presanis (anne.presanis@mrc-bsu.cam.ac.uk)
- Michael Plank (mike.plank@canterbury.ac.nz)

## License

MIT License - see [LICENSE](LICENSE) file for details.