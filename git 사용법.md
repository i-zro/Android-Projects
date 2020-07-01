## 얄팍한 코딩사전

: https://www.youtube.com/watch?v=FXDjmsiv8fI

# 깃허브

---

언제든 시간여행 가능한 평행 우주를 만들어 주는 것

---

# vs-code 터미널 열기

---

Ctrl + `

1. git init : 빈 git 저장소가 만들어짐
1. git config --global user.name "i-zro" : 내이름 등록
1. git config --global user.email "dek3127@gmail.com" : 내 이메일 등록
1. git status : 현재 폴더 안의 파일 상태. untracked file이라고 git에서 아직 쳐다보지 않는 파일이 나타남
1. git add : 파일을 타임캡슐에 묻겠다
   git add -A :모든 파일을 타임캡슐에 묻겠다
1. git commit -m "First Commit" : commit 내용 적기

---

# 임의로 쓰레기 파일 만든 후, 쓰레기 파일 만든 전으로 돌아가기

---

1. 쓰레기 파일을 만들어줌
1. git add -A 해줌
1. git log : commit 일련번호가 나옴 --> 앞 여섯자리만 복사 (ex) 26bd27)
1. git reset 26bd27 --hard : 26bd27 상태로 돌아감,현재 로그 사라짐
1. git revert 26bd27 : 좀 더 소심하게, 현재 로그 남아있는 상태

---

# 평행우주 만들기

---

1. git branch my-idea : my-idea라는 branch 만들어주기
1. git checkout my-idea : my-idea라는 branch로 옮겨오기
1. 쓰레기파일 한개 삭제하고 새로운거 한개 만들어놓기
1. add, commit 해주기
1. git checkout master : 감쪽같이 원래대로 돌아옴

---

# my-idea 브랜치를 master와 병합하기

---

git merge my-idea

---

# 브랜치 작업 내용 시각화

---

git log --graph --all --decorate
git branch -D my-idea : 다쓴 브랜치 삭제

---
