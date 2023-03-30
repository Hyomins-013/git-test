## Git Command

- `git init` : 이미 작업하던 파일에 선언하게 되면 그때부터 git의 버전관리를 받을 수 있게된다.
- `git remote add origin <remote repository url>` : <remote repository url> : 의 저장소를 origin이라는 이름으로 불러서 관리 하고 싶을 때 쓴다.
- `git add <file name>` : 변경 사항이 있는 파일 중에 을 선언해서 저장소에 보낼 준비를 할 수 있다. git add . 을 선언하게 되면 변경사항이 있는 모든 파일을 저장소에 보낼 준비를 한다.
- `git commit` : 해당 명령어에 -m 을 달고 " " 안에 짧은 메시지를 남길수 있다. 보통 무언가를 구현하거나 수정하거나 리팩토링을 완료 했을 때 커밋을 남기며 커밋 마다 해쉬코드가 존재해 돌이킬수 없는 실수를 저지르면 돌아 갈 수 있다. 명령어에 -m 없이 선언하면 에디터 창이 나오고 여러줄의 커밋을 남길수 있다.
- `git push origin <branch name>` : 만든 branch 이름의 PR에 그동안 add, commit 했던 내용을 원격저장소에 저장할 수 있다.
- `git pull origin <branch name>` : 해당 파일에 없는 다른 branch에서 작업하던 코드들을 현재 브런치로 가져올 수 있다.
- `git merge <branch name>` : 현재 HEAD 가 향한 브랜치에 언급한 브랜치를 합친다.
