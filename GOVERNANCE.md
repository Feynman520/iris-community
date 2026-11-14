# 운영 규칙 (Governance)

> **English summary.** IRIS Workspace is led by a single Maintainer, who makes the final decision on what goes into the official repositories and releases. Others take part as users (feedback), contributors (pull requests from forks), or — by invitation — module stewards for one module repository. Only the Maintainer merges into `main`, publishes releases, holds signing keys, and changes the shared database. Participation is unpaid, and no promise of money or ownership is valid unless it is in a document signed by the Maintainer.

이 문서는 IRIS Workspace에서 **누가 무엇을 결정하는지**를 적습니다.

**관리자(Maintainer) = [@Feynman520](https://github.com/Feynman520)** — 다른 문서의 '관리자'는 모두 이 줄을 가리킵니다.

## 1. 최종 결정

공식 저장소와 공식 배포판에 무엇을 넣을지는 관리자가 최종 결정합니다. 의견은 누구나 낼 수 있고, 관리자는 이유를 설명하려고 노력합니다.

## 2. 관리자만 하는 일

- `main`에 병합하기
- 새 판을 내고 서명하기, 안정판으로 올리기
- 서명 열쇠·비밀 값·배포 계정 관리
- 공용 데이터베이스(허브)의 표와 권한 바꾸기
- 새 모듈을 IRIS 창의 설치 목록(카탈로그)에 올리기
- 저장소 설정, 사람 초대와 권한 거두기
- 이름·로고(상표) 사용 허락

## 3. 역할

| 역할 | 누구 | 할 수 있는 것 | 할 수 없는 것 |
|---|---|---|---|
| 관리자 | 위에 적힌 한 사람 | 전부 | — |
| 모듈 담당 | 관리자가 초대한 사람. 모듈 저장소 하나 단위 | 그 저장소에 작업 가지 올리기 · PR · Issue 정리 · 남의 PR에 검토 의견 | `main`에 넣기 · 새 판 내기 · 저장소 설정 · 비밀 값 · 다른 저장소 |
| 기여자 | 누구나(기여 동의서 서명) | 자기 사본(포크)에서 고쳐 PR | 저장소에 직접 올리기 |
| 사용자 | 누구나 | Issue · 의견 보내기 | — |

- 모듈 담당은 '자리'입니다. 지금은 비어 있고, 맡을 사람이 생기면 한 명씩 초대합니다.
- 모듈 담당도 새 판을 직접 내지 않습니다. 출시를 요청하면 관리자가 검사한 뒤 냅니다.

### 모듈 담당으로 초대받는 조건

1. 그 모듈에 병합된 PR이 1건 이상 있다(관리자가 직접 아는 사람은 예외).
2. [기여 동의서](CLA.md)에 서명했다.
3. GitHub 2단계 인증을 켰다.
4. "무보수 · 지분 약속 없음 · 담당 범위는 이 저장소 하나"임을 글로 확인했다.

### 권한 거두기

6개월 동안 활동이 없으면 권한을 거둡니다. 원하면 다시 초대합니다. 행동 강령이나 이 문서를 어긴 경우에는 바로 거둘 수 있습니다.

## 4. 큰 변경은 먼저 이야기합니다

새 기능과 구조 변경은 Issue로 먼저 이야기합니다. 저장소마다 받는 것은 [CONTRIBUTING.md](CONTRIBUTING.md)의 표를 따릅니다.

## 5. 돈과 지분

- 참여는 무보수입니다.
- 기여했다고 해서 수익·지분·고용에 대한 권리가 생기지 않습니다.
- 돈이나 지분에 관한 약속은 **관리자가 서명한 문서**로만 효력이 있습니다. 대화·댓글·메신저에서 한 말은 약속이 아닙니다.

## 6. 이어받기와 법인

- 관리자가 프로젝트를 더 맡을 수 없게 되면, 관리자가 정한 사람이나 단체가 이어받습니다.
- 앞으로 법인을 세우면 관리자의 지위와 권리는 그 법인으로 옮길 수 있습니다. 기여 동의서도 이를 전제로 합니다.

## 7. 이 문서를 바꾸는 방법

이 저장소의 문서는 관리자만 바꿉니다. 고쳤으면 하는 점은 Issue로 알려 주세요.
