# OpenAN Project Governance

OpenAN is a project hosted by [Linux Foundation Networking (LFN)](https://lfnetworking.org) under The Linux Foundation. This document describes the governance structure and processes for the project.

## Overview

OpenAN operates under an open governance model that encourages participation and contribution from any interested party. The project's Technical Steering Committee (TSC) provides technical oversight and strategic direction.

## Technical Steering Committee (TSC)

The TSC is the primary governing body for the OpenAN project's technical direction.

### Responsibilities

The TSC is responsible for:

- Setting the overall technical direction and roadmap for the project
- Approving new sub-projects and repositories
- Establishing and overseeing working groups
- Defining release processes and quality standards
- Managing the lifecycle of project components
- Resolving technical disputes
- Ensuring alignment with the Technical Charter

### Composition

The TSC is composed of:

- **TSC Chair:** Elected by TSC voting members to serve a one-year term, renewable
- **TSC Vice Chair:** Elected by TSC voting members to serve a one-year term, renewable
- **TSC Voting Members:** Representatives from contributing organizations and individual contributors, as defined in the Technical Charter

### Decision Making

The TSC aims to operate by consensus. When consensus cannot be reached, decisions are made by a majority vote of the TSC voting members present at a meeting where quorum is met.

- **Quorum:** A majority of TSC voting members must be present (in person or via electronic means) to conduct business.
- **Voting:** Each TSC voting member has one vote. Votes may be conducted during meetings or via electronic means (e.g., mailing list, GitHub) with a minimum voting period of 72 hours.
- **Lazy Consensus:** For routine matters, a proposal is considered approved if no TSC member objects within 72 hours of the proposal being posted to the TSC mailing list.

### Meetings

- The TSC holds regular meetings open to all community participants.
- All public meetings appear on the [Community Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/openan?view=week).
- Meeting schedules, agendas, and minutes are published on the [OpenAN wiki](https://lf-networking.atlassian.net/wiki).
- Meetings are announced on the [OpenAN mailing lists](https://lists.openan.dev).
- To request a new community meeting, email [support@lfnetworking.org](mailto:support@lfnetworking.org) with the meeting name, its committee, working group, or SIG (if any), the cadence, and the time including the time zone (UTC, PT, etc.).

## Adopter Advisory Committee (AAC)

The AAC provides advisory input to the TSC on topics including market requirements, use cases, and ecosystem engagement. The AAC does not have binding decision-making authority over the TSC's technical direction.

Details of the AAC composition and charter are defined in the Technical Charter.

## Roles

### Contributor

Anyone who contributes to the project (code, documentation, testing, issue reports, reviews, etc.). Contributors are expected to follow the [Contributing Guidelines](https://github.com/project-openan/.github/blob/main/CONTRIBUTING.md) and the [Code of Conduct](https://lfprojects.org/policies/code-of-conduct/).

### Triager

Contributors who have been granted Triage access to one or more repositories. Triagers help manage issues and pull requests for their component and represent the first rung of the contributor ladder. Triagers are members of their component's triagers team.

### Maintainer

Contributors who have been granted write access to one or more repositories. Maintainers are responsible for reviewing and merging contributions, maintaining code quality, and mentoring new contributors. Each repository lists its maintainers in its own MAINTAINERS.md file; the project-wide index and current TSC roster are in [MAINTAINERS.md](MAINTAINERS.md) alongside this document.

Maintainer status is granted by the TSC or by existing maintainers of a given repository, based on sustained, quality contributions.

### TSC Member

Individuals who serve on the Technical Steering Committee as defined by the Technical Charter and TSC composition rules.

## Repository Governance

Each component repository carries a MAINTAINERS.md (the public record of its maintainers) and a CODEOWNERS file (which routes pull request reviews to the component's maintainers team). Changes to these files are made by pull request, preserving a public audit trail of maintainership.

For the organizational repositories (`.github` and `governance`), the TSC owns and merges changes, and LF staff serve as the designated reviewers to provide a neutral review of organizational and governance changes before merge.

## Sub-Projects and Working Groups

The TSC may establish sub-projects and working groups to focus on specific technical areas. Each sub-project or working group operates under this governance framework and reports to the TSC.

## Elections

TSC elections are conducted as defined in the Technical Charter. The LFN staff facilitates the election process to ensure fairness and transparency.

## Amendments

Changes to this governance document require approval by a two-thirds majority of the TSC voting members.

## Reference

- [Technical Charter (PDF)](https://github.com/project-openan/governance/blob/main/OpenAN%20Technical%20Charter%2006-22-2026.pdf)
- [Maintainers](MAINTAINERS.md)
- [Contributing Guidelines](https://github.com/project-openan/.github/blob/main/CONTRIBUTING.md)
- [LF Projects Code of Conduct](https://lfprojects.org/policies/code-of-conduct/)
