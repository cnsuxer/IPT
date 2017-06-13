# **IPT** - **I**'m **P**ublisher **T**oo

> 안녕하세요.LG CNS UX팀 퍼블리싱 스터디를 위한 저장소입니다. 
> 
> 본 가이드를 참조하여 설치 및 환경을 구성해주시면 됩니다.


## 설치 파일

1. [git 다운로드 페이지](https://git-scm.com/)

2. [VScode 다운로드 페이지](https://code.visualstudio.com/)


## git 사용 방법

1. 자신의 로컬에 저장할 폴더를 하나 만들어 줍니다.
2. 해당 폴더에 들어가서 마우스 오른쪽 클릭하여 `git Base here`를 실행합니다.
3. 명령창에 `git clone https://github.com/cnsuxer/IPT.git`를 입력하여 원격저장소를 로컬 저장소로 복제합니다.
4. 로컬 저장소를 원격 저장소에 맞춰 갱신: `git pull`
5. 파일들을 수정 후에 작업에 추가: `git add <파일 이름> git add *`
6. 추가된 작업들을 확정: `git commit -m "수정파일에 대한 설명"`
7. 원격저장소안 'master'브랜치에 등록: `git push origin master`


## VScode 사용 방법

1. 자신이 원하는 폴더로 가서 `shift+마우스 오른쪽` 클릭 후 명령창에 `code ./` 입력해서 해당폴더에서 프로젝트 시작
2. extension메뉴에서 필요한 플러그인 설치합니다.

   - `HTML Snippets`
   - `Beautify`
   - `Meterial Icon Theme`
   - `CSS Peek`
   - `IntelliSense for CSS class names`


## git 사용규칙

예제 폴더에 있는 파일들은 수정하지 말고,

개인폴더 안에서 각자 프로젝트를 관리/수정하여 원격저장소에 올립니다.

커밋했는데.. 다시 현재 버전으로 돌아가고 싶을 때: `git reset HEAD^`


