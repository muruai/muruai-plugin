# 무루아이 플러그인

Claude Code·Codex에서 말로 요청해 [무루아이](https://muruai.com) 자료를 찾고, 고치고, 만들 수 있게 하는 플러그인입니다.

- 자료 찾기·보기, 글씨·색·쪽 고치기, PDF 받기, 되돌리기
- 이야기책·학습지 만들기, 그림 고치기·다시 그리기(크레딧이 드는 작업은 할 일과 크레딧을 먼저 보여 주고 확인을 받은 뒤 시작)
- 그림 은행 그림 넣기, 내 그림 올리기, 기존 자료를 틀로 새 자료 만들기

플러그인에는 선생님 자료가 들어 있지 않습니다. 무엇을 보고 바꿀 수 있는지는 로그인한 무루아이 계정이 정합니다.

## 설치

무루아이 웹 **계정 설정 > AI 도구 연결**에서 설정 문장을 복사해 AI 도구에 붙여 넣으면 AI 도구가 설치합니다. 실행 허용을 물으면 허용해 주세요.

직접 설치할 때는 아래 명령을 차례로 실행합니다.

Claude Code

```
claude plugin marketplace add muruai/muruai-plugin
claude plugin install muruai@muruai
```

Codex

```
codex plugin marketplace add muruai/muruai-plugin
codex plugin add muruai@muruai
```

## 로그인

설치가 끝나면 새 대화를 열고 `/mcp`에서 `muruai`를 골라 무루아이 계정으로 로그인합니다. Codex는 `codex mcp login muruai`로도 됩니다.

## 연결 끊기

무루아이 웹 **계정 설정 > AI 도구 연결**에서 언제든 끊을 수 있습니다.
