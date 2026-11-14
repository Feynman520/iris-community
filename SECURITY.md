# 보안 정책 (Security Policy)

> **English summary.** Please report security vulnerabilities privately: open the affected repository, go to the **Security** tab, and choose **Report a vulnerability**. Do not post details in a public issue. There is no email address for reports. This project is run by one person, so there is no guaranteed response time, but reports are read and handled as quickly as possible.

## 알리는 방법

보안 문제를 찾았다면 **공개 Issue에 쓰지 말고 비공개로** 알려 주세요.

1. 문제가 있는 저장소를 엽니다.
2. 위쪽 **Security** 탭을 누릅니다.
3. **Report a vulnerability**를 눌러 내용을 적습니다.

이렇게 쓴 글은 신고한 분과 관리자만 볼 수 있고, 고쳐질 때까지 공개되지 않습니다.

- 이메일 신고 창구는 두지 않습니다.
- 어느 저장소의 문제인지 모르겠으면 IRIS 창 저장소(`d06-p02-iris-face`)에 알려 주세요.

## 적어 주면 좋은 것

- 어떤 판에서 생기는지(IRIS 창 판, 설치 패키지 판)
- 무엇을 하면 문제가 생기는지(따라 할 수 있는 순서)
- 생길 수 있는 피해
- 개인정보나 실제 비밀 값은 넣지 마세요. 지어낸 값으로 설명해 주세요.

## 그다음 일어나는 일

- 이 프로젝트는 한 사람이 운영합니다. 답하는 기한을 약속하지는 못하지만, 받은 신고는 모두 읽고 되도록 빨리 다룹니다.
- 고친 판을 낸 뒤에 내용을 공개합니다. 원하시면 신고한 분의 이름을 함께 적습니다.

## 범위

| 대상 | 알릴 저장소 |
|---|---|
| IRIS 창 | `d06-p02-iris-face` |
| 설치 패키지, 업데이트 | `d09-p03-iris-installer` |
| 메신저 모듈 | `d06-p04-iris-messenger` |
| 허브 서버(데이터베이스 정의·권한 정책) | `d09-p08-iris-hub` |
| 홈페이지 | `d09-p05-iris-homepage` |
| 문서 자동화 MCP, self-improve | 해당 저장소 |

범위 밖: 사용자가 직접 고친 판에서만 생기는 문제, 사용자가 직접 세운 서버의 운영 실수.

## 서명

공식 배포 파일은 서명되어 있고, IRIS 창은 공식 서명이 없는 모듈 파일을 설치하지 않습니다. 서명 열쇠는 관리자만 가지고 있으며 어느 저장소에도 들어 있지 않습니다. 서명이 맞지 않는 공식 파일을 보셨다면 위 방법으로 알려 주세요.
