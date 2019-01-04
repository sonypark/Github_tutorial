# hello git

## git 명령어 요약

- clone: 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 커밋(=save)
- push: 원격 저장소에 커밋 파일을 업로드

## 파일의 내용 되돌리기

- 특정 파일의 내용을 마지막 커밋으로 돌리고 싶을 때 해당 파일 선택 후 `코드 뭉치 버리기(Discard hunk)` 선택

## 브랜치 변경하기

- 브랜치란: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용한다.
- 체크아웃: 특정 브랜치(혹은 커밋)으로 돌아가고 싶을 때 사용.
- 소스트리의 체크아웃: 브랜치 이름을 더블클릭하면 체크아웃 가능.


## 병합하기
- 해드 브렌치에 변경사항이 없고
- 병합 대상 브렌치가 해드로부터 시자된 경우
- 아주 쉽게 병합 가능 = Fast-forward