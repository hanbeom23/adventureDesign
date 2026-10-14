# adv-agents - AdvLab 강의용 에이전트 팀

역할별 Claude Code 서브에이전트 **11직군**으로 구성된 **AdvLab 가상 개발팀** 배포본입니다.
여러분의 프로젝트에 **추가**해, 작업을 직군에게 **파견(위임)**하며 협업하는 방식을 실습합니다.

## 빠른 시작 (사람 손이 거의 안 갑니다)

자세한 설치·사용법은 [`ONBOARDING.md`](ONBOARDING.md)를 따르세요. 요약하면:
1. 받은 `adv-agents.zip` **압축 풀기**
2. 내 프로젝트에서 **Claude Code 열기**
3. ONBOARDING의 **설치 프롬프트를 복사 → 경로만 바꿔 붙여넣기** → Claude가 에이전트 복사·CLAUDE.md 추가를 알아서 처리
4. Claude Code **재시작** → 파견 시작

> 여러분이 직접 파일을 옮길 필요가 없습니다. 프롬프트만 붙여넣으면 됩니다.
> 기존 파일을 덮어쓰지 않습니다 - 에이전트는 새 파일로 추가되고, 팀 지침은 기존 CLAUDE.md에 덧붙입니다.

## 팀 구성 (11 직군)

| 직군 (호출명) | 역할 |
|---|---|
| `advlab-architect` | 앱·도메인 아키텍트 (구조·모듈 경계·데이터 흐름) |
| `advlab-system-architect` | 시스템·인프라 아키텍트 (물리 구조·분산) |
| `advlab-backend` | 서버시스템 엔지니어 (API·데이터 계층) |
| `advlab-frontend` | UI·디자인시스템 엔지니어 |
| `advlab-mockup` | 목업 시안 디자이너 (HTML 시안) |
| `advlab-data-ml` | 데이터·ML 엔지니어 (파이프라인·검색/추천) |
| `advlab-platform` | 플랫폼·인프라 엔지니어 (배포·SRE·CI) |
| `advlab-qa` | QA 엔지니어 (테스트·품질 게이트·교차검증) |
| `advlab-security` | 보안·거버넌스 (위협 모델·정책) |
| `advlab-pm-int` | 내부 플랫폼 PM (요구 정리·직군 라우팅·조율) |
| `advlab-pmo-int` | 내부 플랫폼 PMO (표준·버전·의존 포트폴리오 조망) |

## 사용 조건

- **Claude Code** + **Claude 계정 로그인** 필요 (API 키 발급 불요 - 계정 로그인 방식).
- 에이전트의 `model:`은 `opus` 기준입니다. 계정 등급에 따라 사용 가능한 모델로 바꿔도 됩니다.
- 본 배포본은 **스냅샷**이며 자동 업데이트되지 않습니다.

## 실습 과제

[`samples/`](samples/) 폴더의 과제로 파견 흐름을 연습할 수 있습니다.
