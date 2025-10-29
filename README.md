# 😺 깃허브 사용법


## 1. SSH 키 등록 📀

 1. 윈도우 터미널 열기
 2. `ssh-keygen` 명령어 입력 후 Enter 3번 누르기
 3. `cd .ssh` 명령어 입력
 4. `ls` 또는 `dir` 명령어 입력해 `.pub`으로 끝나는 파일 열어서 안에 있는 내용 전부 복사해두기
 5. Github 설정 -> SSH and GPG key 세션 -> New SSH Key -> 이름 입력 후 내용에 `4`번에서 복사해둔 내용 붙여넣기 -> 저장

## 2. Git 설정하기 🌐
  1. ```bash
     $ git config --global user.name "Your Name"         // 사용자 이름
     $ git config --global user.email "you@example.com"  // 사용자 이메일 주소
     ```
     명령어로 사용자 설정

## 3. Git으로 업로드하기

  1. 깃허브 리포지토리 ( 저장소 )에 올리고 싶은 프로젝트 폴더에 터미널(또는 Git bash)열기
  2. `git init`명령어 입력
  3.  `git add .` 로 모든 파일 추가하기
  4. `git commit -m "커밋 메세지"`로 커밋하기
  5. `git branch -M main`으로 브랜치 변경하기
  6. `git remote add origin git@github.com:JBNU-HS-CODE/프로젝트이름.git`으로 리포지토리 연결하기
  7. `git push -u origin main`으로 업로드하기
