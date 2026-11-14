# 기여 안내 (Contributing)

> **English summary.** Thank you for your interest in IRIS Workspace. Issues and pull requests are welcome in Korean or English. Each repository accepts different kinds of changes — see the table in section 0 before you start. Core repositories (the IRIS window, the installer, the messenger, the homepage, the hub) accept feedback and small fixes only; tool repositories (document MCP servers, self-improve) accept feature pull requests from forks. Pull requests that port the core to another operating system are not accepted at this time. Every pull request needs a signed [CLA](CLA.md) and is merged only by the Maintainer. Report security problems privately — see [SECURITY.md](SECURITY.md).

IRIS Workspace에 관심을 가져 주셔서 고맙습니다. 의견(Issue)과 코드(PR, 병합 요청)는 한국어와 영어 모두 받습니다.

## 0. 먼저 볼 것 — 저장소마다 받는 것이 다릅니다

| 묶음 | 저장소 | 받는 것 | 받지 않는 것 |
|---|---|---|---|
| 본체 | `d06-p02-iris-face`(IRIS 창) · `d09-p03-iris-installer`(설치 패키지) | 의견(Issue) · **작은 고침 PR** | 기능을 바꾸거나 더하는 PR |
| 선택 모듈 | `d06-p04-iris-messenger`(메신저) | 의견(Issue) · **작은 고침 PR** | 기능을 바꾸거나 더하는 PR |
| 운영 | `d09-p05-iris-homepage`(홈페이지) · `d09-p08-iris-hub`(허브) · `iris-community`(이 문서가 있는 곳) | 의견(Issue) · **작은 고침 PR** | 기능을 바꾸거나 더하는 PR |
| 도구 | 문서 자동화 MCP 5개(`d01-p01` ~ `d01-p05`) · `d06-p01-self-improve` | 의견(Issue) · **기능을 포함한 PR**(자기 사본에서) | — |

- **작은 고침**이란 오타, 문서, 번역, 그리고 기능을 바꾸지 않는 명백한 버그 수정을 말합니다.
- **번역과 문서 PR은 크기와 상관없이 어느 저장소든 환영합니다.**
- 본체·선택 모듈·운영 저장소에 기능을 바꾸는 PR이 오면 닫고, 의견(Issue)으로 남겨 달라고 안내합니다. 본체는 모든 사용자의 PC에 깔리는 바탕이라 관리자가 직접 만듭니다.
- **본체를 다른 운영체제로 통째로 옮기는 PR은 지금 받지 않습니다.** 판이 둘로 갈리면 서로 어긋나기 쉽기 때문입니다. 계획이 바뀌면 이 문서에 적겠습니다.
- 담당자를 둔 모듈 저장소가 생기면 이 표에 줄을 더합니다. 지금은 없습니다.

## 1. 시작하기 전에

- 작은 수정은 바로 PR을 내셔도 됩니다.
- 큰 변경(새 기능, 구조 변경, 여러 파일에 걸친 수정)은 **Issue를 먼저** 열어 방향을 이야기해 주세요. 미리 이야기하지 않은 큰 PR은 받지 못할 수 있습니다.

## 2. 작업 순서

1. 저장소를 자기 계정으로 복사(포크)합니다.
2. 작업용 가지(branch)를 만들어 고칩니다.
3. 커밋 제목은 `fix:`(고침) · `docs:`(문서) · `feat:`(기능) 가운데 하나로 시작합니다.
4. PR을 열고 양식의 물음에 답합니다.

관리자가 초대한 모듈 담당은 포크 대신 그 저장소 안의 작업 가지에 올리고 PR을 냅니다. 어느 경우든 `main`에 넣는 것은 관리자만 합니다.

## 3. 두 겹 검사

| 겹 | 어디서 | 무엇을 |
|---|---|---|
| 기여자 겹 | GitHub 서버(자동 검사가 있는 저장소) 또는 내 PC | 빠른 검사 — 각 저장소 README의 시험 명령 |
| 관리자 겹 | 관리자 PC | 전체 검사 — 실제 설치·로그인·업데이트까지 |

두 겹을 모두 통과한 변경만 `main`에 들어갑니다. PR을 내기 전에 그 저장소 README에 적힌 시험 명령을 돌려 주세요.

## 4. 새 기능은 본체 밖에서

새 기능은 되도록 본체가 아니라 **꽂았다 뺄 수 있는 형태**로 만듭니다.

| 물음 | 예 → |
|---|---|
| 모든 사용자에게 반드시 있어야 하나? | 본체 (관리자가 만듦) |
| 따로 꽂고 뺄 수 있는 화면 기능인가? | 모듈 |
| 에이전트가 일하다 부르는 능력인가? | MCP(코드가 실행됨) 또는 스킬(글로 된 절차) |

어디에 해당하는지 모르겠으면 Issue로 물어 주세요.

## 5. 넣으면 안 되는 것

- 학생·학부모·교직원의 개인정보
- 비밀 열쇠, 토큰, 비밀번호
- 연락처(전화번호·이메일·주소)
- 기기 이름, 사용자 계정 이름이 든 경로
- 특정 학교·기관의 내부 정보

시험 자료가 필요하면 지어낸 값만 씁니다(예: `iris@example.com`).

## 6. AI가 쓴 코드

AI 도구로 만든 코드도 받습니다. 다만 **책임은 PR을 낸 사람에게 있습니다.** 내용을 이해하고, 직접 돌려 보고, 남의 코드를 베끼지 않았는지 확인한 뒤 내 주세요.

## 7. 보안 문제

보안 문제는 Issue에 쓰지 말고 **비공개로** 알려 주세요. 방법은 [SECURITY.md](SECURITY.md)에 있습니다.

## 8. 기여 동의서(CLA)

처음 PR을 내면 봇이 [기여 동의서](CLA.md)에 서명해 달라고 요청합니다. 한 번만 하면 됩니다. 오타 한 글자를 고치는 PR에도 필요합니다. 서명하기 전에는 병합할 수 없습니다.

## 9. 의견은 자유롭게 반영됩니다

Issue·토론·의견함에 남긴 의견과 아이디어는 관리자가 자유롭게 제품에 반영할 수 있으며, 이에 대한 보상이나 이름 표시의 의무는 없습니다. 이 점을 알고 의견을 남겨 주세요.

## 10. GitHub 계정이 없다면

- 홈페이지 의견함: <https://iris-workspace.com/feedback>
- IRIS 창의 설정 → 「의견 보내기」

## 더 읽을 것

- [GOVERNANCE.md](GOVERNANCE.md) — 누가 무엇을 결정하나
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) — 행동 강령
- [TRADEMARKS.md](TRADEMARKS.md) — 이름과 로고
