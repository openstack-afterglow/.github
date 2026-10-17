<p align="center">
  <img src="https://raw.githubusercontent.com/openstack-afterglow/.github/main/profile/assets/afterglow-banner.svg" alt="Afterglow — Open clouds. Shared possibilities." width="100%">
</p>

<p align="center">
  <a href="https://cloud.dmslab.re.kr"><strong>Live deployment</strong></a> ·
  <a href="https://openstack-afterglow.github.io/openstack-afterglow/"><strong>Documentation</strong></a> ·
  <a href="https://github.com/openstack-afterglow/openstack-afterglow"><strong>Dashboard source</strong></a> ·
  <a href="#get-involved"><strong>Contribute</strong></a> ·
  <a href="https://github.com/openstack-afterglow/.github/blob/main/profile/README.ko.md"><strong>한국어</strong></a>
</p>

[English](https://github.com/openstack-afterglow/.github/blob/main/profile/README.md) · [한국어](https://github.com/openstack-afterglow/.github/blob/main/profile/README.ko.md) · [日本語](https://github.com/openstack-afterglow/.github/blob/main/profile/README.ja.md) · [简体中文](https://github.com/openstack-afterglow/.github/blob/main/profile/README.zh-CN.md) · [Español](https://github.com/openstack-afterglow/.github/blob/main/profile/README.es.md)

# A new experience for OpenStack

**Afterglow is an open-source organization building an OpenStack dashboard and the services around it.** Our core project, **Afterglow**, aims to become an alternative to Horizon and Skyline: a modern, unified interface for cloud users and operators.

We build from real operational needs. Afterglow is deployed at **[cloud.dmslab.re.kr](https://cloud.dmslab.re.kr)** as the DMS Cloud console, bringing infrastructure management, Kubernetes, reusable environments, and AI services into one experience. Access to the running service follows the operator's account and project policies.

We welcome developers, OpenStack operators, researchers, designers, technical writers, and first-time contributors. You do not need to contribute code to make a difference.

## What we are building

| Project | Focus | Start here |
| --- | --- | --- |
| **[Afterglow](https://github.com/openstack-afterglow/openstack-afterglow)** | The core dashboard: SvelteKit UI and FastAPI gateway for OpenStack resource management and integrated services. | [README](https://github.com/openstack-afterglow/openstack-afterglow#readme) · [Issues](https://github.com/openstack-afterglow/openstack-afterglow/issues) |
| **[Drover](https://github.com/openstack-afterglow/drover)** | K3s cluster and node-group lifecycle management on OpenStack. | [README](https://github.com/openstack-afterglow/drover#readme) · [Issues](https://github.com/openstack-afterglow/drover/issues) |
| **[Palimpsest](https://github.com/openstack-afterglow/palimpsest)** | Reusable VM environments, SquashFS layers, boot images, and local layered VM workflows. | [README](https://github.com/openstack-afterglow/palimpsest#readme) · [Issues](https://github.com/openstack-afterglow/palimpsest/issues) |
| **[Lumen](https://github.com/openstack-afterglow/lumen)** | AI chat and agent execution, provider routing, tools, memory, and usage tracking. | [README](https://github.com/openstack-afterglow/lumen#readme) · [Issues](https://github.com/openstack-afterglow/lumen/issues) |
| **[Waygate](https://github.com/openstack-afterglow/waygate)** | Project-scoped WireGuard gateway lifecycle and client configuration for OpenStack. | [README](https://github.com/openstack-afterglow/waygate#readme) · [Issues](https://github.com/openstack-afterglow/waygate/issues) |

Each repository documents its own setup, supported environments, release status, and license. The table describes project scope; deployment and maturity can differ by component.

## Why Afterglow?

- **A clearer cloud experience.** Make compute, images, networks, volumes, shares, and load balancers easier to discover and manage.
- **Services that work together.** Connect Kubernetes provisioning, reusable runtime environments, AI capabilities, and project connectivity through a common dashboard.
- **Feedback from real operations.** Turn day-to-day cloud usage into better workflows, documentation, and reproducible fixes.
- **Room for more contributors.** Build a community across frontend, backend, infrastructure, design, testing, and documentation.

## Get involved

**Start small: try a workflow, improve a page, reproduce a bug, or review a change.**

| Your interest | Useful first contributions |
| --- | --- |
| Frontend & UX | Improve SvelteKit screens, accessibility, resource tables, error states, and user journeys. |
| Backend & OpenStack | Improve API integrations, permissions, resource lifecycle handling, and failure recovery. |
| Infrastructure & testing | Document deployments, reproduce compatibility issues, and improve automated checks. |
| Documentation & translation | Clarify setup steps, add examples, and improve translations. |
| Cloud operations & research | Share reproducible use cases, usability feedback, and operational lessons without credentials or tenant data. |

### Your first contribution

1. **Choose a repository** above and read its README, architecture notes, and any contribution or agent instructions.
2. **Check existing issues and pull requests.** For a larger feature or behavior change, open an issue first to discuss the problem and scope. If you are unsure where a cross-project idea belongs, [start with an Afterglow issue](https://github.com/openstack-afterglow/openstack-afterglow/issues/new).
3. **Fork the repository and create a focused branch.** Follow that repository's development setup; the dashboard's local stack has sibling-service and OpenStack configuration requirements.
4. **Make one clear change.** Run the relevant documented checks. Include tests for behavior changes and update affected documentation.
5. **Open a pull request** explaining the problem, the change, and how you verified it. For UI changes, include screenshots; for bugs, include sanitized reproduction steps.

**Bug reports:** include the component, version or commit, environment, expected and actual behavior, and a minimal reproduction. Remove secrets, tokens, private addresses, and user data from logs and screenshots.

**Questions and ideas:** use the relevant repository's Issues. Korean and English are both welcome. You can contribute through issues and pull requests without joining the organization first.

## Giving back to OpenStack

Our goal is to turn experience building and operating Afterglow into useful contributions to the wider OpenStack ecosystem:

- Report reproducible upstream bugs with clear environment details and minimal examples.
- Propose broadly useful fixes, tests, and documentation to the relevant OpenStack projects.
- Discuss API compatibility and integration needs with upstream maintainers before creating project-specific workarounds.
- Share operational lessons and user-experience feedback that can help other clouds.

Afterglow changes are proposed through this organization's GitHub repositories. Changes to upstream OpenStack projects follow the **[official OpenStack contributor guide](https://docs.openstack.org/contributors/code-and-documentation/index.html)** and the target project's contribution process, including Gerrit review where applicable.

**Afterglow is independently developed for the OpenStack ecosystem. This page does not claim official OpenStack project status, endorsement, or upstream acceptance.** Upstream contribution is a direction we want to pursue together.


## Languages

[English](https://github.com/openstack-afterglow/.github/blob/main/profile/README.md) · [한국어](https://github.com/openstack-afterglow/.github/blob/main/profile/README.ko.md) · [日本語](https://github.com/openstack-afterglow/.github/blob/main/profile/README.ja.md) · [简体中文](https://github.com/openstack-afterglow/.github/blob/main/profile/README.zh-CN.md) · [Español](https://github.com/openstack-afterglow/.github/blob/main/profile/README.es.md)

These pages introduce the organization; individual projects document their own language support. English is the reference for this profile. Translation fixes and additional languages are welcome through pull requests. When changing shared information, update the translated introductions too.
