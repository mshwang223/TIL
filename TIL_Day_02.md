# Git hub 두 번째 날



## 주의 사항

1. Git hub에서 절대 수정하지 말 것.
2. Git init 이 후 안의 폴더, 상위 폴더에 Git init 하지 말 것.
   (내가 관리할 프로젝트 폴더에만)

### .ignore : 버전 관리하고 싶지 않은 파일들 관리



- 주의 : 한번 버전 관리한 파일은 무시할 수 없다.

- 따라서 프로젝트 시작할 때 바로 생성한다.(README.md, .gitignore) 

- 참조 : https://www.toptal.com/developers/gitignore/

### Clone -> Download, Pull -> Update, Push -> Upload



- git config --global init.defaultBranch : Git Bash의 Master 변경
   git branch -m master
- 조별 실습 조장 : Github 주인 조원 1, 조원 2 
- .git 폴더 안 index 파일은 Stagin Area 를 담당한다.
- branch 목록 확인 : git branch
- branch 생성 : git branch hotfix
- branch 간 이동 : git switch '브랜치명'
- branch 병합 : (상용 위치에서 병합)
   git merge master
   git merge hotfix
- branch 삭제 : git branch -d hotfix



### [Merge 3가지 상황]



1. Fast - Forward(빨리감기)

2. Auto - merging(자동병합)

3. Conflict(충돌)

   

### Pull Request(PR) : branch & merge & Git hub   * 반영 요청



1. 소유권 없는 경우 -> Forking Request

2. git remote add upstream 'URL' : 다른 유저가 작업한 내용이 있을 수 있기 때문에


   회사 계정 병합할 때 : merge pull request

3. 조별 과제 : https://github.com/kylekyle123/acrostic-poem

   

### 참조. 자바 이클립스 Git Bash 연동 : https://wakestand.tistory.com/345