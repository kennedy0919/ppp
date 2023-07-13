git = 분산 버전 관리 시스템
        버전 관리 시스템이란? -> 파일에 날짜와 시간 기억하기 좋음

git의 3가지 영역
Working directory (작업영역) 
Staging Area (중간단계 버전관리가 필요한 파일들은 여기를 거처감), 
Repository (변경사항을 기록하는곳)

Working directory 에 git add 를 입력하면 Staging Area로 이동함
                           git add .을 입력하면 모두 Staging Area로 이동함
git commit -m 을 입력하면 파일이 저장됨

git의 동작
git init -> 이곳을 저장소로 만들겠다! ()

git init 주의사항
- git 로컬 저장소 내에 또다른 git 로컬 저장소를 만들지 말것!!


이동하고 싶은 폴더 명령어 cd
origin master(별명 master) 사용하기

gitignore 특정 파일이나 폴더를 추적하지 않도록 설정하는것
            프로젝트에 따라 공유하지 않아야 하는 것들도 존재하기 때문 
.gitignore 파일생성(확장자 없음)
이미 git의 관리를 받은 파일은 나중에 gitignore에 작성해도 적용되지 않음