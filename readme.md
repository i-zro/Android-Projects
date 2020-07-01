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
