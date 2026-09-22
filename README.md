# Ernest Borysenko

PhD researcher at the University of Bath, building scientific software for research-software discovery, inverse modelling, and paramagnetic NMR.

## What I work on

- Scientific Python tooling for computational chemistry workflows
- Paramagnetic NMR analysis and susceptibility tensor fitting
- Reproducible research software, CLI tools, and data pipelines
- Physics-aware dataset generation for ML workflows
- Scientific software discovery, retrieval, and relevance ranking

## Selected Projects

### [SciScope](https://github.com/Mephistos-ML/SciScope)

Web service for discovering and monitoring domain-specific scientific software across public repository hosts.

- AI-assisted query planning and multi-source repository and code retrieval
- Admission gates and transparent heuristic ranking for specialised scientific software
- Async search, provider-level failure isolation, structured observability, and personalised update feeds
- FastAPI/PostgreSQL backend with a React/TypeScript frontend

### [SimpNMR-X](https://github.com/Mephistos-ML/simpnmr-x)

Independently maintained research and engineering fork of SimpNMR for prediction, inverse fitting, and analysis of paramagnetic NMR spectra from experimental and *ab initio* inputs. It focuses on stable pipelines, reproducible validation, and maintainable scientific-software architecture; mature changes can later inform upstream SimpNMR development.

- Physics-based PCS, hyperfine, relaxation, and susceptibility-tensor workflows
- Fixed, Hungarian-assignment, and GMM moment-matching inverse fits with weighted objectives and analytic Jacobians
- Variable-temperature modelling, uncertainty diagnostics, objective maps, visualisation, CLI workflows, documentation, and packaged releases

### [SimpNMR-X-Synth](https://github.com/Mephistos-ML/simpnmr-x-synth)

Reproducible synthetic pNMR dataset generator for SimpNMR-X fitting validation and supervised machine-learning workflows.

- Deterministic geometry-based generation of susceptibility, linewidth, and diamagnetic-shift latents
- SimpNMR-X-replayable fitting artefacts plus paired moments-to-parameters ML datasets
- Provenance-complete synthetic data pipelines
- Designed as an upstream tool for simulation and ML experiments

## Focus

I am particularly interested in software at the intersection of scientific modelling and practical engineering: typed configurations, reproducible pipelines, testable numerical code, retrieval and ranking systems, and products that make specialised research software easier to discover and use.

## Tech

`Python` `FastAPI` `PostgreSQL` `NumPy` `SciPy` `pytest` `scientific computing` `research software` `retrieval systems` `ranking` `observability` `TypeScript` `React`

## Links

- GitHub: [Mephistos-ML](https://github.com/Mephistos-ML)
- SciScope: [sciscope.uk](https://sciscope.uk/)
- SimpNMR-X documentation: [simpnmr.org](https://simpnmr.org/)
- SimpNMR-X package: [PyPI / simpnmr-x](https://pypi.org/project/simpnmr-x/)
