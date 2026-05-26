# Security Policy — DEXignation Organization / 조직 보안 정책

This is the **organization-wide** security policy. Individual
repositories may also publish their own `SECURITY.md` with
repository-specific details.

본 문서는 **조직 차원**의 보안 정책입니다. 개별 저장소는 자체
`SECURITY.md`로 저장소별 세부 사항을 추가할 수 있습니다.

---

## Reporting a Vulnerability / 취약점 제보

**Please do not open public GitHub issues for security vulnerabilities.**

**보안 취약점은 공개 GitHub 이슈로 올리지 마십시오.**

Contact us privately at:

비공개로 다음 경로로 연락해주세요:

- **Email**: `security@dexignation.io`
- **Website**: https://dexignation.com
- **PGP key fingerprint**: published in the website footer

We aim to acknowledge reports within **48 hours** and to issue an
initial triage within **5 business days**.

48시간 내 수신 확인, 5영업일 내 1차 분석 결과 회신을 목표로 합니다.

---

## Scope / 범위

### In scope / 범위 내

- All code in repositories under the
  [DEXignation](https://github.com/DEXignation) organization
- Production-relevant deployment scripts and configuration
- Documentation that could lead users to lose funds (e.g. incorrect
  integration examples)

### Out of scope / 범위 외

- Test contracts and mocks (`contracts/mocks/`)
- Issues requiring social engineering or physical access
- Theoretical attacks without a feasible exploitation path
- Third-party code we depend on (report upstream)

---

## Disclosure Policy / 공개 정책

We follow **coordinated disclosure**:

- Reporter and DEXignation agree on a fix and a public-disclosure date.
- DEXignation deploys the fix and verifies no funds are at risk.
- A post-mortem is published, with credit to the reporter (unless they
  prefer to remain anonymous).

**조율된 공개**를 원칙으로 합니다. 수정 후 포스트모템을 공개하며 제보자에게
공로를 표기합니다(익명 원할 경우 익명 처리).

---

## Bug Bounty / 버그 바운티

A formal bug bounty program will be announced after the first
independent audit. Until then, we evaluate severe findings on a
case-by-case basis and will recognise meaningful contributions.

최초 독립 감사 후 정식 바운티 프로그램을 공개합니다. 그 이전 단계에서도
중대한 발견은 개별 평가하여 의미 있는 기여로 인정합니다.
