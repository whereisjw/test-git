# 깃허브 업로드 순서

#### 1.GitHub Repository(원격저장소) 생성 :JavaScript

local repository (로컬저장소) : c/dev/javascript
git 명령어

#### 1)javascript git 폴더 초기화 - $git init

#### 2) 원격 저장소와 연결(순서상관없음) - $git remote add origin 원격저장소주소

#### 3)readme.md파일 생성

#### 4)스테이지에 올리기 - $git add [파일 혹은 폴더명]

#### 5)스테이지 상태확인 $git status

#### 6)로컬 레파지토리에 올리기$git commit -m "메세지이름"

#### 7)원격 저장소 연결 확인(상세) - $git remote show origin

#### 8)원격 저장소에 올리기 $git push origin -u master (-u는 최초만 주고 그 다음 부터 생략가능)
***
***
***
# merge 팀프로젝트용
### 1
git branch 이름   브랜치만들기
git switch 이름    해당 브랜치로 이동
git status 로 확인
### 2
#### git switch 메인,마스터    (마스터로 이동)
#### git merge 브랜치명
다른파일을 건들였으면 정상적으로 합쳐짐, 같은파일을 수정했을경우 충돌(conflict)이 일어남



