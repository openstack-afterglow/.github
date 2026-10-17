<p align="center">
  <img src="https://raw.githubusercontent.com/openstack-afterglow/.github/main/profile/assets/afterglow-banner.svg" alt="Afterglow — Open clouds. Shared possibilities." width="100%">
</p>

<p align="center">
  <a href="https://cloud.dmslab.re.kr"><strong>Live deployment</strong></a> ·
  <a href="https://openstack-afterglow.github.io/openstack-afterglow/"><strong>Documentation</strong></a> ·
  <a href="https://github.com/openstack-afterglow/openstack-afterglow"><strong>Dashboard source</strong></a> ·
  <a href="#get-involved"><strong>Contribute</strong></a> ·
  <a href="#한국어"><strong>한국어</strong></a>
</p>

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
| Documentation & translation | Clarify setup steps, add examples, and improve Korean or English documentation. |
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

---

## 한국어

### OpenStack을 더 쉽게 사용하고, 함께 확장합니다

**OpenStack Afterglow는 OpenStack 대시보드와 다양한 부가 서비스를 만들고 관리하는 오픈소스 조직입니다.** 중심 프로젝트인 **Afterglow**는 Horizon과 Skyline을 대체할 수 있는 현대적인 대시보드를 목표로 합니다.

현재 [cloud.dmslab.re.kr](https://cloud.dmslab.re.kr)에서 DMS Cloud 콘솔로 운영 중이며, 실제 클라우드 운영과 연구 환경에서 얻은 경험을 바탕으로 개선하고 있습니다. 운영 서비스의 이용은 운영자의 계정·프로젝트 정책을 따릅니다.

**함께 만드는 프로젝트**

- **Afterglow** — OpenStack 자원 관리와 부가 서비스를 연결하는 통합 대시보드
- **Drover** — OpenStack 위의 K3s 클러스터·노드그룹 수명 주기 관리
- **Palimpsest** — VM 이미지·SquashFS 레이어·재사용 가능한 실행 환경
- **Lumen** — AI 채팅·에이전트 실행·도구·메모리·사용량 관리
- **Waygate** — 프로젝트별 WireGuard 게이트웨이와 클라이언트 설정 관리

### 누구나 기여할 수 있습니다

프론트엔드·백엔드 개발뿐 아니라 **UI/UX, 접근성, 테스트, 배포 문서, 번역, 버그 재현, 운영 경험 공유**도 환영합니다. 처음 기여하는 분도 참여할 수 있고, 조직에 가입하지 않아도 이슈와 PR을 제출할 수 있습니다.

1. 위 프로젝트 표에서 관심 있는 저장소를 고르고 README와 개발·아키텍처 지침을 확인합니다.
2. 기존 이슈와 PR을 살펴보고, 큰 변경은 먼저 이슈에서 방향을 논의합니다.
3. 저장소를 Fork하고 작은 단위로 수정한 뒤, 해당 저장소의 검사·테스트를 실행합니다.
4. 변경 이유와 검증 결과를 담아 PR을 제출합니다. UI 변경에는 화면을, 버그 수정에는 재현 절차를 함께 남겨주세요.

어디에 제안할지 고민된다면 [Afterglow 이슈](https://github.com/openstack-afterglow/openstack-afterglow/issues/new)에서 시작하세요. **한국어와 영어 모두 환영합니다.** 로그나 화면을 공유할 때는 인증정보와 사용자 데이터를 제거해주세요.

### OpenStack 생태계에 기여하는 프로젝트로

Afterglow에서 발견한 공통 문제를 재현 가능한 버그 보고·패치·테스트·문서로 정리하여 관련 OpenStack 프로젝트에 기여하는 것을 지향합니다. 업스트림 변경은 [OpenStack 공식 기여 가이드](https://docs.openstack.org/contributors/code-and-documentation/index.html)와 각 프로젝트의 절차를 따릅니다.

Afterglow는 독립적으로 개발되는 프로젝트이며, 공식 OpenStack 프로젝트 지정이나 승인을 받았다는 의미는 아닙니다.

<p align="center"><strong>Build with us. Operate with us. Improve OpenStack together.</strong></p>
