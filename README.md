# Ernest Borysenko

PhD researcher at the University of Bath building algorithms and dependable software for scientific work.

I enjoy owning the full path from a mathematical idea to a usable product: formulation, implementation, evaluation, testing, deployment, and maintenance.

## What I work on

- Numerical inference, inverse problems, and uncertainty estimation
- Scientific Python packages with tested numerical kernels and reproducible workflows
- Research-software discovery, information retrieval, and relevance ranking
- Reliable web services, background processing, and external API integrations
- Computational quantum chemistry and experimental model validation

## Selected Projects

### [SciScope](https://github.com/Mephistos-ML/SciScope)

A deployed service for discovering and monitoring scientific software across public repositories. I designed and built it end to end.

- FastAPI and React/TypeScript application with PostgreSQL persistence and database migrations
- LLM-assisted query planning, multi-source retrieval, and explainable evidence-based ranking
- Recoverable background jobs with concurrent worker claims, renewable leases, and atomic publication
- Provider timeouts, retries, rate-limit handling, and preservation of partial results
- PostgreSQL concurrency tests, browser tests against running services, and CI
- Repository subscriptions and personalised activity feeds

Try it at [sciscope.uk](https://sciscope.uk/).

### [SimpNMR](https://github.com/Mephistos-ML/simpnmr-x)

Open-source scientific Python software connecting computational models with experimental NMR data. My current research and engineering development takes place on the `simpnmr-x` working branch.

- Moment-based inference for parameter estimation without explicit signal assignment
- Analytical Jacobians, constrained optimization, and uncertainty diagnostics
- Numerical kernels separated from CLI interfaces, configuration, and workflow orchestration
- Scientific correctness tests, deterministic recovery cases, and reproducible benchmarks
- Versioned releases, documentation, and Python-version compatibility checks in CI

### [SimpNMR-X Synth](https://github.com/Mephistos-ML/simpnmr-x-synth)

A companion generator for controlled SimpNMR validation and machine-learning experiments.

- Deterministic datasets with retained physical ground truth
- Replayable parameter-recovery cases and paired moments-to-parameters datasets
- Provenance manifests and explicit generation settings

## Research

My PhD combines mathematical modelling, numerical methods, and experimental validation. I investigate which conclusions remain reliable when computational assumptions change, where parameters are poorly constrained, and how models can be reformulated to reduce computational cost.

First-author preprint:
[Ab initio-assisted analysis of NMR data of paramagnetic metal complexes in solution](https://chemrxiv.org/doi/full/10.26434/chemrxiv.15001463/v1).

## Engineering approach

I care about software that other people can use and develop further: clear interfaces, explicit configuration, testable numerical code, CI, documentation, and reliable deployment.

I am interested in roles where research and engineering meet, especially scientific software, developer tooling, and dependable backend systems.

## Tech

Python · TypeScript · SQL · FastAPI · React · PostgreSQL  
NumPy · SciPy · pytest · GitHub Actions · Docker · Sphinx

## Links

- [LinkedIn](https://www.linkedin.com/in/ernestborysenko)
- [SciScope — live service](https://sciscope.uk/)
- [SimpNMR — documentation](https://simpnmr.org/)
- [SimpNMR-X — PyPI package](https://pypi.org/project/simpnmr-x/)
