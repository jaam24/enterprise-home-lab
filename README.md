# Enterprise Home Lab

A hands-on infrastructure lab for learning, testing, and documenting systems administration, networking, virtualization, and security. This repository is a portfolio of the work completed, the decisions behind it, and the results verified.

## Goals

- Build a practical lab that supports professional development in IT infrastructure and security.
- Document hardware, network design, configurations, tests, and troubleshooting in a reproducible way.
- Develop projects that can be explained and demonstrated in a portfolio or interview.
- Keep planned work separate from deployed and verified work.

## Current status

**Repository foundation in progress.** The hardware inventory is being documented. Roles, operating systems, and services will be recorded as they are selected and verified.

| Equipment | Current role or status |
| --- | --- |
| HP Z2 Mini G9 | Intended primary lab machine; deployment pending |
| Dell Precision 5810 | Available; build and troubleshooting notes pending |
| Dell Precision T3600 | Available; role pending |
| Dell PowerEdge T310 | Available; role pending |
| Cisco Catalyst 2960-S | Available managed switch |
| BayStack 5520-48T-PWR | Available managed switch |
| Personal desktop | Administration and testing workstation |
| Lenovo X1 Carbon Gen 5 | Portable administration and testing client |

Specifications and verification status live in [the hardware inventory](docs/hardware/inventory.md).

## Repository guide

| Location | Purpose |
| --- | --- |
| [docs/hardware](docs/hardware/inventory.md) | Equipment inventory and device build notes |
| [docs/architecture](docs/architecture/README.md) | Current topology and design decisions |
| [docs/networking](docs/networking/README.md) | Addressing, switching, routing, and validation |
| [docs/virtualization](docs/virtualization/README.md) | Host and virtual machine setup |
| [docs/troubleshooting](docs/troubleshooting/README.md) | Problems, evidence, fixes, and retests |
| [projects](projects/README.md) | Finished, demonstrable implementations |
| [configs](configs/README.md) | Sanitized example configurations and scripts |
| [images](images/README.md) | Selected photos, diagrams, and screenshots |
| [CHANGELOG.md](CHANGELOG.md) | Dated project and documentation updates |

## Roadmap

These are **ideas, not deployed components**. The sequence and tooling may change as the lab develops.

1. Inventory and validate the available hardware.
2. Choose the host operating system and virtualization design.
3. Document the actual network topology and address plan.
4. Build and test administration, identity, security, and monitoring services.
5. Add repeatable automation and recovery procedures.

Each completed implementation will receive a write-up in `projects/` covering its objective, design, setup, validation, troubleshooting, and lessons learned.

## Documentation approach

Entries should identify what was observed, what changed, and how the result was checked. Screenshots and photos should show meaningful evidence, with sensitive information removed before publishing. Example configurations must exclude passwords, tokens, keys, and other secrets.

This repository will grow as lab work is completed; proposed technologies will not be presented as deployed until verified.
