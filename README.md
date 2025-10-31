1. VSCode 열기
2. Git Bash 열기
3. Repository 만들기
4. vscode terminal 열기!
5. vscode Terminal 에서 업로드할 폴더 경로가 잘 잡히는지 확인!!
6. ‘’’git —version’’’ 명령어로 git 설치 확인 및 버전 확인!

<aside>
💡

만약 오류 난다면!!

“C:\Program Files\Git\cmd”

경로 환경변수 설정 후 VSCode 재 실행 해보기!

</aside>

1. ‘’’git init’’’ 명령어로 git 초기화

          ㄴ> .git 이라는 폴더가 생성됨! 로컬 리포지토리

1. ‘’’git config —global [user.name](http://user.name) “깃헙닉네임” ’’’
2. ‘’’git config —global [user.email](http://user.email) “깃헙회원가입시기재한 이메일” ‘’’
3. ‘’’git remote add origin 깃헙리포지토리주소’’’

         ㄴ> 원격 깃헙 리포지토리와 로컬 리포지토리의 연결!

1. ‘’’git add .’’’ 🚨 띄어쓰기 주의!!
2. ‘’’git commit -m “커밋내용”
3. ‘’’git push origin 브랜치이름’’’ ← push 하기!
