# 1. Git 기본
## 1-1. push

git init
- 디렉터리 생성하고 git init 하면 그 위치에 git 저장소 생성 (.git)<br>

git add
- 로컬 작업내용을 스테이징 영역으로 넘기기<br> 
- 전체 : git add .<br>
- 특정 파일 : git add file_name.md<br>

git commit
- git commit -m "message" : 메세지 꼭넣어야함 / 안넣으면 메세지 넣는 vi열림 
- 패키징하는 작업

git push
- 원격저장소로 저장하는 작업 : git push origin main
- origin 저장소 / main 브랜치에 저장 : git push origin main
	- origin : 새 레퍼지토리 생성하면 기본값으로 origin으로 생성됨
	- main : 브랜치 이름
