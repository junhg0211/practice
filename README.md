# practice

> 여러가지 git 연습을 위한 레포지토리

이 레포지토리에는 별 요상한 코드를 다 정리하지 않고 적겠습니다.

## 지금까지 해본 신기한 짓

### 깃 레포지토리 안에다가 깃 레포지토리 만들기

서로 따로 작동한다. `.git` 디렉토리는 무시되는 듯

### PR 만들고 다시 커밋하기

그냥 PR이 갱신된다.

### 한번에 2개 이상의 커밋 머지하기

`git/git` 레포를 뜯어보면서 한 번에 2개 이상의 브랜치를 머지하는 기상천외한 현상을 발견함.
직접 시도해봤는데 됨.

지금까지 merge에는 빨리감기, 병합, 충돌의 3가지 경우만 있는 줄 알았는데,
octopus merge라는 새로운 전략이 있는 것으로 보임. 이걸 그런 경우로 봐야하는지 아직 잘 모르겠지만...
아무튼 신기함!

### PR에서 충돌 발생하기

A 브랜치에 B 브랜치를 커밋하는 PR에서 충돌이 발생하면 A를 B에 merge하여 충돌을 해결한 다음에 머지한다.

GitHub 페이지에는 이 conflict resolve를 도와주는 웹에디터가 있어서 직접 코드를 클론하지 않아도
충돌을 해결할 수 있도록 해준다.

### `git add`를 사용해서 파일의 일부분만 stage하기

`git add -p <filename ...>` 또는 `git add --patch <filename ...>`를 사용해서
파일의 일부분만 스테이지에 추가하는 것이 가능하다.
