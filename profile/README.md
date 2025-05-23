
# Project Ekala

[![Discord](https://img.shields.io/discord/1257327654047187024?label=Discord&logo=discord&logoColor=white)](https://discord.gg/DgC9Snxmg7)

## Our Mission

To revolutionize store-based systems by creating a modern, user-friendly platform that combines innovative build scheduling, maintainable package management, and intelligent automation.

We will:

1. Pioneer the Atom format for reproducible, verifiable, and efficiently transferable package definitions
2. Develop a powerful, API-driven build scheduler that optimizes evaluation and caching
3. Create an intuitive CLI that makes store-based systems accessible and productive
4. Establish patterns and tools for maintaining large package sets through automation and static analysis
5. Build a modular ecosystem that enables seamless extension and adaptation

Our efforts preserve Nix's core strengths in reproducibility while dramatically improving:

- Developer experience through better tooling and APIs
- Package maintenance through automation and static guarantees
- System scalability through optimized scheduling and caching
- Code reuse through the Atom format and modular designs of ekapkgs

<noscript><a href="https://liberapay.com/Ekala/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

## Key Projects

- [**eka-ci**](https://github.com/ekala-project/eka-ci): A CI/CD tool attempting to make large Nix package curation sustainable
- **ekapkgs**: A hard poly-repo fork of nixpkgs.
  - [**ekapkgs roadmap**](https://github.com/ekala-project/ekapkgs-roadmap): A road-map listing out the milestones and goals to get to our ultimate goal
  - [**nix-lib**](https://github.com/ekala-project/nix-lib): A hard fork of `nixpkgs/lib` code base. Contains addtional utilities for Ekapkgs.
  - [**stdenv**](https://github.com/ekala-project/stdenv): **(DEPRECATED)** the standard environment for Nix builds, abstracted to its own repository
  - [**corepkgs**](https://github.com/ekala-project/corepkgs): a minimal core of well maintained code, useful for maintaining a larger package set
  - **Language and Ecosystem Overlays**: Overlays downstream of corepkgs. These are separately maintained and curated.
  - **ekapkgs**: Overlay which re-combines nix-lib, corepkgs, language and ecosystem overlays into a single entrypoint. Similar to nixpkgs.
- [**eka**](https://github.com/ekala-project/eka): The CLI, defining the core logic for the Atom format, and offering a truly high-level interface into the store based world of Nix like tools.
  - status: WIP private pre-alpha
  - license: GPLv3 with amendments
- [**atom**](https://github.com/ekala-project/atom): The novel Nix module system that enables bounded, sensible evaluation for Nix code.
  - status: WIP private beta
  - license: MPL
- [**EEP**](https://github.com/ekala-project/eeps): Ekala Enhancement Proposals
  - status: open for submissions
- [**eos**](https://github.com/ekala-project/eos): The evaluation & build scheduler gateway API binary
  - status: conceptual


## Project Ethic

We are committed to ethical practices and enabling a productive project environment.
We invite all contributors and users to review and adhere to our [Code of Ethics](https://github.com/ekala-project/.github/tree/master?tab=coc-ov-file).

## Get Involved

- [Chat (Discord)](https://discord.gg/DgC9Snxmg7)
