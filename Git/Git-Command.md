# Git 명령어

### 1. `config` 
- 설정: git에게 내가 누군지 알려주기(한번만)

``` bash
 git config --global user.email "you@example.com"
 git config --global user.name "Your Name"
 git config --global --list
```
---
### 2. `git init`
- git 으로 관리 시작 -> 디렉토리당 한번만
주의! 홈폴더나 바탕화면 x
---
### 3. `git status`
- 파일 상태 확인(중요!)
---
### 4. `git add` 파일명
- 무대 위로 올리기
---
### 5. `git commit -m` "커밋 사유"
- 변경사항을 기록. 즉, 사진 찍기
- (vim 빠져 나오는 것 esc + :q )
---
### 6. `git log`
- 커밋의 내역 확인
- 한줄로 확인시`git log --oneline`
---
### 7. `git diff` 해쉬값 해쉬값
- 커밋들을 비교하기
---
### 8. 
```bash
git remote add origin URL
git remote -v1
```
- github와 연결
---
### 9. `git remote rm origin`
- origin 삭제
---

### 10. `git push origin master`
  - github에 local commits 올리기
---