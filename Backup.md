# Git 코드 목록

## 위치
pwd: 현재 위치

ls: 폴더 내용보여줘. 리스트

ls -a: 숨긴파일까지 보여줘

cd 폴더: 폴더로 이동해줘. change directory.

~: 홈 디렉토리

.: `여기`

..:상위폴더 (나갈래)


## 생성/삭제
mkdir 폴더이름: make directory 폴더

rm -r 폴더이름: remove 폴더

touch 파일: 파일 생성

rm 파일: 파일 삭제

mv 파일 파일: `여기`

cp 파일 ./파일: `여기`

clear: 화면 정리


## git 상태
git --version: `여기`

git init: git 폴더로 권한부여 (.git 파일 생성)

git status: 상태확인 (변화여부)

git add 파일: 사진찍기 (staging area)

git commit -m "이름": 복구파일 생성

git config --global user.name '이름': 처음 git 생성할때 이름

git config --global user.email '이메일': 처음 git 생성할때 이메일

git log: 업데이트 내용에 대한 로그

git checkout 코드 : `여기` (master) 에서 코드로 변환됨.

git checkout master : `여기` 마스터로 전환

cat: `여기` 해보니까 빠져나와지지 않음. 메아리침.

cat config: `여기`

cat description: `여기`

code. : Visual Studio Code 실행

git diff 파일 : `여기`

git remote: 버전출력

git remote 저장소별명 저장소주소

git remote add origin 사이트 : 분산 사이트에 저장 (e.g. github)

git remote -v : 연결되있는 모든 분산 데이터 repos. verbose (말이많은). 상세하게 출력

git push: 원격저장소에 코드 백업

git push [저장소별명] [브랜치이름]:

git remote remove origin: 기존의 저장소와의 연결 끊기 



> cf) 특이사항 발생시 
:!q : 이상한 곳 탈출
q: 탈출

ctrl c/ ctrl v: `여기`
ctrl ins/shift ins : 복사 붙여넣기

## 순서
mkdir recap
git init
touch hello.md
code.
git add hello.md
git commit -m 'hello.md'
git status


## 궁금한 코드
1. 실행한 코드 취소


## 참조사항
1. `여기` 라는 작성자가 공부하려고 체크한 부분