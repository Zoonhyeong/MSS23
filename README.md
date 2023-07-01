# MSS23
# 2023 여름방학 프로젝트
# 멘토 : 이준형
# 멘티 : 윤동주, 임한주

# 커밋 규칙
  - 각자 자신의 이름으로 되어있는 폴더 안에서만 작업
  - 자신의 작업한 파일을 본인의 폴더에 저장 후 커밋

# 커밋 방법
  - 로컬 안(ex : C,D 드라이브)에 본인이 원하는 위치에 폴더 생성 (ex : mss_leejunhyeong)
  - git 설치(https://taewow.tistory.com/13 참고)
    깃(git) 설치
    1. 구글에서 "깃 설치" 검색 
    	(https://git-scm.com/book/ko/v2/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-Git-%EC%84%A4%EC%B9%98)
    2. 왼쪽 메뉴에서 Downloads 클릭 > window > 64-bit Git for Windows Setup 다운로드 > 실행
    3. next 눌러서 설치 진행

  - git bash 설치(https://xangmin.tistory.com/102 참고)
  - 본인이 생성한 폴더 우클릭하고 git bash 열기
  - git bash cmd창에 다음과 같이 작성
    1. 작업할 경로 찾기
	    	- 작업 경로에 폴더 생성하고 우클릭 > git bash here 클릭하거나
		    - cmder_mini 열어서 cd로 파일 경로 찾아줌
    2. 처음 생성해서 git 접속을 할 경우 git local repository 생성 시켜주기
	    	- git init
    3. git hub 저장소와 원격으로 연결
    		- git remote add origin https://github.com/Zoonhyeong/MSS23.git
			                          ---------------------------------------
							                         				깃허브 주소
    4. git hub 저장소에 있는 파일들을 가져오기 (신버전으로 업데이트)
    		- git pull origin master
    		※ refusing to merge unrelated historis 에러 발생 시
    		- git pull origin master --allow-unrelated-histories From 
    				https://github.com/Zoonhyeong/MSS23.git
    
    ----------------------------------------------------------------------------------------
    5. push를 할 파일 컴퓨터에서 가져오기
    		- git add .
    6. 선택한 파일들을 커밋하고 커밋 내용 작성해주기
    		- git commit -m "커밋할 내용"
    7. 커밋한 ㅡ 저장소에 push 하여 업로드하기
    		- git push -u origin master

   
