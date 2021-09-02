# git 시작하기 



## git이 뭘까요?

- 분산 버전 관리 시스템 
  - 코드의 히스토리(버전)을 관리하는 도구
  - 개발되어온 과정 파악 가능
  - 이전 버전과의 변경 사항 비교 및 분석 





중앙형과 분산형을 이해하기

중앙형 - 중앙에서 데이터 백업 및 전송 ex) 은행

분산형 - 블록체인 처럼 전체가 공통 데이터 백업 및 전송 





<Git와 GitHub눈 서로 같은 걸까? => NO! >

* Git : 분산 버전 관리 시스템
* GitHub : Git 기반의 저장소 서비스



Git 시작하기.

1. Git은 명령어를 통해서 사용 (CLI / Command - Line Interface)

         - 주요 Unix/Linux 명령어  
         - 현재 위치의 폴더, 파일 목록보기 : ls
         - 현재 위치 이동하기 cd <path>
         - ​                                  cd.. 상위폴더로 이동 
         - 폴더 생성하기 mkdir <name>
         - 파일 생성하기 touch <name>
         - 파일 삭제하기 rm <name> 파일 삭제 
         - ​                         rm -r <name>  폴더삭제



Git 기본기 

<RacingGround 프로젝트 생성>

1. 폴더생성

2. 파일생성

3. git init : 로컬 저장소 생성 / 첫번째 버전으로 남기는 작업  ( 특정버전으로 남긴다

   ​                                                       = 커밋(Commit한다.)

4. 커밋은 

    Working Directory - 내가 작업하고 있는 실제 디렉토리

   Staging Area - 커밋으로 남기고 싶은, 특정 버전으로 관리하고 싶은 파일이 있는 곳

   Repository - 커밋들이 저장되는 곳 



5. git. add  파일명 또는 git. add  . 을 통해 커밋을 가능하게 함. (커밋할 준비가 된다는거)
6.   git commit -m "commit 01" / 커밋에 대한 설명추가 / 커밋 메세지는 자세하게!

