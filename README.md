# 구대연 | Game QA Portfolio

게임의 규칙과 사용자 흐름을 이해하고, 재현 가능한 문서로 품질 문제를 설명하는 **Game QA / Software QA 지원자**입니다. 직접 개발한 게임과 웹 프로젝트를 테스트 대상으로 삼아 기능 구현, 오류 분석, 회귀 테스트 과정을 함께 기록하고 있습니다.

> 현재 핵심 프로젝트의 원본 코드와 결과 화면을 정리 중입니다. 검증된 자료부터 순차적으로 연결합니다.

## Featured Work

### ONE-TAP — Unity One-Touch Avoidance Game

한 번의 입력으로 위험을 피하는 Unity 기반 게임입니다. 게임플레이 구현뿐 아니라 WebGL 전환과 Firebase 랭킹 연동 과정에서 발생한 문제를 QA 사례로 정리합니다.

- 담당: 게임 시스템, 난이도 조정, WebGL 빌드, 랭킹 연동 이슈 분석
- 기술: Unity, C#, WebGL, Firebase
- QA 관점: 플랫폼 차이, 랭킹 저장/조회, 초기화 순서, 네트워크 실패, 회귀 테스트
- 상태: 저장소·실행 링크·증거 자료 정리 중

### Game QA Case Study

버그 리포트와 테스트 케이스를 재현 절차, Expected/Actual, Severity/Priority, Evidence, 원인 추정, Regression Test 형식으로 기록합니다.

- 첫 사례: ONE-TAP WebGL/Firebase 랭킹 이슈
- 포함 예정: 상태 전이, 입력 경계값, 저장/복구, 플랫폼 호환성 테스트
- 저장소: [game-qa-case-study](https://github.com/koody526/game-qa-case-study)

### NEON SYNC — Vanilla JS Smart Vending Machine

재고와 사용자 조건에 따라 구매 가능 상태가 달라지는 스마트 자판기입니다.

- 주요 기능: 재고 관리, 품절 처리, 인증 미니게임, 고카페인 제품 잠금, 입력 예외 처리
- 기술: HTML, CSS, Vanilla JavaScript
- QA 관점: 재고 경계값, 상태 동기화, 잠금 해제 조건, 연속/잘못된 입력
- 상태: 원본 코드와 배포 링크 확인 중

### Pygame Snake — Object-Oriented Game

객체지향 구조로 만든 Snake 게임입니다. 충돌과 방향 입력처럼 작은 규칙 차이가 플레이 결과에 미치는 영향을 테스트합니다.

- 주요 기능: 이동, 충돌 처리, 반대 방향 입력 제한, Apple 재배치 fallback, WIN 상태
- 기술: Python, Pygame
- QA 관점: 벽/자기 충돌, 빠른 연속 입력, 보드 포화, 승리 조건
- 상태: 원본 코드와 실행 화면 확인 중

## Additional Projects & Activities

| 프로젝트 | 초점 | 공개 방식 |
|---|---|---|
| Gemini HCI 재설계 | 사용성 분석과 인터페이스 개선 | 분석 근거·전후 비교 중심 사례 |
| CampusLedger | 사회혁신, AI·블록체인 아이디어 | 기획·검증·역할 중심 사례 |
| 학과 홍보영상 캡스톤 | 협업, 제작, 결과물 관리 | 저작권 확인 후 영상/과정 공개 |
| University Coursework | C 및 프로그래밍 기초 | 핵심 실습만 선별 통합 |

## QA Artifacts

제가 작성하는 QA 문서는 다음 질문에 답하도록 구성합니다.

1. 어떤 환경에서 어떤 절차로 다시 발생하는가?
2. 기대 결과와 실제 결과의 차이는 무엇인가?
3. 사용자와 서비스에 미치는 영향은 어느 정도인가?
4. 원인 가설을 어떤 증거로 좁혔는가?
5. 수정 뒤 무엇을 다시 확인해야 하는가?

## Skills

- Testing: Bug Reporting, Test Case Design, Exploratory Testing, Regression Testing
- Game/Web: Unity, C#, WebGL, Firebase, Vanilla JavaScript
- Programming: Python, Pygame, C
- Collaboration: Git, GitHub, 문서화

## Coursework Repositories

- [university-coursework](https://github.com/koody526/university-coursework) — 대표 수업 실습을 선별해 통합하는 저장소
- [25MultiProgramming1](https://github.com/koody526/25MultiProgramming1) — C 및 Notebook 수업 실습; 통합 정리 예정
- [25AI_C2](https://github.com/koody526/25AI_C2) — C 콘솔 애니메이션·포인터 실습; 통합 정리 예정

## Contact

- GitHub: [@koody526](https://github.com/koody526)

