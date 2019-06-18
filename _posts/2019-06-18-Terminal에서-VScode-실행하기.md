---
title: "macOS Terminal에서 code명령으로 VScode 실행하기"

date: 2019-06-18

related: false

comments: true

read_time: false

categories:
  - VScode
tags:
  - VScode
  - Visual Studio Code
  - Terminal
---

터미널에서 작업 중 특정 위치에서 VScode를 열고 싶으면 `code` 명령어를 입력하면 된다

```bash
code
```

혹시 작동을 하지 않는 경우 아래와 같이 해결하자

1. VScode를 실행
2. 명령 팔레트를 실행 (⇧⌘P - cmd+shift+P)
3. Shell Command : install 'code' command in PATH 입력 후 선택 실행한다
   ![vscode shell-command](/assets/images/shell-command.png)

터미널을 재시작 하고 `code` 명령어를 입력하면 VScode가 실행된다.

---

참조

![vscode shell-command](/assets/images/shell-command1.png)

<https://code.visualstudio.com/docs/setup/mac>
