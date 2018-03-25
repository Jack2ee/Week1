# Week1 - Git 기초

- Git 명령어

```shell
# 초기화
$ git init

# 유저 정보 확인
$ git config user.name
$ git config user.email

# 현재 디렉토리 상태 체크
$ git status

# 파일을 stage area 에 등록
$ git add [file]

# 현재 버전을 저장
$ git commit -m "이 버전을 설명하는 간단한 메시지"

# commit 한 기록들을 가져오기
$ git log

# 기존 commit에 비해 달라진 점 확인하기
$ git diff

# 이전 commit으로 되돌리기(옵션 : --hard / --soft / --mixed)
$ git reset --option [commit SHA-1]

# origin 이라는 변수에 웹 주소를 저장(사용의 편리성)
$ git remote add origin [주소]

# origin 이라는 GitHub Repository 의 master branch 에 현재 버전을 등록
$ git push origin master


```
