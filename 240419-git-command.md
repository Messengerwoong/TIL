# git command 명령어 작성 

git config --global user.name “{username}”
Git에 사용자 이름을 설정
git config --global user.email “{emailaddr}”
Git에 사용자 이메일 주소를 설정
git config --global core.editor “vim”
Git에서 기본적으로 사용할 편집기를 Vim으로 설정
git config --global core.pager “cat”
Git에서 출력을 보여줄 때 사용할 페이저를 설정
git config --list
git config --list 명령어는 현재 Git 설정을 리스트로 출력
vi ~/.gitconfig
파일을 열어서 설정을 확인하고 변경

# how to start 
vi README.md 
README.md 파일을 vi로 수정한다
git status
git의 상태를 파악한다.
git add README.md
git을 commit준비상태로 바꾼다. 
git push origin main 
깃을 저장소에 push한다. 

