# Git

- 기본 master branch 'master'
- 기본 원격 branch 'origin'
- git remote를 입력하면 원격 저장소가 있는 지 확인 가능
- git fetch 후 git status로 원격 저장소 최신 상태 확인 가능
- git branch "브랜치명" : 브랜치 만들기
- git checkout "브랜치명" : 브랜치 이동하기
- git checkout -b "브랜치명" : 브랜치 만들고, 만든 브랜치로 바로 이동하기
- git branch -a : 원격과 로컬에 있는 브랜치를 모두 볼 수 있다
- git checkout -b "브랜치명" origin/"브랜치명" : 로컬에 앞에 이름으로 브랜치를 만들어서 뒤에 이름의 원격의 브랜치를 가져온다는 뜻
- git branch -D "브랜치명" : 로컬 브랜치 삭제
- git push -d "원격명" "브랜치명" : 원격 브랜치 삭제
- git merge "브랜치명" : master에서 다른 브랜치를 병합하고 싶다면, master 브랜치로 이동한 후 병합하고 싶은 브랜치명을 입력해주면 된다.
- gitk : 지금까지 진행된 git 내용을 그래픽으로 볼 수 있다(시간/작성자 기록도 볼 수 있음)

## How to remove file or directory from the staging area

- git reset HEAD -- \<file> or -- \<directoryName>
- Your modifications will be kept. When you run git status the file will once again show up as modified but not yet staged

## Tips

- Google에서 "git 커밋 메시지 작성법"을 검색하면 git을 사용할 때 좋은 방법이 나오니 참고해서 사용할 것
