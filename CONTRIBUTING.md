# 기여 표준

## 폴더 이름

1. 레포지토리 최상 디렉토리의 폴더 이름은 `YYYYMMDD##`의 형식으로 한다.
   이때 `##`은 `01`부터 시작하는 폴더의 연번을 의미한다.

## 브랜치

1. 모든 수정사항은 `master` 브랜치 이외의 곳에서 작성한다.
   - 가령 파일 하나를 수정할 때에도 브랜치를 만들어 그곳에서 작업한다.
1. 모든 브랜치는 `--no-ff` 옵션을 적용하여 `master` 브랜치에 병합한다.
   - 이것은 각자 작업들을 하나로 묶어서, 한 주제로 작업된 커밋들을 한 번에 확인하는 데에 도움을 준다.
1. 브랜치 이름에서 띄어쓰기는 하이픈(`-`)으로 표시한다.

1. 가장 일반적인 브랜치 이름은 `test/`로 시작한다.
   - 예를 들어서 `README.md` 파일을 수정하는 브랜치의 이름은 `test/edit-readme`등과 같이 작성한다.
