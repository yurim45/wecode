# git 명령어

### git 초기 셋팅

#### `git init`

- 새로운 폴더를 만들고, git 추적 실행하기 위한 명령어
- 명령어는 항상 그 폴더에서 실행
- 추적 삭제 필요시 `.git` 폴더 삭제

---

### github에 올리기

#### `git remote add origin 저장하려는 주소`

- 올리고자 하는 주소를 지정

#### `git add .`

- 현재 작업한 내용을 임시 저장

#### `git commit -m "설명"`

- 임시 저장한 내용에 대한 설명 작성 후 commit

#### `git push origin 위치`

- remote에 최종 올리는 명령어
- `git push origin master` 또는
- `git push origin 브랜치명`

---

### branch 만들기

- `git branch branch명` branch 생성하기
- `git checkout branch명` 현재 위치에서 나가서 branch명으로 이동
