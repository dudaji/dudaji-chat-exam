# dudaji-chat-exam

- 현재 아주 간단하게 동작하는 chatting 코드가 있습니다.
- 해당 코드는 동작하지만 개선해야할 부분이 많이 있습니다.
- 아래 이슈를 해결 부탁드립니다.

## Issues

- requirements.txt를 통해서 package가 관리되게 해주세요.
- .gitignore를 등록해주세요.
- lint를 적용해주세요.
- print를 logging library로 변경해주시고, 좋은 포멧터를 적용한 뒤, 파일에도 로그가 남게 해주세요.
- packet protocol을 json 혹은 protobuf로 변경해주세요.
- recv / send를 포함하여 리팩토링을 진행하고, 불안정한 코드를 튼튼하게 수정해주세요. (hint: command pattern 적용 등)
    - https://github.com/dudaji/dudaji-chat-exam/blob/main/client.py#L17
    - https://github.com/dudaji/dudaji-chat-exam/blob/main/server.py#L44
    - https://github.com/dudaji/dudaji-chat-exam/blob/main/server.py#L12

- 각종 매직넘버를 config를 통해서 관리하도록 해주세요.
- README.md파일에 Quick start 문서를 작성해주세요.
- 기타 개선하고 싶은 부분을 자유롭게 개선해주세요.

## 제출 방법

1. git clone

```sh
git clone --depth=1 https://github.com/dudaji/dudaji-chat-exam.git
```

2. 이슈를 해결해나가면서 변경한 내용을 commit 해주세요.  

```sh
git add --all
git clone -m "Add .gitignore"
```

3. 완료 후 git bundle 된 파일을 이메일로 보내주세요.  

```sh
git bundle create dudaji-chat-exam.bundle --all
```

제출 이메일 주소: help-zoom-aaaaiilxjmgygtxnvjywr6lh3e@dudaji.slack.com
