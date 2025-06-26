# TIL
Today I Learnd..

## .gitignore

[Website](https://gitignore.io)

‼️  github 관리

```shell
$ git add {file_name} > git add . 비추(commit 따로 관리)
$ git commit > -m "contents" 비추(실수할 가능성 높음)
$ git push origin main > git push 비추(여러개의 branch 사용할 경우 실수가능성)
```
> Conventional Commits
> 1. commit의 제목은 commit을 설명하는 문장형이 아닌 구나 절의 형태로 작성
> 2. importanceofcapitalize 'Importance of Capitalize'
> 3. prefix 꼭 달기
>     - feat: 기능 개발 관련
>     - fix: 오류 개선 혹은 버그 패치
>     - docs: 문서화 작업
>     - test: test 관련
>     - conf: 환경설정 관련
>     - build: 빌드 작업 관련
>     - ci: Continuous Intergration 관련
>     - chore: 패키지 매니저, 스크립트 등
>     - style: 코드 포매팅 관련
>
> ex) feat: Add Feature - Return sum of 2 numbers

‼️  branch

local = main

remote = origin/main

분기점을 생성하여 독립적으로 코드를 변경할 수 있도록

```shell
$ git branch {branch_name} : branch 생성
$ git switch {branch_name} : branch 변경
$ git branch -d {branch_name} : branch 삭제
$ git merge {branch_name} : branch 병합 (main branch 기준 $ git merge sub)
```

✅ branch에서 작업하던 code가 영 아니다 싶으면 그냥 branch 삭제하면 됨
